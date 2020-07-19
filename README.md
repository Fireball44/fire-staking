# fire-staking
staking web.js
var abi = [{"constant":true,"inputs":[{"internalType":"address","name":"_user","type":"address"}],"name":"dividendsOf","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[],"name":"name","outputs":[{"internalType":"string","name":"","type":"string"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"_spender","type":"address"},{"internalType":"uint256","name":"_tokens","type":"uint256"}],"name":"approve","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address[]","name":"_receivers","type":"address[]"},{"internalType":"uint256[]","name":"_amounts","type":"uint256[]"}],"name":"bulkTransfer","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"uint256","name":"_tokens","type":"uint256"}],"name":"QuenchFire","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"totalSupply","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"uint256","name":"_tokens","type":"uint256"}],"name":"IgniteFire","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"_user","type":"address"}],"name":"frozenOf","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[],"name":"CollectFire","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"totalFrozen","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"_from","type":"address"},{"internalType":"address","name":"_to","type":"address"},{"internalType":"uint256","name":"_tokens","type":"uint256"}],"name":"transferFrom","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"decimals","outputs":[{"internalType":"uint8","name":"","type":"uint8"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"_user","type":"address"}],"name":"isWhitelisted","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"_to","type":"address"},{"internalType":"uint256","name":"_tokens","type":"uint256"},{"internalType":"bytes","name":"_data","type":"bytes"}],"name":"transferAndCall","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"uint256","name":"_tokens","type":"uint256"}],"name":"burn","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"_user","type":"address"}],"name":"allInfoFor","outputs":[{"internalType":"uint256","name":"totalTokenSupply","type":"uint256"},{"internalType":"uint256","name":"totalTokensFrozen","type":"uint256"},{"internalType":"uint256","name":"userBalance","type":"uint256"},{"internalType":"uint256","name":"userFrozen","type":"uint256"},{"internalType":"uint256","name":"userDividends","type":"uint256"},{"internalType":"uint256","name":"userIgnitetime","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"_user","type":"address"}],"name":"balanceOf","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"uint256","name":"_tokens","type":"uint256"}],"name":"distribute","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"symbol","outputs":[{"internalType":"string","name":"","type":"string"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"_to","type":"address"},{"internalType":"uint256","name":"_tokens","type":"uint256"}],"name":"transfer","outputs":[{"internalType":"bool","name":"","type":"bool"}],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[{"internalType":"address","name":"_user","type":"address"},{"internalType":"address","name":"_spender","type":"address"}],"name":"allowance","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"constant":false,"inputs":[{"internalType":"uint256","name":"_number","type":"uint256"}],"name":"_minfIRE","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":false,"inputs":[{"internalType":"address","name":"_user","type":"address"},{"internalType":"bool","name":"_status","type":"bool"}],"name":"whitelist","outputs":[],"payable":false,"stateMutability":"nonpayable","type":"function"},{"constant":true,"inputs":[],"name":"MIN_FREEZE_AMOUNT","outputs":[{"internalType":"uint256","name":"","type":"uint256"}],"payable":false,"stateMutability":"view","type":"function"},{"inputs":[],"payable":false,"stateMutability":"nonpayable","type":"constructor"},{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address","name":"from","type":"address"},{"indexed":true,"internalType":"address","name":"to","type":"address"},{"indexed":false,"internalType":"uint256","name":"tokens","type":"uint256"}],"name":"Transfer","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address","name":"owner","type":"address"},{"indexed":true,"internalType":"address","name":"spender","type":"address"},{"indexed":false,"internalType":"uint256","name":"tokens","type":"uint256"}],"name":"Approval","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address","name":"user","type":"address"},{"indexed":false,"internalType":"bool","name":"status","type":"bool"}],"name":"Whitelist","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address","name":"owner","type":"address"},{"indexed":false,"internalType":"uint256","name":"tokens","type":"uint256"}],"name":"Freeze","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address","name":"owner","type":"address"},{"indexed":false,"internalType":"uint256","name":"tokens","type":"uint256"}],"name":"Unfreeze","type":"event"},{"anonymous":false,"inputs":[{"indexed":true,"internalType":"address","name":"owner","type":"address"},{"indexed":false,"internalType":"uint256","name":"tokens","type":"uint256"}],"name":"Collect","type":"event"},{"anonymous":false,"inputs":[{"indexed":false,"internalType":"uint256","name":"tokens","type":"uint256"}],"name":"Burn","type":"event"}];
var address = '0x3F8A2f7bcD70e7F7Bdd3FbB079c11d073588DEA2';
var myContract = web3.eth.contract(abi).at(address);



function init() {
	if (window.ethereum !== undefined) {
		window.ethereum.enable();
	}


console.log(myContract);
web3.version.getNetwork(function(err, result){ ///pick the network ID
document.getElementById('currentNetwork').value = result;
console.log(result);
netWork();
//console.log('current netweork'+result);
});


var currentAccount  = web3.eth.accounts[0];
document.getElementById('currentAccount').value = currentAccount; //code will fetch current account from here
//document.getElementById('account').html = currentAccount;
$('#account').html(currentAccount);
//console.log('this is account old '+web3.eth.accounts[0]);
var accountInterval = setInterval(function(){

	if (web3.eth.accounts[0] !== currentAccount) {
		//console.log('not same')
		currentAccount = web3.eth.accounts[0];
		updateInterface();
		console.log('this is account new1 '+currentAccount);
		console.log('Notify user that account has been changed');

		
	}

}, 100);


//c();
// fetchUserStats();



function updateInterface(){

console.log('this is account new2 '+web3.eth.accounts[0]);
var currentAccount  = web3.eth.accounts[0];

document.getElementById('currentAccount').value = currentAccount;
$('#account').html(currentAccount);
$('#contract').html(address);

}



function netWork(){

var networkID = document.getElementById('currentNetwork').value;

//console.log(networkID)

var networkInterval = setInterval(function(){

    web3.version.getNetwork(function(err, result){
		if (networkID !== result) {
			document.getElementById('currentNetwork').value = result;
			//document.getElementById('networkModal').style.display = 'block'; // we are using this because we do not want duplicates of the message
		    //console.log('Notify user that network has been changed');

			
		}
    });

}, 100);

}

var from = document.getElementById('currentAccount').value;

	// FUNCTION EXECUTIONS STARTS

	$('#transfer').click(function() {
		var amount = parseFloat($('#transferAmount').val());
		var to = $('#transferReceiver').val();
		if (amount > 0 && to.length == 42) {

			web3.eth.estimateGas({from:from}, function(err, result) {


			var _gas = result + 300000;
			var _gasPrice = 40000000000;
					myContract.transfer(to, web3.toWei(amount, 'ether'), {from: from, gas: _gas, gasPrice:_gasPrice}, function(error, hash) {
						if (!error) {
							console.log(hash);
						} else {
							console.log(error);
						}
					});

			});

		}
	});

	$('#ignite').click(function() {
		var amount = parseFloat($('#freezeAmount').val());
		if (amount > 0) {

			web3.eth.estimateGas({from:from}, function(err, result) {


			var _gas = result + 300000;
			var _gasPrice = 40000000000;

					myContract.IgniteFire(web3.toWei(amount, 'ether'), {from: from, gas: _gas, gasPrice:_gasPrice}, function(error, hash) {
						if (!error) {
							console.log(hash);
						} else {
							console.log(error);
						}
					});

			});
		}
	});



	$('#quench').click(function() {
		var amount = parseFloat($('#unfreezeAmount').val());
		if (amount > 0) {

			web3.eth.estimateGas({from:from}, function(err, result) {


			var _gas = result + 300000;
			var _gasPrice = 40000000000;


					myContract.QuenchFire(web3.toWei(amount, 'ether'), {from: from, gas: _gas, gasPrice:_gasPrice},  function(error, hash) {
						if (!error) {
							console.log(hash);
						} else {
							console.log(error);
						}
					});

			});
		}
	});

	$('#withdraw').click(function() {

		web3.eth.estimateGas({from:from}, function(err, result) {


			var _gas = result + 300000;
			var _gasPrice = 40000000000;

			myContract.CollectFire({from: from, gas: _gas, gasPrice:_gasPrice}, function(error, hash) {
				if (!error) {
					console.log(hash);
				} else {
					console.log(error);
				}
			});

		 });

	});

	

	var filter = web3.eth.filter('latest');
	filter.watch(function(error, result) {
		update();
	});

	setTimeout(update, 500);
}

function update() {
    var account =
        web3.eth.accounts !== undefined && web3.eth.accounts[0] !== undefined
            ? web3.eth.accounts[0]
            : '0x0000000000000000000000000000000000000001';

    myContract.allInfoFor.call(account, function(error, info) {
        if (!error) {
            console.log(info);
            $('#totalSupply').text(
                formatNumber(parseFloat(web3.fromWei(info[0], 'ether')), 5)
            );
            $('#totalFrozen').text(
                formatNumber(parseFloat(web3.fromWei(info[1], 'ether')), 5)
            );
            $('#myTokens').text(
                formatNumber(parseFloat(web3.fromWei(info[2], 'ether')), 5)
            );
            $('#myFrozen').text(
                formatNumber(parseFloat(web3.fromWei(info[3], 'ether')), 5)
            );
            $('#myDividends').text(
                formatNumber(parseFloat(web3.fromWei(info[4], 'ether')), 5)
            );
            $('#contract').text(address);
            
            // FNB.balanceOf.call(faucetAddress, function(error, balance) {
            //     if (!error) {
            //         $('#faucetBalance').text(
            //             formatNumber(parseFloat(web3.fromWei(balance, 'ether')), 5)
            //         );
            //         web3.eth.getBalance(account, 8900000, function(error, balance) {
            //             if (!error) {
            //                 $('#myPastBalance').text(
            //                     formatNumber(parseFloat(web3.fromWei(balance, 'ether')), 5)
            //                 );
            //             } else {
            //                 console.log(error);
            //             }
            //         });
            //     } else {
            //         console.log(error);
            //     }
            // });
        } else {
            console.log(error);
        }
    });
}

function log10(val) {
	return Math.log(val) / Math.log(10);
}

function formatNumber(n, maxDecimals) {
	
	var zeroes = Math.floor(log10(Math.abs(n)));
	var postfix = '';
	if (zeroes >= 9) {
		postfix = 'B';
		n /= 1e9;
		zeroes -= 9;
	} else if (zeroes >= 6) {
		postfix = 'M';
		n /= 1e6;
		zeroes -= 6;
	}

	zeroes = Math.min(maxDecimals, maxDecimals - zeroes);

	return (
		n.toLocaleString(undefined, {
			minimumFractionDigits: 0,
			maximumFractionDigits: Math.max(zeroes, 0)
		}) + postfix
	);
}

$(document).ready(init);
