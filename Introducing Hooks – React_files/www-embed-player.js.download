(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var l;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var ea=ca(this);function n(a,b){if(b)a:{var c=ea;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
n("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.i=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.i};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
n("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=ea[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ha(aa(this))}})}return a});
function ha(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function p(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ia(a){if(!(a instanceof Array)){a=p(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ja(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ka="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ja(d,e)&&(a[e]=d[e])}return a};
n("Object.assign",function(a){return a||ka});
var na="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},pa=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=na(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),qa;
if("function"==typeof Object.setPrototypeOf)qa=Object.setPrototypeOf;else{var ra;a:{var sa={a:!0},ta={};try{ta.__proto__=sa;ra=ta.a;break a}catch(a){}ra=!1}qa=ra?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ua=qa;
function u(a,b){a.prototype=na(b.prototype);a.prototype.constructor=a;if(ua)ua(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Z=b.prototype}
function va(){this.C=!1;this.m=null;this.j=void 0;this.i=1;this.o=this.s=0;this.u=this.l=null}
function wa(a){if(a.C)throw new TypeError("Generator is already running");a.C=!0}
va.prototype.O=function(a){this.j=a};
function xa(a,b){a.l={cc:b,kc:!0};a.i=a.s||a.o}
va.prototype.return=function(a){this.l={return:a};this.i=this.o};
function v(a,b,c){a.i=c;return{value:b}}
va.prototype.B=function(a){this.i=a};
function ya(a,b,c){a.s=b;void 0!=c&&(a.o=c)}
function za(a,b){a.i=b;a.s=0}
function Aa(a){a.s=0;var b=a.l.cc;a.l=null;return b}
function Ba(a){a.u=[a.l];a.s=0;a.o=0}
function Ca(a){var b=a.u.splice(0)[0];(b=a.l=a.l||b)?b.kc?a.i=a.s||a.o:void 0!=b.B&&a.o<b.B?(a.i=b.B,a.l=null):a.i=a.o:a.i=0}
function Da(a){this.i=new va;this.j=a}
function Ea(a,b){wa(a.i);var c=a.i.m;if(c)return Fa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.i.return);
a.i.return(b);return Ga(a)}
function Fa(a,b,c,d){try{var e=b.call(a.i.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.i.C=!1,e;var f=e.value}catch(g){return a.i.m=null,xa(a.i,g),Ga(a)}a.i.m=null;d.call(a.i,f);return Ga(a)}
function Ga(a){for(;a.i.i;)try{var b=a.j(a.i);if(b)return a.i.C=!1,{value:b.value,done:!1}}catch(c){a.i.j=void 0,xa(a.i,c)}a.i.C=!1;if(a.i.l){b=a.i.l;a.i.l=null;if(b.kc)throw b.cc;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ha(a){this.next=function(b){wa(a.i);a.i.m?b=Fa(a,a.i.m.next,b,a.i.O):(a.i.O(b),b=Ga(a));return b};
this.throw=function(b){wa(a.i);a.i.m?b=Fa(a,a.i.m["throw"],b,a.i.O):(xa(a.i,b),b=Ga(a));return b};
this.return=function(b){return Ea(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ia(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function x(a){return Ia(new Ha(new Da(a)))}
function Ja(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
n("Reflect",function(a){return a?a:{}});
n("Reflect.construct",function(){return pa});
n("Reflect.setPrototypeOf",function(a){return a?a:ua?function(b,c){try{return ua(b,c),!0}catch(d){return!1}}:null});
n("Promise",function(a){function b(g){this.i=0;this.l=void 0;this.j=[];this.C=!1;var h=this.m();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.i=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.j=function(g){if(null==this.i){this.i=[];var h=this;this.l(function(){h.o()})}this.i.push(g)};
var e=ea.setTimeout;c.prototype.l=function(g){e(g,0)};
c.prototype.o=function(){for(;this.i&&this.i.length;){var g=this.i;this.i=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(m){this.m(m)}}}this.i=null};
c.prototype.m=function(g){this.l(function(){throw g;})};
b.prototype.m=function(){function g(m){return function(q){k||(k=!0,m.call(h,q))}}
var h=this,k=!1;return{resolve:g(this.L),reject:g(this.o)}};
b.prototype.L=function(g){if(g===this)this.o(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.R(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.K(g):this.s(g)}};
b.prototype.K=function(g){var h=void 0;try{h=g.then}catch(k){this.o(k);return}"function"==typeof h?this.T(h,g):this.s(g)};
b.prototype.o=function(g){this.O(2,g)};
b.prototype.s=function(g){this.O(1,g)};
b.prototype.O=function(g,h){if(0!=this.i)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.i);this.i=g;this.l=h;2===this.i&&this.P();this.u()};
b.prototype.P=function(){var g=this;e(function(){if(g.H()){var h=ea.console;"undefined"!==typeof h&&h.error(g.l)}},1)};
b.prototype.H=function(){if(this.C)return!1;var g=ea.CustomEvent,h=ea.Event,k=ea.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=ea.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.l;return k(g)};
b.prototype.u=function(){if(null!=this.j){for(var g=0;g<this.j.length;++g)f.j(this.j[g]);this.j=null}};
var f=new c;b.prototype.R=function(g){var h=this.m();g.bb(h.resolve,h.reject)};
b.prototype.T=function(g,h){var k=this.m();try{g.call(h,k.resolve,k.reject)}catch(m){k.reject(m)}};
b.prototype.then=function(g,h){function k(w,t){return"function"==typeof w?function(z){try{m(w(z))}catch(E){q(E)}}:t}
var m,q,r=new b(function(w,t){m=w;q=t});
this.bb(k(g,m),k(h,q));return r};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.bb=function(g,h){function k(){switch(m.i){case 1:g(m.l);break;case 2:h(m.l);break;default:throw Error("Unexpected state: "+m.i);}}
var m=this;null==this.j?f.j(k):this.j.push(k);this.C=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var m=p(g),q=m.next();!q.done;q=m.next())d(q.value).bb(h,k)})};
b.all=function(g){var h=p(g),k=h.next();return k.done?d([]):new b(function(m,q){function r(z){return function(E){w[z]=E;t--;0==t&&m(w)}}
var w=[],t=0;do w.push(void 0),t++,d(k.value).bb(r(w.length-1),q),k=h.next();while(!k.done)})};
return b});
n("WeakMap",function(a){function b(k){this.i=(h+=Math.random()+1).toString();if(k){k=p(k);for(var m;!(m=k.next()).done;)m=m.value,this.set(m[0],m[1])}}
function c(){}
function d(k){var m=typeof k;return"object"===m&&null!==k||"function"===m}
function e(k){if(!ja(k,g)){var m=new c;ba(k,g,{value:m})}}
function f(k){var m=Object[k];m&&(Object[k]=function(q){if(q instanceof c)return q;Object.isExtensible(q)&&e(q);return m(q)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),m=Object.seal({}),q=new a([[k,2],[m,3]]);if(2!=q.get(k)||3!=q.get(m))return!1;q.delete(k);q.set(m,4);return!q.has(k)&&4==q.get(m)}catch(r){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,m){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ja(k,g))throw Error("WeakMap key fail: "+k);k[g][this.i]=m;return this};
b.prototype.get=function(k){return d(k)&&ja(k,g)?k[g][this.i]:void 0};
b.prototype.has=function(k){return d(k)&&ja(k,g)&&ja(k[g],this.i)};
b.prototype.delete=function(k){return d(k)&&ja(k,g)&&ja(k[g],this.i)?delete k[g][this.i]:!1};
return b});
n("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var m=h.i;return ha(function(){if(m){for(;m.head!=h.i;)m=m.previous;for(;m.next!=m.head;)return m=m.next,{done:!1,value:k(m)};m=null}return{done:!0,value:void 0}})}
function d(h,k){var m=k&&typeof k;"object"==m||"function"==m?f.has(k)?m=f.get(k):(m=""+ ++g,f.set(k,m)):m="p_"+k;var q=h.data_[m];if(q&&ja(h.data_,m))for(h=0;h<q.length;h++){var r=q[h];if(k!==k&&r.key!==r.key||k===r.key)return{id:m,list:q,index:h,entry:r}}return{id:m,list:q,index:-1,entry:void 0}}
function e(h){this.data_={};this.i=b();this.size=0;if(h){h=p(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(p([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var m=k.entries(),q=m.next();if(q.done||q.value[0]!=h||"s"!=q.value[1])return!1;q=m.next();return q.done||4!=q.value[0].x||"t"!=q.value[1]||!m.next().done?!1:!0}catch(r){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var m=d(this,h);m.list||(m.list=this.data_[m.id]=[]);m.entry?m.entry.value=k:(m.entry={next:this.i,previous:this.i.previous,head:this.i,key:h,value:k},m.list.push(m.entry),this.i.previous.next=m.entry,this.i.previous=m.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.i=this.i.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var m=this.entries(),q;!(q=m.next()).done;)q=q.value,h.call(k,q[1],q[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ka(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
n("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ka(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
n("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
n("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ka(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
n("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
n("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
n("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
function La(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
n("Array.prototype.entries",function(a){return a?a:function(){return La(this,function(b,c){return[b,c]})}});
n("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
n("Array.prototype.keys",function(a){return a?a:function(){return La(this,function(b){return b})}});
n("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
n("Object.setPrototypeOf",function(a){return a||ua});
n("Set",function(a){function b(c){this.i=new Map;if(c){c=p(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.i.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(p([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.i.set(c,c);this.size=this.i.size;return this};
b.prototype.delete=function(c){c=this.i.delete(c);this.size=this.i.size;return c};
b.prototype.clear=function(){this.i.clear();this.size=0};
b.prototype.has=function(c){return this.i.has(c)};
b.prototype.entries=function(){return this.i.entries()};
b.prototype.values=function(){return this.i.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.i.forEach(function(f){return c.call(d,f,f,e)})};
return b});
n("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ja(b,d)&&c.push([d,b[d]]);return c}});
n("Array.prototype.values",function(a){return a?a:function(){return La(this,function(b,c){return c})}});
n("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
n("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
n("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ka(this,b,"includes").indexOf(b,c||0)}});
n("globalThis",function(a){return a||ea});
n("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ja(b,d)&&c.push(b[d]);return c}});
var Ma=Ma||{},y=this||self;function A(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function B(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Na(a){a.Bb=void 0;a.getInstance=function(){return a.Bb?a.Bb:a.Bb=new a}}
function Oa(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Pa(a){var b=Oa(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Qa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ra(a){return Object.prototype.hasOwnProperty.call(a,Sa)&&a[Sa]||(a[Sa]=++Ta)}
var Sa="closure_uid_"+(1E9*Math.random()>>>0),Ta=0;function Ua(a,b,c){return a.call.apply(a.bind,arguments)}
function Va(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Xa(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Xa=Ua:Xa=Va;return Xa.apply(null,arguments)}
function Ya(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Za(a,b){function c(){}
c.prototype=b.prototype;a.Z=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.fr=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function $a(a){return a}
;function ab(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,ab);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
Za(ab,Error);ab.prototype.name="CustomError";function bb(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.l=!b&&/[?&]ae=1(&|$)/.test(a);this.m=!b&&/[?&]ae=2(&|$)/.test(a);if((this.i=/[?&]adurl=([^&]*)/.exec(a))&&this.i[1]){try{var c=decodeURIComponent(this.i[1])}catch(d){c=null}this.j=c}}
;function cb(){}
function db(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var eb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},fb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},gb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},hb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},ib=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
fb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d},jb=Array.prototype.every?function(a,b){return Array.prototype.every.call(a,b,void 0)}:function(a,b){for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&!b.call(void 0,d[e],e,a))return!1;
return!0};
function kb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function lb(a,b){b=eb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function nb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Pa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function ob(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function pb(a){var b=qb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function rb(a){for(var b in a)return!1;return!0}
function sb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function tb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function ub(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function vb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function wb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=wb(a[c]);return b}
var xb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function yb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<xb.length;f++)c=xb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var zb;function Ab(){if(void 0===zb){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:$a,createScript:$a,createScriptURL:$a})}catch(c){y.console&&y.console.error(c.message)}zb=a}else zb=a}return zb}
;function Bb(a,b){this.l=a===Cb&&b||""}
Bb.prototype.j=!0;Bb.prototype.i=function(){return this.l};
function Db(a){return new Bb(Cb,a)}
var Cb={};Db("");var Gb={};function Hb(a){this.l=Gb===Gb?a:"";this.j=!0}
Hb.prototype.toString=function(){return this.l.toString()};
Hb.prototype.i=function(){return this.l.toString()};function Ib(a,b){this.l=b===Jb?a:""}
Ib.prototype.toString=function(){return this.l+""};
Ib.prototype.j=!0;Ib.prototype.i=function(){return this.l.toString()};
function Kb(a){if(a instanceof Ib&&a.constructor===Ib)return a.l;Oa(a);return"type_error:TrustedResourceUrl"}
var Jb={};function Lb(a){var b=Ab();a=b?b.createScriptURL(a):a;return new Ib(a,Jb)}
;var Mb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function Nb(a,b){return a<b?-1:a>b?1:0}
;function Ob(a,b){this.l=b===Pb?a:""}
Ob.prototype.toString=function(){return this.l.toString()};
Ob.prototype.j=!0;Ob.prototype.i=function(){return this.l.toString()};
function Qb(a){if(a instanceof Ob&&a.constructor===Ob)return a.l;Oa(a);return"type_error:SafeUrl"}
var Rb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Pb={},Sb=new Ob("about:invalid#zClosurez",Pb);function Tb(){var a=y.navigator;return a&&(a=a.userAgent)?a:""}
function C(a){return-1!=Tb().indexOf(a)}
;function Ub(){return C("Trident")||C("MSIE")}
function Vb(){return C("Firefox")||C("FxiOS")}
function Wb(){return C("Safari")&&!(Xb()||C("Coast")||C("Opera")||C("Edge")||C("Edg/")||C("OPR")||Vb()||C("Silk")||C("Android"))}
function Xb(){return(C("Chrome")||C("CriOS"))&&!C("Edge")||C("Silk")}
function Yb(){return C("Android")&&!(Xb()||Vb()||C("Opera")||C("Silk"))}
function ac(a){var b={};a.forEach(function(c){b[c[0]]=c[1]});
return function(c){return b[c.find(function(d){return d in b})]||""}}
function bc(a){var b=Tb();if("Internet Explorer"===a){if(Ub())if((a=/rv: *([\d\.]*)/.exec(b))&&a[1])b=a[1];else{a="";var c=/MSIE +([\d\.]+)/.exec(b);if(c&&c[1])if(b=/Trident\/(\d.\d)/.exec(b),"7.0"==c[1])if(b&&b[1])switch(b[1]){case "4.0":a="8.0";break;case "5.0":a="9.0";break;case "6.0":a="10.0";break;case "7.0":a="11.0"}else a="7.0";else a=c[1];b=a}else b="";return b}var d=RegExp("([A-Z][\\w ]+)/([^\\s]+)\\s*(?:\\((.*?)\\))?","g");c=[];for(var e;e=d.exec(b);)c.push([e[1],e[2],e[3]||void 0]);b=ac(c);
switch(a){case "Opera":if(C("Opera"))return b(["Version","Opera"]);if(C("OPR"))return b(["OPR"]);break;case "Microsoft Edge":if(C("Edge"))return b(["Edge"]);if(C("Edg/"))return b(["Edg"]);break;case "Chromium":if(Xb())return b(["Chrome","CriOS","HeadlessChrome"])}return"Firefox"===a&&Vb()||"Safari"===a&&Wb()||"Android Browser"===a&&Yb()||"Silk"===a&&C("Silk")?(b=c[2])&&b[1]||"":""}
function cc(a){a=bc(a);if(""===a)return NaN;a=a.split(".");return 0===a.length?NaN:Number(a[0])}
;var dc={};function ec(a){this.l=dc===dc?a:"";this.j=!0}
ec.prototype.i=function(){return this.l.toString()};
ec.prototype.toString=function(){return this.l.toString()};function fc(a,b){b instanceof Ob||b instanceof Ob||(b="object"==typeof b&&b.j?b.i():String(b),Rb.test(b)||(b="about:invalid#zClosurez"),b=new Ob(b,Pb));a.href=Qb(b)}
function gc(a,b){a.rel="stylesheet";a.href=Kb(b).toString();(b=hc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function ic(){return hc("script[nonce]")}
var jc=/^[\w+/_-]+[=]{0,2}$/;function hc(a,b){b=(b||y).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&jc.test(a)?a:"":""}
;function kc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var lc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function mc(a){return a?decodeURI(a):a}
function nc(a,b){return b.match(lc)[a]||null}
function oc(a){return mc(nc(3,a))}
function pc(a){var b=a.match(lc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function qc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function rc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)rc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function sc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)rc(a[b],a[b+1],c);return c.join("&")}
function tc(a){var b=[],c;for(c in a)rc(c,a[c],b);return b.join("&")}
function uc(a,b){var c=2==arguments.length?sc(arguments[1],0):sc(arguments,1);return qc(a,c)}
function vc(a,b){b=tc(b);return qc(a,b)}
function wc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return qc(a,b+c)}
function Ac(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var Bc=/#|$/,Cc=/[?&]($|#)/;function Dc(a,b){for(var c=a.search(Bc),d=0,e,f=[];0<=(e=Ac(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(Cc,"$1")}
;function Ec(){return C("iPhone")&&!C("iPod")&&!C("iPad")}
function Fc(){var a=Tb();if(C("Windows")){var b=/Windows (?:NT|Phone) ([0-9.]+)/;b.exec(a)}else Ec()||C("iPad")||C("iPod")?(b=/(?:iPhone|iPod|iPad|CPU)\s+OS\s+(\S+)/,(a=b.exec(a))&&a[1].replace(/_/g,".")):C("Macintosh")?(b=/Mac OS X ([0-9_.]+)/,(a=b.exec(a))&&a[1].replace(/_/g,".")):-1!=Tb().toLowerCase().indexOf("kaios")?(b=/(?:KaiOS)\/(\S+)/i,b.exec(a)):C("Android")?(b=/Android\s+([^\);]+)(\)|;)/,b.exec(a)):C("CrOS")&&(b=/(?:CrOS\s+(?:i686|x86_64)\s+([0-9.]+))/,b.exec(a))}
;function Gc(a){Gc[" "](a);return a}
Gc[" "]=function(){};
function Hc(a){var b=Ic;return Object.prototype.hasOwnProperty.call(b,9)?b[9]:b[9]=a(9)}
;var Jc=C("Opera"),Kc=Ub(),Lc=C("Edge"),Mc=C("Gecko")&&!(-1!=Tb().toLowerCase().indexOf("webkit")&&!C("Edge"))&&!(C("Trident")||C("MSIE"))&&!C("Edge"),Nc=-1!=Tb().toLowerCase().indexOf("webkit")&&!C("Edge"),Oc=C("Android");function Pc(){var a=y.document;return a?a.documentMode:void 0}
var Qc;a:{var Rc="",Sc=function(){var a=Tb();if(Mc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Lc)return/Edge\/([\d\.]+)/.exec(a);if(Kc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Nc)return/WebKit\/(\S+)/.exec(a);if(Jc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Sc&&(Rc=Sc?Sc[1]:"");if(Kc){var Tc=Pc();if(null!=Tc&&Tc>parseFloat(Rc)){Qc=String(Tc);break a}}Qc=Rc}var Uc=Qc,Ic={};
function Vc(){return Hc(function(){for(var a=0,b=Mb(String(Uc)).split("."),c=Mb("9").split("."),d=Math.max(b.length,c.length),e=0;0==a&&e<d;e++){var f=b[e]||"",g=c[e]||"";do{f=/(\d*)(\D*)(.*)/.exec(f)||["","","",""];g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];if(0==f[0].length&&0==g[0].length)break;a=Nb(0==f[1].length?0:parseInt(f[1],10),0==g[1].length?0:parseInt(g[1],10))||Nb(0==f[2].length,0==g[2].length)||Nb(f[2],g[2]);f=f[3];g=g[3]}while(0==a)}return 0<=a})}
var Wc;if(y.document&&Kc){var Xc=Pc();Wc=Xc?Xc:parseInt(Uc,10)||void 0}else Wc=void 0;var Yc=Wc;var Zc=Ec()||C("iPod"),$c=C("iPad");Yb();Xb();var ad=Wb()&&!(Ec()||C("iPad")||C("iPod"));var bd={},cd=null;
function dd(a,b){Pa(a);void 0===b&&(b=0);if(!cd){cd={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));bd[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===cd[h]&&(cd[h]=g)}}}b=bd[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],m=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|m>>4];m=b[(m&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+m+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var ed="undefined"!==typeof Uint8Array;function fd(a){return ed&&null!=a&&a instanceof Uint8Array}
var gd={};var hd;function id(a,b){if(b!==gd)throw Error("illegal external caller");this.ka=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
function jd(){return hd||(hd=new id(null,gd))}
id.prototype.isEmpty=function(){return null==this.ka};var kd="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol(void 0):void 0;function ld(a,b){Object.isFrozen(a)||(kd?a[kd]|=b:void 0!==a.fa?a.fa|=b:Object.defineProperties(a,{fa:{value:b,configurable:!0,writable:!0,enumerable:!1}}))}
function md(a,b){Object.isExtensible(a)&&(kd?a[kd]&&(a[kd]&=~b):void 0!==a.fa&&(a.fa&=~b))}
function nd(a){var b;kd?b=a[kd]:b=a.fa;return null==b?0:b}
function od(a,b){kd?a[kd]=b:void 0!==a.fa?a.fa=b:Object.defineProperties(a,{fa:{value:b,configurable:!0,writable:!0,enumerable:!1}})}
function td(a){ld(a,1);return a}
function ud(a){ld(a,17);return a}
function vd(a){return a?!!(nd(a)&2):!1}
function wd(a){ld(a,16);return a}
function xd(a){if(!Array.isArray(a))throw Error("cannot mark non-array as shared mutably");md(a,16)}
function yd(a,b){od(b,(nd(a)|0)&-51)}
;var zd={};function Ad(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var Bd,Cd=Object.freeze(td([]));function Dd(a){if(vd(a.v))throw Error("Cannot mutate an immutable Message");}
;function Ed(a){return a.displayName||a.name||"unknown type name"}
function Fd(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Ed(b)+" but got "+(a&&Ed(a.constructor)));return a}
;function Gd(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(a&&!Array.isArray(a)){if(fd(a))return dd(a);if(a instanceof id){var b=a.ka;return null==b?"":"string"===typeof b?b:a.ka=dd(b)}}}return a}
;function Hd(a,b,c,d){if(null!=a){if(Array.isArray(a))a=Id(a,b,c,void 0!==d);else if(Ad(a)){var e={},f;for(f in a)e[f]=Hd(a[f],b,c,d);a=e}else a=b(a,d);return a}}
function Id(a,b,c,d){d=d?!!(nd(a)&16):void 0;var e=Array.prototype.slice.call(a);c(a,e);for(a=0;a<e.length;a++)e[a]=Hd(e[a],b,c,d);return e}
function Jd(a){return a.Eb===zd?a.toJSON():Gd(a)}
function Kd(a){if(!a)return a;if("object"===typeof a){if(fd(a))return new Uint8Array(a);if(a.Eb===zd)return a.clone()}return a}
function Ld(){}
;function Md(a,b,c){return-1===b?null:b>=a.qa?a.S?a.S[b]:void 0:(void 0===c?0:c)&&a.S&&(c=a.S[b],null!=c)?c:a.v[b+a.ma]}
function D(a,b,c,d,e){d=void 0===d?!1:d;(void 0===e?0:e)||Dd(a);a.jc&&(a.jc=void 0);if(b>=a.qa||d)return(a.S||(a.S=a.v[a.qa+a.ma]={}))[b]=c,a;void 0!==a.S&&a.qa>=a.v.length?(d=a.v.length-1,e=b+a.ma,e>=d?(a.v[d]=void 0,a.v[e]=c,a.v.push(a.S)):a.v[e]=c):a.v[b+a.ma]=c;void 0!==a.S&&b in a.S&&delete a.S[b];return a}
function Nd(a,b,c,d){var e=Md(a,b,d);Array.isArray(e)||(e=Cd);var f=nd(e);f&1||td(e);vd(a.v)?c&1||(ld(e,2),Object.freeze(e)):e===Cd||!(c&1&&c&2)&&f&2?(e=td(Array.prototype.slice.call(e)),D(a,b,e,d)):!(c&2)&&f&16&&xd(e);return e}
function Od(a,b,c,d){Dd(a);(c=Pd(a,c))&&c!==b&&null!=d&&D(a,c,void 0,!1);return D(a,b,d)}
function Pd(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Md(a,e)&&(0!==c&&D(a,c,void 0,!1,!0),c=e)}return c}
function Qd(a,b,c,d){var e=d=void 0===d?!1:d,f=Md(a,c,e);var g=!1;var h=null==f||"object"!==typeof f||(g=Array.isArray(f))||f.Eb!==zd?g?new b(f):void 0:f;h!==f&&null!=h&&(D(a,c,h,e,!0),ld(h.v,nd(a.v)&-33));b=h;if(null==b)return b;vd(b.v)&&!vd(a.v)&&(b=Rd(b),D(a,c,b,d));return b}
function Sd(a,b,c,d,e){e=void 0===e?!0:e;a.i||(a.i={});var f=a.i[c];d=Nd(a,c,2|(e?1:0),d);var g=!!(nd(a.v)&16),h=vd(d);h=vd(a.v)||h;if(!f){f=[];for(var k=h,m=0;m<d.length;m++){var q=d[m];k=k||vd(q);var r=b,w=g,t=!1;t=void 0===t?!1:t;w=void 0===w?!1:w;q=Array.isArray(q)?new r(w?wd(q):q):t?new r:void 0;void 0!==q&&(f.push(q),h&&ld(q.v,2))}a.i[c]=f;b=!k;Object.isFrozen(d)||(g=nd(d)|33,od(d,b?g|8:g&-9))}e=h||e;d=vd(f);e&&!d&&(Object.isFrozen(f)&&(a.i[c]=f=f.slice()),ld(f,2),Object.freeze(f));!e&&d&&(a.i[c]=
f=f.slice());return f}
function Td(a,b,c,d){d=void 0===d?!1:d;var e=vd(a.v);b=Sd(a,b,c,d,e);a=Nd(a,c,3,d);if(e=!e&&a){if(!a)throw Error("cannot check mutability state of non-array");e=!(nd(a)&8)}if(e){for(e=0;e<b.length;e++)(c=b[e])&&vd(c.v)&&(c=e,d=Rd(b[e]),b[c]=d,a[e]=b[e].v);ld(a,8)}return b}
function G(a,b,c,d){Dd(a);null!=d?Fd(d,b):d=void 0;return D(a,c,d)}
function Ud(a,b,c,d,e){Dd(a);null!=e?Fd(e,b):e=void 0;Od(a,c,d,e)}
function Vd(a,b,c,d){Dd(a);if(null!=d){var e=td([]);for(var f=!1,g=0;g<d.length;g++)e[g]=Fd(d[g],b).v,f=f||vd(e[g]);a.i||(a.i={});a.i[c]=d;b=e;f?md(b,8):ld(b,8)}else a.i&&(a.i[c]=void 0),e=Cd;return D(a,c,e)}
function Wd(a,b,c,d){Dd(a);var e=Sd(a,c,b,void 0,!1);c=null!=d?Fd(d,c):new c;a=Nd(a,b,2);e.push(c);a.push(c.v);vd(c.v)&&md(a,8)}
function Xd(a,b){return Md(a,b)}
function Yd(a,b){return null==a?b:a}
;function Zd(a,b,c,d,e,f){(a=a.i&&a.i[c])?(e=f.sb?td(a.slice()):a,Vd(b,0<e.length?e[0].constructor:void 0,c,e)):(ed&&d instanceof Uint8Array?e=d.length?new id(new Uint8Array(d),gd):jd():(Array.isArray(d)&&(e?ld(d,2):d&&nd(d)&1&&f.sb?(e=Array.prototype.slice.call(d),od(e,(nd(d)|0)&-51),d=e):xd(d)),e=d),D(b,c,e))}
;function Rd(a){if(!vd(a.v))return a;var b={sb:!0},c=vd(a.v);if(c&&!b.sb)throw Error("copyRepeatedFields must be true for frozen messages");c||xd(a.v);var d=new a.constructor;a.Ma&&(d.Ma=a.Ma.slice());for(var e=a.v,f=0;f<e.length;f++){var g=e[f];if(f===e.length-1&&Ad(g))for(var h in g){var k=+h;Number.isNaN(k)?(d.S||(d.S=d.v[d.qa+d.ma]={}))[h]=g[h]:Zd(a,d,k,g[h],c,b)}else Zd(a,d,f-a.ma,g,c,b)}d.jc=a;return d}
;function I(a,b,c){null==a&&(a=$d);$d=null;var d=this.constructor.i||0,e=0<d,f=this.constructor.j,g,h=!1;if(a){if(g=!!(nd(a)&16))h=nd(a),od(a,h|32),h=!!(h&32)}else g=f?[f]:[],ld(g,48),a=g,g=!0;e&&0<a.length&&Ad(a[a.length-1])&&"g"in a[a.length-1]&&(d=0);this.ma=(f?0:-1)-d;this.i=void 0;this.v=a;a:{f=this.v.length;d=f-1;if(f&&(f=this.v[d],Ad(f))){this.S=f;b=Object.keys(f);0<b.length&&jb(b,isNaN)?this.qa=Number.MAX_VALUE:this.qa=d-this.ma;break a}void 0!==b&&-1<b?(this.qa=Math.max(b,d+1-this.ma),this.S=
void 0):this.qa=Number.MAX_VALUE}if(!e&&this.S&&"g"in this.S)throw Error('Unexpected "g" flag in sparse object of message that is not a group type.');if(c)for(e=g&&!h?ud:td,b=0;b<c.length;b++)g=c[b],(h=Md(this,g))?Array.isArray(h)&&e(h):D(this,g,Cd,!1,!0)}
l=I.prototype;l.toJSON=function(){var a=this.v,b;Bd?b=a:b=Id(a,Jd,Ld);return b};
function ae(a){Bd=!0;try{return JSON.stringify(a.toJSON(),be)}finally{Bd=!1}}
l.clone=function(){var a=Id(this.v,Kd,yd);wd(a);$d=a;a=new this.constructor(a);$d=null;ce(a,this);return a};
l.isMutable=function(){return!vd(this.v)};
l.Eb=zd;l.toString=function(){return this.v.toString()};
function be(a,b){return Gd(b)}
function ce(a,b){b.Ma&&(a.Ma=b.Ma.slice());var c=b.i;if(c){b=b.S;for(var d in c){var e=c[d];if(e){var f=!(!b||!b[d]),g=+d;if(Array.isArray(e)){if(e.length)for(f=Td(a,e[0].constructor,g,f),g=0;g<Math.min(f.length,e.length);g++)ce(f[g],e[g])}else throw Error("unexpected object: type: "+Oa(e)+": "+e);}}}}
var $d;function de(a){var b=this.i,c=this.j;return this.isRepeated?Td(a,b,c,!0):Qd(a,b,c,!0)}
;function ee(a){this.Vb=a}
;function fe(a,b,c){this.j=a;this.m=b;this.i=c||[];this.Ca=new Map}
l=fe.prototype;l.Hc=function(a){var b=Ja.apply(1,arguments),c=this.vb(b);c?c.push(new ee(a)):this.wc(a,b)};
l.wc=function(a){this.Ca.set(this.dc(Ja.apply(1,arguments)),[new ee(a)])};
l.vb=function(){var a=this.dc(Ja.apply(0,arguments));return this.Ca.has(a)?this.Ca.get(a):void 0};
l.Tc=function(){var a=this.vb(Ja.apply(0,arguments));return a&&a.length?a[0]:void 0};
l.clear=function(){this.Ca.clear()};
l.dc=function(){var a=Ja.apply(0,arguments);return a?a.join(","):"key"};function ge(a,b){fe.call(this,a,3,b)}
u(ge,fe);ge.prototype.l=function(a){var b=Ja.apply(1,arguments),c=0,d=this.Tc(b);d&&(c=d.Vb);this.wc(c+a,b)};function he(a,b){fe.call(this,a,2,b)}
u(he,fe);he.prototype.l=function(a){this.Hc(a,Ja.apply(1,arguments))};function ie(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function je(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Pa(d)?je.apply(null,d):ie(d)}}
;function J(){this.O=this.O;this.C=this.C}
J.prototype.O=!1;J.prototype.i=function(){return this.O};
J.prototype.dispose=function(){this.O||(this.O=!0,this.D())};
function ke(a,b){le(a,Ya(ie,b))}
function le(a,b){a.O?b():(a.C||(a.C=[]),a.C.push(b))}
J.prototype.D=function(){if(this.C)for(;this.C.length;)this.C.shift()()};function me(a,b){this.type=a;this.i=this.target=b;this.defaultPrevented=this.l=!1}
me.prototype.stopPropagation=function(){this.l=!0};
me.prototype.preventDefault=function(){this.defaultPrevented=!0};function ne(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=oe(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,pe[c])c=pe[c];else{c=String(c);if(!pe[c]){var f=/function\s+([^\(]+)/m.exec(c);pe[c]=f?f[1]:"[Anonymous]"}c=pe[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function oe(a,b){b||(b={});b[qe(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[qe(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=oe(a,b));return c}
function qe(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var pe={};var re=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",function(){},b),y.removeEventListener("test",function(){},b)}catch(c){}return a}();function se(a,b){me.call(this,a?a.type:"");this.relatedTarget=this.i=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.j=null;a&&this.init(a,b)}
Za(se,me);var te={2:"touch",3:"pen",4:"mouse"};
se.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.i=b;if(b=a.relatedTarget){if(Mc){a:{try{Gc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:te[a.pointerType]||"";this.state=a.state;
this.j=a;a.defaultPrevented&&se.Z.preventDefault.call(this)};
se.prototype.stopPropagation=function(){se.Z.stopPropagation.call(this);this.j.stopPropagation?this.j.stopPropagation():this.j.cancelBubble=!0};
se.prototype.preventDefault=function(){se.Z.preventDefault.call(this);var a=this.j;a.preventDefault?a.preventDefault():a.returnValue=!1};var ze="closure_listenable_"+(1E6*Math.random()|0);var Ae=0;function Be(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.gb=e;this.key=++Ae;this.Oa=this.ab=!1}
function Ce(a){a.Oa=!0;a.listener=null;a.proxy=null;a.src=null;a.gb=null}
;function De(a){this.src=a;this.listeners={};this.i=0}
De.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.i++);var g=Ee(a,b,d,e);-1<g?(b=a[g],c||(b.ab=!1)):(b=new Be(b,this.src,f,!!d,e),b.ab=c,a.push(b));return b};
De.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Ee(e,b,c,d);return-1<b?(Ce(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.i--),!0):!1};
function Fe(a,b){var c=b.type;c in a.listeners&&lb(a.listeners[c],b)&&(Ce(b),0==a.listeners[c].length&&(delete a.listeners[c],a.i--))}
function Ee(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Oa&&f.listener==b&&f.capture==!!c&&f.gb==d)return e}return-1}
;var Ge="closure_lm_"+(1E6*Math.random()|0),He={},Ie=0;function Je(a,b,c,d,e){if(d&&d.once)Ke(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Je(a,b[f],c,d,e);else c=Le(c),a&&a[ze]?a.ia(b,c,Qa(d)?!!d.capture:!!d,e):Me(a,b,c,!1,d,e)}
function Me(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Qa(e)?!!e.capture:!!e,h=Ne(a);h||(a[Ge]=h=new De(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Oe();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)re||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Pe(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Ie++}}
function Oe(){function a(c){return b.call(a.src,a.listener,c)}
var b=Qe;return a}
function Ke(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ke(a,b[f],c,d,e);else c=Le(c),a&&a[ze]?a.m.add(String(b),c,!0,Qa(d)?!!d.capture:!!d,e):Me(a,b,c,!0,d,e)}
function Re(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Re(a,b[f],c,d,e);else(d=Qa(d)?!!d.capture:!!d,c=Le(c),a&&a[ze])?a.m.remove(String(b),c,d,e):a&&(a=Ne(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Ee(b,c,d,e)),(c=-1<a?b[a]:null)&&Se(c))}
function Se(a){if("number"!==typeof a&&a&&!a.Oa){var b=a.src;if(b&&b[ze])Fe(b.m,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Pe(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Ie--;(c=Ne(b))?(Fe(c,a),0==c.i&&(c.src=null,b[Ge]=null)):Ce(a)}}}
function Pe(a){return a in He?He[a]:He[a]="on"+a}
function Qe(a,b){if(a.Oa)a=!0;else{b=new se(b,this);var c=a.listener,d=a.gb||a.src;a.ab&&Se(a);a=c.call(d,b)}return a}
function Ne(a){a=a[Ge];return a instanceof De?a:null}
var Te="__closure_events_fn_"+(1E9*Math.random()>>>0);function Le(a){if("function"===typeof a)return a;a[Te]||(a[Te]=function(b){return a.handleEvent(b)});
return a[Te]}
;function Ue(){J.call(this);this.m=new De(this);this.Ec=this;this.la=null}
Za(Ue,J);Ue.prototype[ze]=!0;Ue.prototype.addEventListener=function(a,b,c,d){Je(this,a,b,c,d)};
Ue.prototype.removeEventListener=function(a,b,c,d){Re(this,a,b,c,d)};
function Ve(a,b){var c=a.la;if(c){var d=[];for(var e=1;c;c=c.la)d.push(c),++e}a=a.Ec;c=b.type||b;"string"===typeof b?b=new me(b,a):b instanceof me?b.target=b.target||a:(e=b,b=new me(c,a),yb(b,e));e=!0;if(d)for(var f=d.length-1;!b.l&&0<=f;f--){var g=b.i=d[f];e=We(g,c,!0,b)&&e}b.l||(g=b.i=a,e=We(g,c,!0,b)&&e,b.l||(e=We(g,c,!1,b)&&e));if(d)for(f=0;!b.l&&f<d.length;f++)g=b.i=d[f],e=We(g,c,!1,b)&&e}
Ue.prototype.D=function(){Ue.Z.D.call(this);if(this.m){var a=this.m,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Ce(d[e]);delete a.listeners[c];a.i--}}this.la=null};
Ue.prototype.ia=function(a,b,c,d){return this.m.add(String(a),b,!1,c,d)};
function We(a,b,c,d){b=a.m.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Oa&&g.capture==c){var h=g.listener,k=g.gb||g.src;g.ab&&Fe(a.m,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Xe(a,b){this.l=a;this.m=b;this.j=0;this.i=null}
Xe.prototype.get=function(){if(0<this.j){this.j--;var a=this.i;this.i=a.next;a.next=null}else a=this.l();return a};
function Ye(a,b){a.m(b);100>a.j&&(a.j++,b.next=a.i,a.i=b)}
;function Ze(a,b){return a+Math.random()*(b-a)}
;function $e(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
l=$e.prototype;l.clone=function(){return new $e(this.x,this.y)};
l.equals=function(a){return a instanceof $e&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
l.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
l.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
l.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
l.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function af(a,b){this.width=a;this.height=b}
l=af.prototype;l.clone=function(){return new af(this.width,this.height)};
l.aspectRatio=function(){return this.width/this.height};
l.isEmpty=function(){return!(this.width*this.height)};
l.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
l.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
l.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
l.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function bf(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function cf(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function df(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var ef;function ff(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!C("Presto")&&(a=function(){var e=cf("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Xa(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Ub()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Ub;c.Ub=null;e()}};
return function(e){d.next={Ub:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function gf(a){y.setTimeout(function(){throw a;},0)}
;function hf(){this.j=this.i=null}
hf.prototype.add=function(a,b){var c=jf.get();c.set(a,b);this.j?this.j.next=c:this.i=c;this.j=c};
hf.prototype.remove=function(){var a=null;this.i&&(a=this.i,this.i=this.i.next,this.i||(this.j=null),a.next=null);return a};
var jf=new Xe(function(){return new kf},function(a){return a.reset()});
function kf(){this.next=this.scope=this.i=null}
kf.prototype.set=function(a,b){this.i=a;this.scope=b;this.next=null};
kf.prototype.reset=function(){this.next=this.scope=this.i=null};var lf,mf=!1,nf=new hf;function of(a,b){lf||pf();mf||(lf(),mf=!0);nf.add(a,b)}
function pf(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);lf=function(){a.then(qf)}}else lf=function(){var b=qf;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!C("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(ef||(ef=ff()),ef(b)):y.setImmediate(b)}}
function qf(){for(var a;a=nf.remove();){try{a.i.call(a.scope)}catch(b){gf(b)}Ye(jf,a)}mf=!1}
;function rf(a){this.i=0;this.C=void 0;this.m=this.j=this.l=null;this.o=this.s=!1;if(a!=cb)try{var b=this;a.call(void 0,function(c){sf(b,2,c)},function(c){sf(b,3,c)})}catch(c){sf(this,3,c)}}
function tf(){this.next=this.context=this.onRejected=this.j=this.i=null;this.l=!1}
tf.prototype.reset=function(){this.context=this.onRejected=this.j=this.i=null;this.l=!1};
var uf=new Xe(function(){return new tf},function(a){a.reset()});
function vf(a,b,c){var d=uf.get();d.j=a;d.onRejected=b;d.context=c;return d}
function wf(a){return new rf(function(b,c){c(a)})}
rf.prototype.then=function(a,b,c){return xf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
rf.prototype.$goog_Thenable=!0;l=rf.prototype;l.ob=function(a,b){return xf(this,null,a,b)};
l.catch=rf.prototype.ob;l.cancel=function(a){if(0==this.i){var b=new yf(a);of(function(){zf(this,b)},this)}};
function zf(a,b){if(0==a.i)if(a.l){var c=a.l;if(c.j){for(var d=0,e=null,f=null,g=c.j;g&&(g.l||(d++,g.i==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.i&&1==d?zf(c,b):(f?(d=f,d.next==c.m&&(c.m=d),d.next=d.next.next):Af(c),Bf(c,e,3,b)))}a.l=null}else sf(a,3,b)}
function Cf(a,b){a.j||2!=a.i&&3!=a.i||Df(a);a.m?a.m.next=b:a.j=b;a.m=b}
function xf(a,b,c,d){var e=vf(null,null,null);e.i=new rf(function(f,g){e.j=b?function(h){try{var k=b.call(d,h);f(k)}catch(m){g(m)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof yf?g(h):f(k)}catch(m){g(m)}}:g});
e.i.l=a;Cf(a,e);return e.i}
l.Bd=function(a){this.i=0;sf(this,2,a)};
l.Cd=function(a){this.i=0;sf(this,3,a)};
function sf(a,b,c){if(0==a.i){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.i=1;a:{var d=c,e=a.Bd,f=a.Cd;if(d instanceof rf){Cf(d,vf(e||cb,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(m){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Qa(d))try{var k=d.then;if("function"===typeof k){Ef(d,k,e,f,a);g=!0;break a}}catch(m){f.call(a,m);g=!0;break a}g=!1}}}g||(a.C=c,a.i=b,a.l=null,Df(a),3!=b||c instanceof yf||Ff(a,c))}}
function Ef(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Df(a){a.s||(a.s=!0,of(a.Rc,a))}
function Af(a){var b=null;a.j&&(b=a.j,a.j=b.next,b.next=null);a.j||(a.m=null);return b}
l.Rc=function(){for(var a;a=Af(this);)Bf(this,a,this.i,this.C);this.s=!1};
function Bf(a,b,c,d){if(3==c&&b.onRejected&&!b.l)for(;a&&a.o;a=a.l)a.o=!1;if(b.i)b.i.l=null,Gf(b,c,d);else try{b.l?b.j.call(b.context):Gf(b,c,d)}catch(e){Hf.call(null,e)}Ye(uf,b)}
function Gf(a,b,c){2==b?a.j.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Ff(a,b){a.o=!0;of(function(){a.o&&Hf.call(null,b)})}
var Hf=gf;function yf(a){ab.call(this,a)}
Za(yf,ab);yf.prototype.name="cancel";function If(a,b){Ue.call(this);this.l=a||1;this.j=b||y;this.o=Xa(this.zd,this);this.s=Date.now()}
Za(If,Ue);l=If.prototype;l.enabled=!1;l.ca=null;function Jf(a,b){a.l=b;a.ca&&a.enabled?(a.stop(),a.start()):a.ca&&a.stop()}
l.zd=function(){if(this.enabled){var a=Date.now()-this.s;0<a&&a<.8*this.l?this.ca=this.j.setTimeout(this.o,this.l-a):(this.ca&&(this.j.clearTimeout(this.ca),this.ca=null),Ve(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
l.start=function(){this.enabled=!0;this.ca||(this.ca=this.j.setTimeout(this.o,this.l),this.s=Date.now())};
l.stop=function(){this.enabled=!1;this.ca&&(this.j.clearTimeout(this.ca),this.ca=null)};
l.D=function(){If.Z.D.call(this);this.stop();delete this.j};
function Kf(a,b,c){if("function"===typeof a)c&&(a=Xa(a,c));else if(a&&"function"==typeof a.handleEvent)a=Xa(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:y.setTimeout(a,b||0)}
;function Lf(a){this.C=a;this.i=new Map;this.s=new Set;this.l=0;this.m=100;this.flushInterval=3E4;this.j=new If(this.flushInterval);this.j.ia("tick",this.qb,!1,this);this.o=!1}
l=Lf.prototype;l.uc=function(a){this.o=a;this.m=1};
function Mf(a){a.j.enabled||a.j.start();a.l++;a.l>=a.m&&a.qb()}
l.qb=function(){var a=this.i.values();a=[].concat(ia(a)).filter(function(b){return b.Ca.size});
a.length&&this.C.flush(a,this.o);Nf(a);this.l=0;this.j.enabled&&this.j.stop()};
l.Ic=function(a){var b=Ja.apply(1,arguments);this.i.has(a)||this.i.set(a,new ge(a,b))};
l.Sb=function(a){var b=Ja.apply(1,arguments);this.i.has(a)||this.i.set(a,new he(a,b))};
function Of(a,b){return a.s.has(b)?void 0:a.i.get(b)}
l.Mb=function(a){this.Cc.apply(this,[a,1].concat(ia(Ja.apply(1,arguments))))};
l.Cc=function(a,b){var c=Ja.apply(2,arguments),d=Of(this,a);d&&d instanceof ge&&(d.l(b,c),Mf(this))};
l.pb=function(a,b){var c=Ja.apply(2,arguments),d=Of(this,a);d&&d instanceof he&&(d.l(b,c),Mf(this))};
function Nf(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Pf(a){this.i=a;this.i.Sb("/client_streamz/bg/fil",{ub:3,tb:"rk"})}
function Qf(a){this.i=a;this.i.Ic("/client_streamz/bg/fsc",{ub:3,tb:"rk"})}
function Rf(a){this.i=a;this.i.Sb("/client_streamz/bg/fsl",{ub:3,tb:"rk"})}
;function Sf(a){I.call(this,a,-1,Tf)}
u(Sf,I);function Uf(a){I.call(this,a,-1,Vf)}
u(Uf,I);function Wf(a){I.call(this,a)}
u(Wf,I);function Xf(a){I.call(this,a)}
u(Xf,I);var Tf=[3,6,4],Vf=[1],Yf=[1,2,3],Zf=[1,2,3];function $f(a){I.call(this,a,-1,ag)}
u($f,I);var ag=[1];function bg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function cg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;q=m=0}
function b(r){for(var w=g,t=0;64>t;t+=4)w[t/4]=r[t]<<24|r[t+1]<<16|r[t+2]<<8|r[t+3];for(t=16;80>t;t++)r=w[t-3]^w[t-8]^w[t-14]^w[t-16],w[t]=(r<<1|r>>>31)&4294967295;r=e[0];var z=e[1],E=e[2],F=e[3],O=e[4];for(t=0;80>t;t++){if(40>t)if(20>t){var N=F^z&(E^F);var Q=1518500249}else N=z^E^F,Q=1859775393;else 60>t?(N=z&E|F&(z|E),Q=2400959708):(N=z^E^F,Q=3395469782);N=((r<<5|r>>>27)&4294967295)+N+O+Q+w[t]&4294967295;O=F;F=E;E=(z<<30|z>>>2)&4294967295;z=r;r=N}e[0]=e[0]+r&4294967295;e[1]=e[1]+z&4294967295;e[2]=
e[2]+E&4294967295;e[3]=e[3]+F&4294967295;e[4]=e[4]+O&4294967295}
function c(r,w){if("string"===typeof r){r=unescape(encodeURIComponent(r));for(var t=[],z=0,E=r.length;z<E;++z)t.push(r.charCodeAt(z));r=t}w||(w=r.length);t=0;if(0==m)for(;t+64<w;)b(r.slice(t,t+64)),t+=64,q+=64;for(;t<w;)if(f[m++]=r[t++],q++,64==m)for(m=0,b(f);t+64<w;)b(r.slice(t,t+64)),t+=64,q+=64}
function d(){var r=[],w=8*q;56>m?c(h,56-m):c(h,64-(m-56));for(var t=63;56<=t;t--)f[t]=w&255,w>>>=8;b(f);for(t=w=0;5>t;t++)for(var z=24;0<=z;z-=8)r[w++]=e[t]>>z&255;return r}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var m,q;a();return{reset:a,update:c,digest:d,Oc:function(){for(var r=d(),w="",t=0;t<r.length;t++)w+="0123456789ABCDEF".charAt(Math.floor(r[t]/16))+"0123456789ABCDEF".charAt(r[t]%16);return w}}}
;function dg(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,eg(bg(d),a,c||null)].join(" "):null}
function eg(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],fb(d,function(h){e.push(h)}),fg(e.join(" "));
var f=[],g=[];fb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];fb(d,function(h){e.push(h)});
a=fg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function fg(a){var b=cg();b.update(a);return b.Oc().toLowerCase()}
;var gg={};function hg(a){this.i=a||{cookie:""}}
l=hg.prototype;l.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{hb:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
l.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.zr;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.hb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.i.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
l.get=function(a,b){for(var c=a+"=",d=(this.i.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Mb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
l.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{hb:0,path:b,domain:c});return d};
l.yb=function(){return ig(this).keys};
l.isEmpty=function(){return!this.i.cookie};
l.clear=function(){for(var a=ig(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function ig(a){a=(a.i.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Mb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var jg=new hg("undefined"==typeof document?null:document);function kg(a){return!!gg.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function lg(a){a=void 0===a?!1:a;var b=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;kg(a)&&(b=b||y.__1PSAPISID);if(b)return!0;var c=new hg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");kg(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function mg(a,b,c,d){(a=y[a])||(a=(new hg(document)).get(b));return a?dg(a,c,d):null}
function ng(a,b){b=void 0===b?!1:b;var c=bg(String(y.location.href)),d=[];if(lg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?y.__SAPISID:y.__APISID;e||(e=new hg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?dg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&kg(b)&&((b=mg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=mg("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function og(a){I.call(this,a,-1,pg)}
u(og,I);var pg=[2];function qg(a){this.i=this.j=this.l=a}
qg.prototype.reset=function(){this.i=this.j=this.l};
qg.prototype.getValue=function(){return this.j};function rg(a){var b=[];sg(new tg,a,b);return b.join("")}
function tg(){}
function sg(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),sg(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),ug(d,c),c.push(":"),sg(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":ug(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var vg={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},wg=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function ug(a,b){b.push('"',a.replace(wg,function(c){var d=vg[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),vg[c]=d);return d}),'"')}
;function xg(){}
xg.prototype.i=null;xg.prototype.getOptions=function(){var a;(a=this.i)||(a={},yg(this)&&(a[0]=!0,a[1]=!0),a=this.i=a);return a};var zg;function Ag(){}
Za(Ag,xg);function Bg(a){return(a=yg(a))?new ActiveXObject(a):new XMLHttpRequest}
function yg(a){if(!a.j&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.j=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.j}
zg=new Ag;function Cg(a){Ue.call(this);this.headers=new Map;this.L=a||null;this.j=!1;this.K=this.A=null;this.o=this.T="";this.l=this.R=this.u=this.P=!1;this.s=0;this.H=null;this.da="";this.X=this.Y=!1}
Za(Cg,Ue);var Dg=/^https?$/i,Eg=["POST","PUT"],Fg=[];function Gg(a,b,c,d,e,f,g){var h=new Cg;Fg.push(h);b&&h.ia("complete",b);h.m.add("ready",h.Mc,!0,void 0,void 0);f&&(h.s=Math.max(0,f));g&&(h.Y=g);h.send(a,c,d,e)}
l=Cg.prototype;l.Mc=function(){this.dispose();lb(Fg,this)};
l.send=function(a,b,c,d){if(this.A)throw Error("[goog.net.XhrIo] Object is active with another request="+this.T+"; newUri="+a);b=b?b.toUpperCase():"GET";this.T=a;this.o="";this.P=!1;this.j=!0;this.A=this.L?Bg(this.L):Bg(zg);this.K=this.L?this.L.getOptions():zg.getOptions();this.A.onreadystatechange=Xa(this.mc,this);try{this.getStatus(),this.R=!0,this.A.open(b,String(a),!0),this.R=!1}catch(g){this.getStatus();Hg(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=p(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=y.FormData&&a instanceof y.FormData;!(0<=eb(Eg,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=p(c);for(d=b.next();!d.done;d=b.next())c=p(d.value),d=c.next().value,c=c.next().value,this.A.setRequestHeader(d,c);this.da&&(this.A.responseType=this.da);"withCredentials"in this.A&&this.A.withCredentials!==this.Y&&(this.A.withCredentials=this.Y);try{Kg(this),0<this.s&&(this.X=Lg(this.A),this.getStatus(),this.X?(this.A.timeout=this.s,this.A.ontimeout=Xa(this.yc,this)):
this.H=Kf(this.yc,this.s,this)),this.getStatus(),this.u=!0,this.A.send(a),this.u=!1}catch(g){this.getStatus(),Hg(this,g)}};
function Lg(a){return Kc&&Vc()&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
l.yc=function(){"undefined"!=typeof Ma&&this.A&&(this.o="Timed out after "+this.s+"ms, aborting",this.getStatus(),Ve(this,"timeout"),this.abort(8))};
function Hg(a,b){a.j=!1;a.A&&(a.l=!0,a.A.abort(),a.l=!1);a.o=b;Mg(a);Ng(a)}
function Mg(a){a.P||(a.P=!0,Ve(a,"complete"),Ve(a,"error"))}
l.abort=function(){this.A&&this.j&&(this.getStatus(),this.j=!1,this.l=!0,this.A.abort(),this.l=!1,Ve(this,"complete"),Ve(this,"abort"),Ng(this))};
l.D=function(){this.A&&(this.j&&(this.j=!1,this.l=!0,this.A.abort(),this.l=!1),Ng(this,!0));Cg.Z.D.call(this)};
l.mc=function(){this.i()||(this.R||this.u||this.l?Og(this):this.cd())};
l.cd=function(){Og(this)};
function Og(a){if(a.j&&"undefined"!=typeof Ma)if(a.K[1]&&4==Pg(a)&&2==a.getStatus())a.getStatus();else if(a.u&&4==Pg(a))Kf(a.mc,0,a);else if(Ve(a,"readystatechange"),a.isComplete()){a.getStatus();a.j=!1;try{if(Qg(a))Ve(a,"complete"),Ve(a,"success");else{try{var b=2<Pg(a)?a.A.statusText:""}catch(c){b=""}a.o=b+" ["+a.getStatus()+"]";Mg(a)}}finally{Ng(a)}}}
function Ng(a,b){if(a.A){Kg(a);var c=a.A,d=a.K[0]?function(){}:null;
a.A=null;a.K=null;b||Ve(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function Kg(a){a.A&&a.X&&(a.A.ontimeout=null);a.H&&(y.clearTimeout(a.H),a.H=null)}
l.isActive=function(){return!!this.A};
l.isComplete=function(){return 4==Pg(this)};
function Qg(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=nc(1,String(a.T)),!a&&y.self&&y.self.location&&(a=y.self.location.protocol.slice(0,-1)),b=!Dg.test(a?a.toLowerCase():"");c=b}return c}
function Pg(a){return a.A?a.A.readyState:0}
l.getStatus=function(){try{return 2<Pg(this)?this.A.status:-1}catch(a){return-1}};
l.getLastError=function(){return"string"===typeof this.o?this.o:String(this.o)};function Rg(a){I.call(this,a)}
u(Rg,I);function Sg(a){I.call(this,a,-1,Tg)}
u(Sg,I);var Tg=[1];var Ug=["platform","platformVersion","architecture","model","uaFullVersion"];new Sg;function Vg(a){I.call(this,a)}
u(Vg,I);function Wg(a){I.call(this,a,31,Xg)}
u(Wg,I);var Xg=[3,20,27];function Yg(a){I.call(this,a,17,Zg)}
u(Yg,I);var Zg=[3,5];function $g(a){I.call(this,a,6,ah)}
u($g,I);var ah=[5];function bh(a){I.call(this,a)}
u(bh,I);var ch;ch=new function(a,b,c){this.j=a;this.fieldName=b;this.i=c;this.isRepeated=0;this.l=de}(175237375,{mr:0},bh);function dh(a,b,c,d,e,f,g,h,k,m,q){Ue.call(this);var r=this;this.P="";this.l=[];this.Qb="";this.Rb=this.va=-1;this.Xa=!1;this.K=this.o=null;this.H=0;this.Fc=1;this.timeoutMillis=0;this.da=!1;Ue.call(this);this.Pb=b||function(){};
this.u=new eh(a,f);this.Dc=d;this.Wa=q;this.Gc=Ya(Ze,0,1);this.T=e||null;this.L=c||null;this.X=g||!1;this.pageId=k||null;this.logger=null;this.withCredentials=!h;this.Ja=f||!1;!this.Ja&&(65<=cc("Chromium")||45<=cc("Firefox")||12<=cc("Safari")||(Ec()||C("iPad")||C("iPod"))&&Fc());a=D(new Vg,1,1);fh(this.u,a);this.s=new qg(1E4);this.j=new If(this.s.getValue());ke(this,this.j);m=gh(this,m);Je(this.j,"tick",m,!1,this);this.R=new If(6E5);ke(this,this.R);Je(this.R,"tick",m,!1,this);this.X||this.R.start();
this.Ja||(Je(document,"visibilitychange",function(){"hidden"===document.visibilityState&&r.Y()}),Je(document,"pagehide",this.Y,!1,this))}
u(dh,Ue);function gh(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
dh.prototype.D=function(){this.Y();Ue.prototype.D.call(this)};
function hh(a){a.T||(a.T=.01>a.Gc()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.T}
function ih(a,b){a.s=new qg(1>b?1:b);Jf(a.j,a.s.getValue())}
dh.prototype.log=function(a){a=a.clone();var b=this.Fc++;D(a,21,b);this.P&&D(a,26,this.P);if(!Md(a,1)){b=a;var c=Date.now().toString();D(b,1,c)}null!=Md(a,15,!1)||D(a,15,60*(new Date).getTimezoneOffset());this.o&&(b=this.o.clone(),G(a,og,16,b));for(;1E3<=this.l.length;)this.l.shift(),++this.H;this.l.push(a);Ve(this,new jh(a));this.X||this.j.enabled||this.j.start()};
dh.prototype.flush=function(a,b){var c=this;if(0===this.l.length)a&&a();else if(this.da)kh(this);else{var d=Date.now();if(this.Rb>d&&this.va<d)b&&b("throttled");else{var e=lh(this.u,this.l,this.H);d={};var f=this.Pb();f&&(d.Authorization=f);var g=hh(this);this.L&&(d["X-Goog-AuthUser"]=this.L,g=wc(g,"authuser",this.L));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=wc(g,"pageId",this.pageId));if(f&&this.Qb===f)b&&b("stale-auth-token");else{this.l=[];this.j.enabled&&this.j.stop();this.H=0;var h=ae(e),
k;this.K&&this.K.isSupported(h.length)&&(k=this.K.compress(h));var m={url:g,body:h,Kc:1,Ib:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},q=function(t){c.s.reset();Jf(c.j,c.s.getValue());if(t){var z=null;try{var E=JSON.parse(t.replace(")]}'\n",""));z=new $g(E)}catch(F){}z&&(t=Number(Yd(Md(z,1),"-1")),0<t&&(c.va=Date.now(),c.Rb=c.va+t),z=ch.l(z))&&(z=Yd(Md(z,1),-1),-1!=z&&(c.Xa||ih(c,z)))}a&&a()},r=function(t,z){var E=Td(e,Wg,3),F=c.s;
F.i=Math.min(3E5,2*F.i);F.j=Math.min(3E5,F.i+Math.round(.2*(Math.random()-.5)*F.i));Jf(c.j,c.s.getValue());401===t&&f&&(c.Qb=f);void 0===z&&(z=500<=t&&600>t||401===t||0===t);z&&(c.l=E.concat(c.l),c.X||c.j.enabled||c.j.start());b&&b("net-send-failed",t)},w=function(){c.Wa?c.Wa.send(m,q,r):c.Dc(m,q,r)};
k?k.then(function(t){m.Ib["Content-Encoding"]="gzip";m.Ib["Content-Type"]="application/binary";m.body=t;m.Kc=2;w()},function(){w()}):w()}}}};
dh.prototype.Y=function(){this.flush()};
function kh(a){mh(a,function(b,c){b=wc(b,"format","json");b=window.navigator.sendBeacon(b,ae(c));a.da&&!b&&(a.da=!1);return b})}
function mh(a,b){if(0!==a.l.length){var c=Dc(hh(a),"format");c=uc(c,"auth",a.Pb(),"authuser",a.L||"0");for(var d=0;10>d&&a.l.length;++d){var e=a.l.slice(0,32),f=lh(a.u,e,a.H);if(!b(c,f))break;a.H=0;a.l=a.l.slice(e.length)}a.j.enabled&&a.j.stop()}}
function jh(){me.call(this,"event-logged",void 0)}
u(jh,me);function eh(a,b){this.j=b=void 0===b?!1:b;this.uach=this.locale=null;this.i=new Yg;D(this.i,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));fh(this,new Vg)}
function fh(a,b){G(a.i,Vg,1,b);Md(b,1)||D(b,1,1);a.j||(b=nh(a),Md(b,5)||D(b,5,a.locale));a.uach&&(b=nh(a),Qd(b,Sg,9)||G(b,Sg,9,a.uach))}
function oh(a,b){var c=void 0===c?Ug:c;b(window,c).then(function(d){a.uach=d;d=nh(a);G(d,Sg,9,a.uach);return!0}).catch(function(){return!1})}
function nh(a){a=Qd(a.i,Vg,1);var b=Qd(a,Rg,11);b||(b=new Rg,G(a,Rg,11,b));return b}
function lh(a,b,c){c=void 0===c?0:c;a=a.i.clone();var d=Date.now().toString();a=D(a,4,d);b=Vd(a,Wg,3,b);c&&D(b,14,c);return b}
;function ph(a,b,c){Gg(a.url,function(d){d=d.target;if(Qg(d)){try{var e=d.A?d.A.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Ib,a.timeoutMillis,a.withCredentials)}
;function qh(){this.l="https://play.google.com/log?format=json&hasfast=true";this.u=!1;this.o=ph;this.i=""}
;function rh(){var a=void 0===a?"":a;var b=void 0===b?"":b;var c=new qh;c.i="";""!=a&&(c.l=a);b&&(c.j=b);a=new dh(1828,c.K?c.K:ng,"0",c.o,c.l,c.u,!1,c.R,void 0,void 0,c.s?c.s:void 0);c.O&&fh(a.u,c.O);if(c.j){b=c.j;var d=nh(a.u);D(d,7,b)}c.m&&(a.K=c.m);c.i&&(a.P=c.i);c.C&&((b=c.C)?(a.o||(a.o=new og),b=ae(b),D(a.o,4,b)):a.o&&D(a.o,4,void 0,!1));c.L&&(d=c.L,a.o||(a.o=new og),b=a.o,null==d?d=Cd:td(d),D(b,2,d));c.H&&(b=c.H,a.Xa=!0,ih(a,b));c.P&&oh(a.u,c.P);this.i=a}
rh.prototype.flush=function(a){var b=a||[];if(b.length){a=new $f;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e,g=new Sf;var h=D(g,1,f.j);var k=f;g=[];for(var m=0;m<k.i.length;m++)g.push(k.i[m].tb);if(null==g)g=Cd;else{for(k=0;k<g.length;k++);ld(g,5)}g=D(h,3,g);h=[];k=[];m=p(f.Ca.keys());for(var q=m.next();!q.done;q=m.next())k.push(q.value.split(","));for(m=0;m<k.length;m++){q=k[m];var r=f.m;for(var w=f.vb(q)||[],t=[],z=0;z<w.length;z++){var E=w[z];E=E&&E.Vb;var F=new Xf;switch(r){case 3:Od(F,1,
Zf,Number(E));break;case 2:Od(F,2,Zf,Number(E))}t.push(F)}r=t;for(w=0;w<r.length;w++){t=r[w];z=new Uf;t=G(z,Xf,2,t);z=q;E=[];F=f;for(var O=[],N=0;N<F.i.length;N++)O.push(F.i[N].ub);F=O;for(O=0;O<F.length;O++){N=F[O];var Q=z[O],da=new Wf;switch(N){case 3:Od(da,1,Yf,String(Q));break;case 2:Od(da,2,Yf,Number(Q));break;case 1:Od(da,3,Yf,"true"==Q)}E.push(da)}Vd(t,Wf,1,E);h.push(t)}}Vd(g,Uf,4,h);c.push(g);e.clear()}Vd(a,Sf,1,c);b=this.i;a instanceof Wg?b.log(a):(c=new Wg,a=ae(a),a=D(c,8,a),b.log(a));this.i.flush()}};function sh(){this.s=th();this.m=new rh;this.i=new Lf(this.m);this.o=new Pf(this.i);this.j=new Qf(this.i);this.l=new Rf(this.i);this.Fa=window.document.location.hostname}
function th(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function uh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function vh(a){var b=this;this.eb=!1;if(a.gd){var c;this.wa=null!=(c=a.wa)?c:new sh}c=a.program;a=a.globalName;var d=new uh;this.j=d.promise;this.xd=p((0,y[a].a)(c,function(e,f){Promise.resolve().then(function(){var g;if(null!=(g=b.wa)){var h=th()-g.s;g.o.i.pb("/client_streamz/bg/fil",h,g.Fa)}d.resolve({Jc:e,ud:f})})},!0)).next().value;
this.td=d.promise.then(function(){})}
vh.prototype.snapshot=function(a){var b=this;if(this.eb)throw Error("Already disposed");var c=th(),d;null!=(d=this.wa)&&d.j.i.Mb("/client_streamz/bg/fsc",d.Fa);return this.j.then(function(e){var f=e.Jc;return new Promise(function(g){f(function(h){var k;if(null!=(k=b.wa)){var m=th()-c;k.l.i.pb("/client_streamz/bg/fsl",m,k.Fa)}g(h)},[a.Xb,
a.vd])})})};
vh.prototype.dispose=function(){var a;null!=(a=this.wa)&&a.i.qb();this.eb=!0;this.j.then(function(b){(b=b.ud)&&b()})};
vh.prototype.i=function(){return this.eb};var wh=window;Db("csi.gstatic.com");Db("googleads.g.doubleclick.net");Db("partner.googleadservices.com");Db("pubads.g.doubleclick.net");Db("securepubads.g.doubleclick.net");Db("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var xh;try{new URL("s://g"),xh=!0}catch(a){xh=!1}var yh=xh;function zh(a,b){a.src=Kb(b);var c,d;(c=(b=null==(d=(c=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:d.call(c,"script[nonce]"))?b.nonce||b.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function Ah(a){var b=Bh;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Ch(){var a=[];Ah(function(b){a.push(b)});
return a}
var Bh={Qd:"allow-forms",Rd:"allow-modals",Sd:"allow-orientation-lock",Td:"allow-pointer-lock",Ud:"allow-popups",Vd:"allow-popups-to-escape-sandbox",Wd:"allow-presentation",Xd:"allow-same-origin",Yd:"allow-scripts",Zd:"allow-top-navigation",ae:"allow-top-navigation-by-user-activation"},Dh=db(function(){return Ch()});
function Eh(){var a=Fh(),b={};fb(Dh(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Fh(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function Gh(a){this.isValid=a}
function Hh(a){return new Gh(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var Ih=[Hh("data"),Hh("http"),Hh("https"),Hh("mailto"),Hh("ftp"),new Gh(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function Jh(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Kh=(new Date).getTime();var Lh="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");ia(Lh);function Mh(a){Ue.call(this);var b=this;this.u=this.l=0;this.aa=null!=a?a:{V:function(e,f){return setTimeout(e,f)},
ga:function(e){clearTimeout(e)}};
var c,d;this.j=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.o=function(){return x(function(e){return v(e,Nh(b),0)})};
window.addEventListener("offline",this.o);window.addEventListener("online",this.o);this.u||Oh(this)}
u(Mh,Ue);function Ph(){var a=Qh;Mh.i||(Mh.i=new Mh(a));return Mh.i}
Mh.prototype.dispose=function(){window.removeEventListener("offline",this.o);window.removeEventListener("online",this.o);this.aa.ga(this.u);delete Mh.i};
Mh.prototype.W=function(){return this.j};
function Oh(a){a.u=a.aa.V(function(){var b;return x(function(c){if(1==c.i)return a.j?(null==(b=window.navigator)?0:b.onLine)?c.B(3):v(c,Nh(a),3):v(c,Nh(a),3);Oh(a);c.i=0})},3E4)}
function Nh(a,b){return a.s?a.s:a.s=new Promise(function(c){var d,e,f,g;return x(function(h){switch(h.i){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,ya(h,2,3),d&&(a.l=a.aa.V(function(){d.abort()},b||2E4)),v(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:Ba(h);a.s=void 0;a.l&&(a.aa.ga(a.l),a.l=0);g!==a.j&&(a.j=g,a.j?Ve(a,"networkstatus-online"):Ve(a,"networkstatus-offline"));c(g);Ca(h);break;case 2:Aa(h),g=!1,h.B(3)}})})}
;function Rh(){this.data_=[];this.i=-1}
Rh.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data_[a]!==b&&(this.data_[a]=b,this.i=-1)};
Rh.prototype.get=function(a){return!!this.data_[a]};
function Sh(a){-1===a.i&&(a.i=ib(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.i}
;function Th(a,b){this.i=a[y.Symbol.iterator]();this.j=b}
Th.prototype[Symbol.iterator]=function(){return this};
Th.prototype.next=function(){var a=this.i.next();return{value:a.done?void 0:this.j.call(void 0,a.value),done:a.done}};
function Uh(a,b){return new Th(a,b)}
;function Vh(){this.blockSize=-1}
;function Wh(){this.blockSize=-1;this.blockSize=64;this.i=[];this.o=[];this.s=[];this.l=[];this.l[0]=128;for(var a=1;a<this.blockSize;++a)this.l[a]=0;this.m=this.j=0;this.reset()}
Za(Wh,Vh);Wh.prototype.reset=function(){this.i[0]=1732584193;this.i[1]=4023233417;this.i[2]=2562383102;this.i[3]=271733878;this.i[4]=3285377520;this.m=this.j=0};
function Xh(a,b,c){c||(c=0);var d=a.s;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.i[0];c=a.i[1];var g=a.i[2],h=a.i[3],k=a.i[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var m=1518500249}else f=c^g^h,m=1859775393;else 60>e?(f=c&g|h&(c|g),m=2400959708):
(f=c^g^h,m=3395469782);f=(b<<5|b>>>27)+f+k+m+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.i[0]=a.i[0]+b&4294967295;a.i[1]=a.i[1]+c&4294967295;a.i[2]=a.i[2]+g&4294967295;a.i[3]=a.i[3]+h&4294967295;a.i[4]=a.i[4]+k&4294967295}
Wh.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.o,f=this.j;d<b;){if(0==f)for(;d<=c;)Xh(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Xh(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Xh(this,e);f=0;break}}this.j=f;this.m+=b}};
Wh.prototype.digest=function(){var a=[],b=8*this.m;56>this.j?this.update(this.l,56-this.j):this.update(this.l,this.blockSize-(this.j-56));for(var c=this.blockSize-1;56<=c;c--)this.o[c]=b&255,b/=256;Xh(this,this.o);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.i[c]>>d&255,++b;return a};function Yh(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Zh(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function $h(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Yh(a).match(/\S+/g)||[],b=0<=eb(a,b));return b}
function ai(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):$h(a,"inverted-hdpi")&&Zh(a,Array.prototype.filter.call(a.classList?a.classList:Yh(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function bi(){}
bi.prototype.next=function(){return ci};
var ci={done:!0,value:void 0};function di(a){return{value:a,done:!1}}
bi.prototype.ea=function(){return this};function ei(a){if(a instanceof fi||a instanceof gi||a instanceof hi)return a;if("function"==typeof a.next)return new fi(function(){return a});
if("function"==typeof a[Symbol.iterator])return new fi(function(){return a[Symbol.iterator]()});
if("function"==typeof a.ea)return new fi(function(){return a.ea()});
throw Error("Not an iterator or iterable.");}
function fi(a){this.j=a}
fi.prototype.ea=function(){return new gi(this.j())};
fi.prototype[Symbol.iterator]=function(){return new hi(this.j())};
fi.prototype.i=function(){return new hi(this.j())};
function gi(a){this.j=a}
u(gi,bi);gi.prototype.next=function(){return this.j.next()};
gi.prototype[Symbol.iterator]=function(){return new hi(this.j)};
gi.prototype.i=function(){return new hi(this.j)};
function hi(a){fi.call(this,function(){return a});
this.l=a}
u(hi,fi);hi.prototype.next=function(){return this.l.next()};function ii(a,b){this.j={};this.i=[];this.ra=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof ii)for(c=a.yb(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
l=ii.prototype;l.yb=function(){ji(this);return this.i.concat()};
l.has=function(a){return ki(this.j,a)};
l.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||li;ji(this);for(var c,d=0;c=this.i[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function li(a,b){return a===b}
l.isEmpty=function(){return 0==this.size};
l.clear=function(){this.j={};this.ra=this.size=this.i.length=0};
l.remove=function(a){return this.delete(a)};
l.delete=function(a){return ki(this.j,a)?(delete this.j[a],--this.size,this.ra++,this.i.length>2*this.size&&ji(this),!0):!1};
function ji(a){if(a.size!=a.i.length){for(var b=0,c=0;b<a.i.length;){var d=a.i[b];ki(a.j,d)&&(a.i[c++]=d);b++}a.i.length=c}if(a.size!=a.i.length){var e={};for(c=b=0;b<a.i.length;)d=a.i[b],ki(e,d)||(a.i[c++]=d,e[d]=1),b++;a.i.length=c}}
l.get=function(a,b){return ki(this.j,a)?this.j[a]:b};
l.set=function(a,b){ki(this.j,a)||(this.size+=1,this.i.push(a),this.ra++);this.j[a]=b};
l.forEach=function(a,b){for(var c=this.yb(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
l.clone=function(){return new ii(this)};
l.keys=function(){return ei(this.ea(!0)).i()};
l.values=function(){return ei(this.ea(!1)).i()};
l.entries=function(){var a=this;return Uh(this.keys(),function(b){return[b,a.get(b)]})};
l.ea=function(a){ji(this);var b=0,c=this.ra,d=this,e=new bi;e.next=function(){if(c!=d.ra)throw Error("The map has changed since the iterator was created");if(b>=d.i.length)return ci;var f=d.i[b++];return di(a?f:d.j[f])};
return e};
function ki(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function K(a){J.call(this);this.s=1;this.m=[];this.o=0;this.j=[];this.l={};this.u=!!a}
Za(K,J);l=K.prototype;l.subscribe=function(a,b,c){var d=this.l[a];d||(d=this.l[a]=[]);var e=this.s;this.j[e]=a;this.j[e+1]=b;this.j[e+2]=c;this.s=e+3;d.push(e);return e};
function mi(a,b,c,d){if(b=a.l[b]){var e=a.j;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.Ia(b)}}
l.Ia=function(a){var b=this.j[a];if(b){var c=this.l[b];0!=this.o?(this.m.push(a),this.j[a+1]=function(){}):(c&&lb(c,a),delete this.j[a],delete this.j[a+1],delete this.j[a+2])}return!!b};
l.ta=function(a,b){var c=this.l[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.u)for(e=0;e<c.length;e++){var g=c[e];ni(this.j[g+1],this.j[g+2],d)}else{this.o++;try{for(e=0,f=c.length;e<f&&!this.i();e++)g=c[e],this.j[g+1].apply(this.j[g+2],d)}finally{if(this.o--,0<this.m.length&&0==this.o)for(;c=this.m.pop();)this.Ia(c)}}return 0!=e}return!1};
function ni(a,b,c){of(function(){a.apply(b,c)})}
l.clear=function(a){if(a){var b=this.l[a];b&&(b.forEach(this.Ia,this),delete this.l[a])}else this.j.length=0,this.l={}};
l.D=function(){K.Z.D.call(this);this.clear();this.m.length=0};function oi(a){this.i=a}
oi.prototype.set=function(a,b){void 0===b?this.i.remove(a):this.i.set(a,rg(b))};
oi.prototype.get=function(a){try{var b=this.i.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
oi.prototype.remove=function(a){this.i.remove(a)};function pi(a){this.i=a}
Za(pi,oi);function qi(a){this.data=a}
function ri(a){return void 0===a||a instanceof qi?a:new qi(a)}
pi.prototype.set=function(a,b){pi.Z.set.call(this,a,ri(b))};
pi.prototype.j=function(a){a=pi.Z.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
pi.prototype.get=function(a){if(a=this.j(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function si(a){this.i=a}
Za(si,pi);si.prototype.set=function(a,b,c){if(b=ri(b)){if(c){if(c<Date.now()){si.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}si.Z.set.call(this,a,b)};
si.prototype.j=function(a){var b=si.Z.j.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())si.prototype.remove.call(this,a);else return b}};function ti(){}
;function ui(){}
Za(ui,ti);ui.prototype[Symbol.iterator]=function(){return ei(this.ea(!0)).i()};
ui.prototype.clear=function(){var a=Array.from(this);a=p(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function vi(a){this.i=a}
Za(vi,ui);l=vi.prototype;l.isAvailable=function(){if(!this.i)return!1;try{return this.i.setItem("__sak","1"),this.i.removeItem("__sak"),!0}catch(a){return!1}};
l.set=function(a,b){try{this.i.setItem(a,b)}catch(c){if(0==this.i.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
l.get=function(a){a=this.i.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.i.removeItem(a)};
l.ea=function(a){var b=0,c=this.i,d=new bi;d.next=function(){if(b>=c.length)return ci;var e=c.key(b++);if(a)return di(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return di(e)};
return d};
l.clear=function(){this.i.clear()};
l.key=function(a){return this.i.key(a)};function wi(){var a=null;try{a=window.localStorage||null}catch(b){}this.i=a}
Za(wi,vi);function xi(a,b){this.j=a;this.i=null;var c;if(c=Kc)c=!(9<=Number(Yc));if(c){yi||(yi=new ii);this.i=yi.get(a);this.i||(b?this.i=document.getElementById(b):(this.i=document.createElement("userdata"),this.i.addBehavior("#default#userData"),document.body.appendChild(this.i)),yi.set(a,this.i));try{this.i.load(this.j)}catch(d){this.i=null}}}
Za(xi,ui);var zi={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},yi=null;function Ai(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return zi[b]})}
l=xi.prototype;l.isAvailable=function(){return!!this.i};
l.set=function(a,b){this.i.setAttribute(Ai(a),b);Bi(this)};
l.get=function(a){a=this.i.getAttribute(Ai(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.i.removeAttribute(Ai(a));Bi(this)};
l.ea=function(a){var b=0,c=this.i.XMLDocument.documentElement.attributes,d=new bi;d.next=function(){if(b>=c.length)return ci;var e=c[b++];if(a)return di(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return di(e)};
return d};
l.clear=function(){for(var a=this.i.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Bi(this)};
function Bi(a){try{a.i.save(a.j)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Ci(a,b){this.j=a;this.i=b+"::"}
Za(Ci,ui);Ci.prototype.set=function(a,b){this.j.set(this.i+a,b)};
Ci.prototype.get=function(a){return this.j.get(this.i+a)};
Ci.prototype.remove=function(a){this.j.remove(this.i+a)};
Ci.prototype.ea=function(a){var b=this.j[Symbol.iterator](),c=this,d=new bi;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.i.length)!=c.i;){e=b.next();if(e.done)return e;e=e.value}return di(a?e.slice(c.i.length):c.j.get(e))};
return d};function Di(a){I.call(this,a)}
u(Di,I);function Ei(a){I.call(this,a)}
u(Ei,I);Ei.prototype.getKey=function(){return Md(this,1)};
Ei.prototype.getValue=function(){return Xd(this,2===Pd(this,Fi)?2:-1)};
Ei.prototype.setValue=function(a){return Od(this,2,Fi,a)};
var Fi=[2,3,4,5,6];function Gi(a){I.call(this,a)}
u(Gi,I);function Hi(a){I.call(this,a)}
u(Hi,I);function Ii(a){I.call(this,a,-1,Ji)}
u(Ii,I);var Ji=[2];function Ki(a){I.call(this,a,-1,Li)}
u(Ki,I);Ki.prototype.getPlayerType=function(){return Md(this,36)};
Ki.prototype.setHomeGroupInfo=function(a){return G(this,Ii,81,a)};
Ki.prototype.clearLocationPlayabilityToken=function(){return D(this,89,void 0,!1)};
var Li=[9,66,24,32,86,100,101];function Mi(a){I.call(this,a,-1,Ni)}
u(Mi,I);var Ni=[15,26,28];function Oi(a){I.call(this,a)}
u(Oi,I);Oi.prototype.setToken=function(a){return D(this,2,a)};function Pi(a){I.call(this,a,-1,Qi)}
u(Pi,I);Pi.prototype.setSafetyMode=function(a){return D(this,5,a)};
var Qi=[12];function Ri(a){I.call(this,a,-1,Si)}
u(Ri,I);Ri.prototype.nb=function(a){G(this,Ki,1,a)};
var Si=[12];function Ti(a){this.name=a}
;var Ui=new Ti("continuationCommand");var Vi=new Ti("webCommandMetadata");var Wi=new Ti("signalServiceEndpoint");var Xi={ri:"EMBEDDED_PLAYER_MODE_UNKNOWN",mi:"EMBEDDED_PLAYER_MODE_DEFAULT",oi:"EMBEDDED_PLAYER_MODE_PFP",ni:"EMBEDDED_PLAYER_MODE_PFL"};var Yi=new Ti("feedbackEndpoint");var Zi={Iq:"WEB_DISPLAY_MODE_UNKNOWN",Eq:"WEB_DISPLAY_MODE_BROWSER",Gq:"WEB_DISPLAY_MODE_MINIMAL_UI",Hq:"WEB_DISPLAY_MODE_STANDALONE",Fq:"WEB_DISPLAY_MODE_FULLSCREEN"};function $i(a){I.call(this,a,-1,aj)}
u($i,I);function bj(a){I.call(this,a)}
u(bj,I);bj.prototype.getKey=function(){return Yd(Md(this,1),"")};
bj.prototype.getValue=function(){return Yd(Md(this,2),"")};
bj.prototype.setValue=function(a){return D(this,2,a)};
var aj=[4,5];function cj(a){I.call(this,a)}
u(cj,I);function dj(a){I.call(this,a)}
u(dj,I);var ej=[2,3,4];function fj(a){I.call(this,a)}
u(fj,I);fj.prototype.getMessage=function(){return Yd(Md(this,1),"")};function gj(a){I.call(this,a)}
u(gj,I);function hj(a){I.call(this,a)}
u(hj,I);function ij(a){I.call(this,a,-1,jj)}
u(ij,I);var jj=[10,17];function kj(a){I.call(this,a)}
u(kj,I);function lj(a){I.call(this,a)}
u(lj,I);function mj(a){I.call(this,a)}
u(mj,I);function nj(a){I.call(this,a)}
u(nj,I);function oj(a){I.call(this,a)}
u(oj,I);function pj(a,b){G(a,mj,1,b)}
oj.prototype.j=function(a){D(this,2,a)};
function qj(a){I.call(this,a)}
u(qj,I);function rj(a,b){G(a,mj,1,b)}
;function sj(a){I.call(this,a,-1,tj)}
u(sj,I);sj.prototype.j=function(a){D(this,1,a)};
function uj(a,b){G(a,mj,2,b)}
var tj=[3];function vj(a){I.call(this,a)}
u(vj,I);vj.prototype.j=function(a){D(this,1,a)};function wj(a){I.call(this,a)}
u(wj,I);wj.prototype.j=function(a){D(this,1,a)};function xj(a){I.call(this,a)}
u(xj,I);xj.prototype.j=function(a){D(this,1,a)};function yj(a){I.call(this,a)}
u(yj,I);yj.prototype.j=function(a){D(this,1,a)};function zj(a){I.call(this,a)}
u(zj,I);function Aj(a){I.call(this,a)}
u(Aj,I);function Bj(a){I.call(this,a,-1,Cj)}
u(Bj,I);Bj.prototype.getPlayerType=function(){var a=Md(this,7);return null==a?0:a};
Bj.prototype.setVideoId=function(a){return D(this,19,a)};
function Dj(a,b){Wd(a,68,Ej,b)}
function Ej(a){I.call(this,a)}
u(Ej,I);Ej.prototype.getId=function(){return Yd(Md(this,2),"")};
var Cj=[83,68];function Fj(a){I.call(this,a)}
u(Fj,I);function Gj(a){I.call(this,a)}
u(Gj,I);function Hj(a){I.call(this,a)}
u(Hj,I);function Ij(a){I.call(this,a,442)}
u(Ij,I);
var Jj=[23,24,11,6,7,5,2,3,13,20,21,22,28,32,37,229,241,45,59,225,288,72,73,78,208,156,202,215,74,76,79,80,111,85,91,97,100,102,105,119,126,127,136,146,148,151,157,158,159,163,164,168,176,222,383,177,178,179,411,184,188,189,190,191,193,194,195,196,197,198,199,200,201,402,320,203,204,205,206,258,259,260,261,327,209,219,226,227,232,233,234,240,244,247,248,249,251,256,257,266,254,255,270,272,278,291,293,300,304,308,309,310,311,313,314,319,321,323,324,328,330,331,332,334,337,338,340,344,348,350,351,352,
353,354,355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,388,389,403,410,412,429,413,414,415,416,417,418,430,423,424,425,426,427,431,117,439,441];var Kj={rj:0,cj:1,ij:2,jj:4,oj:8,kj:16,lj:32,qj:64,pj:128,ej:256,gj:512,nj:1024,fj:2048,hj:4096,dj:8192,mj:16384};function Lj(a){I.call(this,a)}
u(Lj,I);function gk(a){I.call(this,a)}
u(gk,I);gk.prototype.setVideoId=function(a){return Od(this,1,hk,a)};
gk.prototype.getPlaylistId=function(){return Xd(this,2===Pd(this,hk)?2:-1)};
var hk=[1,2];function ik(a){I.call(this,a,-1,jk)}
u(ik,I);var jk=[3];var kk=new Ti("webPlayerShareEntityServiceEndpoint");var lk=new Ti("playlistEditEndpoint");var mk=new Ti("modifyChannelNotificationPreferenceEndpoint");var nk=new Ti("unsubscribeEndpoint");var ok=new Ti("subscribeEndpoint");function pk(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var qk=y.window,rk,sk,tk=(null==qk?void 0:null==(rk=qk.yt)?void 0:rk.config_)||(null==qk?void 0:null==(sk=qk.ytcfg)?void 0:sk.data_)||{};A("yt.config_",tk);function uk(){pk(tk,arguments)}
function L(a,b){return a in tk?tk[a]:b}
function vk(){var a=tk.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;function M(a){a=wk(a);return"string"===typeof a&&"false"===a?!1:!!a}
function xk(a,b){a=wk(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function yk(){return L("EXPERIMENTS_TOKEN","")}
function wk(a){var b=L("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:L("EXPERIMENT_FLAGS",{})[a]}
function zk(){var a=[],b=L("EXPERIMENTS_FORCED_FLAGS",{});for(c in b)a.push({key:c,value:String(b[c])});var c=L("EXPERIMENT_FLAGS",{});for(var d in c)d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var Ak=[];function Bk(a){Ak.forEach(function(b){return b(a)})}
function Ck(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Dk(b)}}:a}
function Dk(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=L("ERRORS",[]),e.push([a,"ERROR",b,c,d]),uk("ERRORS",e));Bk(a)}
function Ek(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=L("ERRORS",[]),e.push([a,"WARNING",b,c,d]),uk("ERRORS",e))}
;function Fk(){var a=Gk;B("yt.ads.biscotti.getId_")||A("yt.ads.biscotti.getId_",a)}
function Hk(a){A("yt.ads.biscotti.lastId_",a)}
;var Ik=/^[\w.]*$/,Jk={q:!0,search_query:!0};function Kk(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Lk(f[0]||""),h=Lk(f[1]||"");g in c?Array.isArray(c[g])?nb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(r){var k=r,m=f[0],q=String(Kk);k.args=[{key:m,value:f[1],query:a,method:Mk==q?"unchanged":q}];Jk.hasOwnProperty(m)||Ek(k)}}return c}
var Mk=String(Kk);function Nk(a){var b=[];ob(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];fb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Ok(a){"?"==a.charAt(0)&&(a=a.substr(1));return Kk(a,"&")}
function Pk(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Ok(1<a.length?a[1]:a[0])):{}}
function Qk(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Ok(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return vc(a,e)+d}
function Rk(a){if(!b)var b=window.location.href;var c=nc(1,a),d=oc(a);c&&d?(a=a.match(lc),b=b.match(lc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?oc(b)==d&&(Number(nc(4,b))||null)==(Number(nc(4,a))||null):!0;return a}
function Lk(a){return a&&a.match(Ik)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Sk(a){var b=Tk;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Kh;e.flash="0";a:{try{var f=b.i.top.location.href}catch(fa){f=2;break a}f=f?f===b.j.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?wh:g;try{var h=g.history.length}catch(fa){h=0}e.u_his=h;var k;e.u_h=null==(k=wh.screen)?void 0:k.height;var m;e.u_w=null==(m=wh.screen)?void 0:m.width;var q;e.u_ah=null==(q=wh.screen)?void 0:q.availHeight;var r;e.u_aw=
null==(r=wh.screen)?void 0:r.availWidth;var w;e.u_cd=null==(w=wh.screen)?void 0:w.colorDepth}catch(fa){}h=b.i;try{var t=h.screenX;var z=h.screenY}catch(fa){}try{var E=h.outerWidth;var F=h.outerHeight}catch(fa){}try{var O=h.innerWidth;var N=h.innerHeight}catch(fa){}try{var Q=h.screenLeft;var da=h.screenTop}catch(fa){}try{O=h.innerWidth,N=h.innerHeight}catch(fa){}try{var U=h.screen.availWidth;var mb=h.screen.availTop}catch(fa){}t=[Q,da,t,z,U,mb,E,F,O,N];try{var Wa=(b.i.top||window).document,ma="CSS1Compat"==
Wa.compatMode?Wa.documentElement:Wa.body;var H=(new af(ma.clientWidth,ma.clientHeight)).round()}catch(fa){H=new af(-12245933,-12245933)}Wa=H;H={};var la=void 0===la?y:la;ma=new Rh;la.SVGElement&&la.document.createElementNS&&ma.set(0);z=Eh();z["allow-top-navigation-by-user-activation"]&&ma.set(1);z["allow-popups-to-escape-sandbox"]&&ma.set(2);la.crypto&&la.crypto.subtle&&ma.set(3);la.TextDecoder&&la.TextEncoder&&ma.set(4);la=Sh(ma);H.bc=la;H.bih=Wa.height;H.biw=Wa.width;H.brdim=t.join();b=b.j;b=(H.vis=
b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,H.wgl=!!wh.WebGLRenderingContext,H);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Tk=new function(){var a=window.document;this.i=window;this.j=a};
A("yt.ads_.signals_.getAdSignalsString",function(a){return Nk(Sk(a))});Date.now();var Uk="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function Vk(){if(!Uk)return null;var a=Uk();return"open"in a?a:null}
function Wk(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function Xk(a,b){"function"===typeof a&&(a=Ck(a));return window.setTimeout(a,b)}
function Yk(a){window.clearTimeout(a)}
;var Zk={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},$k="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ia(Lh)),al=!1;
function bl(a,b){b=void 0===b?{}:b;var c=Rk(a),d=M("web_ajax_ignore_global_headers_if_set"),e;for(e in Zk){var f=L(Zk[e]);"X-Goog-Visitor-Id"!==e||f||(f=L("VISITOR_DATA"));!f||!c&&oc(a)||d&&void 0!==b[e]||(b[e]=f)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!oc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!oc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||
!oc(a))b["X-YouTube-Ad-Signals"]=Nk(Sk());return b}
function cl(a){var b=window.location.search,c=oc(a);M("debug_handle_relative_url_for_query_forward_killswitch")||c||!Rk(a)||(c=document.location.hostname);var d=mc(nc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Ok(b),f={};fb($k,function(g){e[g]&&(f[g]=e[g])});
return Qk(a,f||{},!1)}
function dl(a,b){var c=b.format||"JSON";a=el(a,b);var d=fl(a,b),e=!1,f=gl(a,function(k){if(!e){e=!0;h&&Yk(h);var m=Wk(k),q=null,r=400<=k.status&&500>k.status,w=500<=k.status&&600>k.status;if(m||r||w)q=hl(a,c,k,b.convertToSafeHtml);if(m)a:if(k&&204==k.status)m=!0;else{switch(c){case "XML":m=0==parseInt(q&&q.return_code,10);break a;case "RAW":m=!0;break a}m=!!q}q=q||{};r=b.context||y;m?b.onSuccess&&b.onSuccess.call(r,k,q):b.onError&&b.onError.call(r,k,q);b.onFinish&&b.onFinish.call(r,k,q)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=Xk(function(){e||(e=!0,f.abort(),Yk(h),g.call(b.context||y,f))},d)}return f}
function el(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=L("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=Qk(a,b||{},!0);return a}
function fl(a,b){var c=L("XSRF_FIELD_NAME"),d=L("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=L("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||oc(a)&&!b.withCredentials&&oc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(M("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=Ok(e),yb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):tc(e));f=e||f&&!rb(f);!al&&f&&"POST"!=b.method&&(al=!0,Dk(Error("AJAX request with postData should use POST")));return e}
function hl(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Ek(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?il(a):null)e={},fb(a.getElementsByTagName("*"),function(g){e[g.tagName]=jl(g)})}d&&kl(e);
return e}
function kl(a){if(Qa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;Db("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=a[b],e=Ab();d=e?e.createHTML(d):d;a[c]=new ec(d)}else kl(a[b])}}
function il(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function jl(a){var b="";fb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function gl(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Ck(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=Vk();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;M("debug_forward_web_query_parameters")&&(a=cl(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=bl(a,e))for(var m in e)k.setRequestHeader(m,e[m]),"content-type"==m.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;function ll(a){var b=this;this.j=void 0;this.i=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.j=c});
a.addEventListener("appinstalled",function(){b.i=!0},{once:!0})}
function ml(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function nl(a,b,c,d,e){jg.set(""+a,b,{hb:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function ol(a,b,c){jg.remove(""+a,void 0===b?"/":b,void 0===c?"youtube.com":c)}
function pl(){if(!jg.isEnabled())return!1;if(!jg.isEmpty())return!0;jg.set("TESTCOOKIESENABLED","1",{hb:60});if("1"!==jg.get("TESTCOOKIESENABLED"))return!1;jg.remove("TESTCOOKIESENABLED");return!0}
;var ql=B("ytglobal.prefsUserPrefsPrefs_")||{};A("ytglobal.prefsUserPrefsPrefs_",ql);function rl(){this.i=L("ALT_PREF_COOKIE_NAME","PREF");this.j=L("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=jg.get(""+this.i,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(ql[d]=c.toString())}}}
rl.prototype.get=function(a,b){sl(a);tl(a);a=void 0!==ql[a]?ql[a].toString():null;return null!=a?a:b?b:""};
rl.prototype.set=function(a,b){sl(a);tl(a);if(null==b)throw Error("ExpectedNotNull");ql[a]=b.toString()};
function ul(a){return!!((vl("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
rl.prototype.remove=function(a){sl(a);tl(a);delete ql[a]};
rl.prototype.clear=function(){for(var a in ql)delete ql[a]};
function tl(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function sl(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function vl(a){a=void 0!==ql[a]?ql[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Na(rl);var wl={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},xl={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},yl={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},zl={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function Al(){var a=y.navigator;return a?a.connection:void 0}
function Bl(){var a=Al();if(a){var b=wl[a.type||"unknown"]||"CONN_UNKNOWN";a=wl[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function Cl(){var a=Al();if(null!=a&&a.effectiveType)return zl.hasOwnProperty(a.effectiveType)?zl[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function Dl(){return"INNERTUBE_API_KEY"in tk&&"INNERTUBE_API_VERSION"in tk}
function El(){return{innertubeApiKey:L("INNERTUBE_API_KEY"),innertubeApiVersion:L("INNERTUBE_API_VERSION"),Ab:L("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),fc:L("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Vc:L("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:L("INNERTUBE_CONTEXT_CLIENT_VERSION"),ic:L("INNERTUBE_CONTEXT_HL"),hc:L("INNERTUBE_CONTEXT_GL"),Wc:L("INNERTUBE_HOST_OVERRIDE")||"",Yc:!!L("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Xc:!!L("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:L("SERIALIZED_CLIENT_CONFIG_DATA")}}
function Fl(a){var b={client:{hl:a.ic,gl:a.hc,clientName:a.fc,clientVersion:a.innertubeContextClientVersion,configInfo:a.Ab}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=yk();""!==c&&(b.client.experimentsToken=c);c=zk();0<c.length&&(b.request={internalExperimentFlags:c});Gl(a,void 0,b);Hl(void 0,b);Il(a,void 0,b);Jl(void 0,b);L("DELEGATED_SESSION_ID")&&!M("pageid_as_header_web")&&(b.user={onBehalfOfUser:L("DELEGATED_SESSION_ID")});
a=Object;c=a.assign;for(var d=b.client,e={},f=p(Object.entries(Ok(L("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=p(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function Kl(a){var b=new Ri,c=new Ki;D(c,1,a.ic);D(c,2,a.hc);D(c,16,a.Vc);D(c,17,a.innertubeContextClientVersion);if(a.Ab){var d=a.Ab,e=new Gi;d.coldConfigData&&D(e,1,d.coldConfigData);d.appInstallData&&D(e,6,d.appInstallData);d.coldHashData&&D(e,3,d.coldHashData);d.hotHashData&&D(e,5,d.hotHashData);G(c,Gi,62,e)}(d=y.devicePixelRatio)&&1!=d&&D(c,65,d);d=yk();""!==d&&D(c,54,d);d=zk();if(0<d.length){e=new Mi;for(var f=0;f<d.length;f++){var g=new Ei;D(g,1,d[f].key);g.setValue(d[f].value);Wd(e,15,Ei,
g)}G(b,Mi,5,e)}Gl(a,c);Hl(c);Il(a,c);Jl(c);L("DELEGATED_SESSION_ID")&&!M("pageid_as_header_web")&&(a=new Pi,D(a,3,L("DELEGATED_SESSION_ID")));a=p(Object.entries(Ok(L("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=p(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?D(c,12,e):"cmodel"===d?D(c,13,e):"cbr"===d?D(c,87,e):"cbrver"===d?D(c,88,e):"cos"===d?D(c,18,e):"cosver"===d?D(c,19,e):"cplatform"===d&&D(c,42,e);b.nb(c);return b}
function Gl(a,b,c){a=a.fc;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=Qd(b,Hi,96)||new Hi;var d=ml();d=Object.keys(Zi).indexOf(d);d=-1===d?null:d;null!==d&&D(c,3,d);G(b,Hi,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=ml())}
function Hl(a,b){var c;if(M("web_log_memory_total_kbytes")&&(null==(c=y.navigator)?0:c.deviceMemory)){var d;c=null==(d=y.navigator)?void 0:d.deviceMemory;a?D(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function Il(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=Qd(b,Gi,62))?d:new Gi;D(c,6,a.appInstallData);G(b,Gi,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function Jl(a,b){var c=Bl();c&&(a?D(a,61,xl[c]):b&&(b.client.connectionType=c));M("web_log_effective_connection_type")&&(c=Cl())&&(a?D(a,94,yl[c]):b&&(b.client.effectiveConnectionType=c))}
function Ll(a,b,c){c=void 0===c?{}:c;var d={};L("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":L("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||L("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.er||L("AUTHORIZATION"))||(a?b="Bearer "+B("gapi.auth.getToken")().dr:b=ng([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=L("SESSION_INDEX",0),M("pageid_as_header_web")&&(d["X-Goog-PageId"]=L("DELEGATED_SESSION_ID")));return d}
;function Ml(a){a=Object.assign({},a);delete a.Authorization;var b=ng();if(b){var c=new Wh;c.update(L("INNERTUBE_API_KEY"));c.update(b);a.hash=dd(c.digest(),3)}return a}
;function Nl(a){var b=new wi;(b=b.isAvailable()?a?new Ci(b,a):b:null)||(a=new xi(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.i=(a=b)?new si(a):null;this.j=document.domain||window.location.hostname}
Nl.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.i)try{this.i.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(rg(b))}catch(f){return}else e=escape(b);nl(a,e,c,this.j)};
Nl.prototype.get=function(a,b){var c=void 0,d=!this.i;if(!d)try{c=this.i.get(a)}catch(e){d=!0}if(d&&(c=jg.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Nl.prototype.remove=function(a){this.i&&this.i.remove(a);ol(a,"/",this.j)};var Ol=window,P=Ol.ytcsi&&Ol.ytcsi.now?Ol.ytcsi.now:Ol.performance&&Ol.performance.timing&&Ol.performance.now&&Ol.performance.timing.navigationStart?function(){return Ol.performance.timing.navigationStart+Ol.performance.now()}:function(){return(new Date).getTime()};var Pl;function Ql(){Pl||(Pl=new Nl("yt.innertube"));return Pl}
function Rl(a,b,c,d){if(d)return null;d=Ql().get("nextId",!0)||1;var e=Ql().get("requests",!0)||{};e[d]={method:a,request:b,authState:Ml(c),requestTime:Math.round(P())};Ql().set("nextId",d+1,86400,!0);Ql().set("requests",e,86400,!0);return d}
function Sl(a){var b=Ql().get("requests",!0)||{};delete b[a];Ql().set("requests",b,86400,!0)}
function Tl(a){var b=Ql().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(P())-d.requestTime)){var e=d.authState,f=Ml(Ll(!1));ub(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(P())),Ul(a,d.method,e,{}));delete b[c]}}Ql().set("requests",b,86400,!0)}}
;function Vl(){}
function Wl(a,b){return Xl(a,0,b)}
Vl.prototype.V=function(a,b){return Xl(a,1,b)};
function Yl(a,b){Xl(a,2,b)}
function Zl(a){var b=B("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function $l(){Vl.apply(this,arguments)}
u($l,Vl);function am(){$l.i||($l.i=new $l);return $l.i}
function Xl(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Xk(a,c||0)}
$l.prototype.ga=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):Yk(a)}};
$l.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};
$l.prototype.pause=function(){var a=B("yt.scheduler.instance.pause");a&&a()};var Qh=am();var bm=Zc||$c;function cm(a){var b=Tb();return b?0<=b.toLowerCase().indexOf(a):!1}
;var dm=function(){var a;return function(){a||(a=new Nl("ytidb"));return a}}();
function em(){var a;return null==(a=dm())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var fm=[],gm,hm=!1;function im(){var a={};for(gm=new jm(void 0===a.handleError?km:a.handleError,void 0===a.logEvent?lm:a.logEvent);0<fm.length;)switch(a=fm.shift(),a.type){case "ERROR":gm.handleError(a.payload);break;case "EVENT":gm.logEvent(a.eventType,a.payload)}}
function mm(a){hm||(gm?gm.handleError(a):(fm.push({type:"ERROR",payload:a}),10<fm.length&&fm.shift()))}
function nm(a,b){hm||(gm?gm.logEvent(a,b):(fm.push({type:"EVENT",eventType:a,payload:b}),10<fm.length&&fm.shift()))}
;function R(a){var b=Ja.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ia(b))}
u(R,Error);function om(){try{return pm(),!0}catch(a){return!1}}
function pm(a){if(void 0!==L("DATASYNC_ID"))return L("DATASYNC_ID");throw new R("Datasync ID not set",void 0===a?"unknown":a);}
;function qm(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function rm(a){return a.substr(0,a.indexOf(":"))||a}
;var sm={},tm=(sm.AUTH_INVALID="No user identifier specified.",sm.EXPLICIT_ABORT="Transaction was explicitly aborted.",sm.IDB_NOT_SUPPORTED="IndexedDB is not supported.",sm.MISSING_INDEX="Index not created.",sm.MISSING_OBJECT_STORES="Object stores not created.",sm.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",sm.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",sm.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
sm.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",sm.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",sm.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",sm.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",sm),um={},vm=(um.AUTH_INVALID="ERROR",um.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",um.EXPLICIT_ABORT="IGNORED",um.IDB_NOT_SUPPORTED="ERROR",um.MISSING_INDEX=
"WARNING",um.MISSING_OBJECT_STORES="ERROR",um.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",um.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",um.QUOTA_EXCEEDED="WARNING",um.QUOTA_MAYBE_EXCEEDED="WARNING",um.UNKNOWN_ABORT="WARNING",um.INCOMPATIBLE_DB_VERSION="WARNING",um),wm={},xm=(wm.AUTH_INVALID=!1,wm.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,wm.EXPLICIT_ABORT=!1,wm.IDB_NOT_SUPPORTED=!1,wm.MISSING_INDEX=!1,wm.MISSING_OBJECT_STORES=!1,wm.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,wm.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,wm.QUOTA_EXCEEDED=!1,wm.QUOTA_MAYBE_EXCEEDED=!0,wm.UNKNOWN_ABORT=!0,wm.INCOMPATIBLE_DB_VERSION=!1,wm);function ym(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?tm[a]:c;d=void 0===d?vm[a]:d;e=void 0===e?xm[a]:e;R.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.i=e;Object.setPrototypeOf(this,ym.prototype)}
u(ym,R);function zm(a,b){ym.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},tm.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,zm.prototype)}
u(zm,ym);function Am(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Am.prototype)}
u(Am,Error);var Bm=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Cm(a,b,c,d){b=rm(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof ym)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new ym("QUOTA_EXCEEDED",a);if(ad&&"UnknownError"===e.name)return new ym("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Am)return new ym("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&Bm.some(function(f){return e.message.includes(f)}))return new ym("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new ym("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",nc:e.name})];e.level="WARNING";return e}
function Dm(a,b,c){var d=em();return new ym("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function Em(a){if(!a)throw Error();throw a;}
function Fm(a){return a}
function Gm(a){this.i=a}
function Hm(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=p(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=p(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.i=[];this.onRejected=[];a=a.i;try{a(c,b)}catch(e){b(e)}}
Hm.all=function(a){return new Hm(new Gm(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={Ba:0};f.Ba<a.length;f={Ba:f.Ba},++f.Ba)Hm.resolve(a[f.Ba]).then(function(g){return function(h){d[g.Ba]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
Hm.resolve=function(a){return new Hm(new Gm(function(b,c){a instanceof Hm?a.then(b,c):b(a)}))};
Hm.reject=function(a){return new Hm(new Gm(function(b,c){c(a)}))};
Hm.prototype.then=function(a,b){var c=this,d=null!=a?a:Fm,e=null!=b?b:Em;return new Hm(new Gm(function(f,g){"PENDING"===c.state.status?(c.i.push(function(){Im(c,c,d,f,g)}),c.onRejected.push(function(){Jm(c,c,e,f,g)})):"FULFILLED"===c.state.status?Im(c,c,d,f,g):"REJECTED"===c.state.status&&Jm(c,c,e,f,g)}))};
Hm.prototype.catch=function(a){return this.then(void 0,a)};
function Im(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Hm?Km(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Jm(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Hm?Km(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Km(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Hm?Km(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Lm(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Mm(a){return new Promise(function(b,c){Lm(a,b,c)})}
function Nm(a){return new Hm(new Gm(function(b,c){Lm(a,b,c)}))}
;function Om(a,b){return new Hm(new Gm(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function Pm(a,b){this.i=a;this.options=b;this.transactionCount=0;this.l=Math.round(P());this.j=!1}
l=Pm.prototype;l.add=function(a,b,c){return Qm(this,[a],{mode:"readwrite",U:!0},function(d){return d.objectStore(a).add(b,c)})};
l.clear=function(a){return Qm(this,[a],{mode:"readwrite",U:!0},function(b){return b.objectStore(a).clear()})};
l.close=function(){this.i.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
l.count=function(a,b){return Qm(this,[a],{mode:"readonly",U:!0},function(c){return c.objectStore(a).count(b)})};
function Rm(a,b,c){a=a.i.createObjectStore(b,c);return new Sm(a)}
l.delete=function(a,b){return Qm(this,[a],{mode:"readwrite",U:!0},function(c){return c.objectStore(a).delete(b)})};
l.get=function(a,b){return Qm(this,[a],{mode:"readonly",U:!0},function(c){return c.objectStore(a).get(b)})};
function Tm(a,b){return Qm(a,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(c){c=c.objectStore("LogsRequestsStore");return Nm(c.i.put(b,void 0))})}
l.objectStoreNames=function(){return Array.from(this.i.objectStoreNames)};
function Qm(a,b,c,d){var e,f,g,h,k,m,q,r,w,t,z,E;return x(function(F){switch(F.i){case 1:var O={mode:"readonly",U:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?O.mode=c:Object.assign(O,c);e=O;a.transactionCount++;f=e.U?3:1;g=0;case 2:if(h){F.B(3);break}g++;k=Math.round(P());ya(F,4);m=a.i.transaction(b,e.mode);O=new Um(m);O=Vm(O,d);return v(F,O,6);case 6:return q=F.j,r=Math.round(P()),Wm(a,k,r,g,void 0,b.join(),e),F.return(q);case 4:w=Aa(F);t=Math.round(P());z=Cm(w,a.i.name,b.join(),a.i.version);
if((E=z instanceof ym&&!z.i)||g>=f)Wm(a,k,t,g,z,b.join(),e),h=z;F.B(2);break;case 3:return F.return(Promise.reject(h))}})}
function Wm(a,b,c,d,e,f,g){b=c-b;e?(e instanceof ym&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&nm("QUOTA_EXCEEDED",{dbName:rm(a.i.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof ym&&"UNKNOWN_ABORT"===e.type&&(c-=a.l,0>c&&c>=Math.pow(2,31)&&(c=0),nm("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.j=!0),Xm(a,!1,d,f,b,g.tag),mm(e)):Xm(a,!0,d,f,b,g.tag)}
function Xm(a,b,c,d,e,f){nm("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.j,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
l.getName=function(){return this.i.name};
function Sm(a){this.i=a}
l=Sm.prototype;l.add=function(a,b){return Nm(this.i.add(a,b))};
l.autoIncrement=function(){return this.i.autoIncrement};
l.clear=function(){return Nm(this.i.clear()).then(function(){})};
l.count=function(a){return Nm(this.i.count(a))};
function Ym(a,b){return Zm(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
l.delete=function(a){return a instanceof IDBKeyRange?Ym(this,a):Nm(this.i.delete(a))};
l.get=function(a){return Nm(this.i.get(a))};
l.index=function(a){try{return new $m(this.i.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new Am(a,this.i.name);throw b;}};
l.getName=function(){return this.i.name};
l.keyPath=function(){return this.i.keyPath};
function Zm(a,b,c){a=a.i.openCursor(b.query,b.direction);return an(a).then(function(d){return Om(d,c)})}
function Um(a){var b=this;this.i=a;this.l=new Map;this.j=!1;this.done=new Promise(function(c,d){b.i.addEventListener("complete",function(){c()});
b.i.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.i.error)});
b.i.addEventListener("abort",function(){var e=b.i.error;if(e)d(e);else if(!b.j){e=ym;for(var f=b.i.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.i.db.name,mode:b.i.mode});d(e)}})})}
function Vm(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return p(d).next().value})}
Um.prototype.abort=function(){this.i.abort();this.j=!0;throw new ym("EXPLICIT_ABORT");};
Um.prototype.objectStore=function(a){a=this.i.objectStore(a);var b=this.l.get(a);b||(b=new Sm(a),this.l.set(a,b));return b};
function $m(a){this.i=a}
l=$m.prototype;l.count=function(a){return Nm(this.i.count(a))};
l.delete=function(a){return bn(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
l.get=function(a){return Nm(this.i.get(a))};
l.getKey=function(a){return Nm(this.i.getKey(a))};
l.keyPath=function(){return this.i.keyPath};
l.unique=function(){return this.i.unique};
function bn(a,b,c){a=a.i.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return an(a).then(function(d){return Om(d,c)})}
function cn(a,b){this.request=a;this.cursor=b}
function an(a){return Nm(a).then(function(b){return b?new cn(a,b):null})}
l=cn.prototype;l.advance=function(a){this.cursor.advance(a);return an(this.request)};
l.continue=function(a){this.cursor.continue(a);return an(this.request)};
l.delete=function(){return Nm(this.cursor.delete()).then(function(){})};
l.getKey=function(){return this.cursor.key};
l.getValue=function(){return this.cursor.value};
l.update=function(a){return Nm(this.cursor.update(a))};function dn(a,b,c){return new Promise(function(d,e){function f(){w||(w=new Pm(g.result,{closed:r}));return w}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,m=c.yd,q=c.upgrade,r=c.closed,w;g.addEventListener("upgradeneeded",function(t){try{if(null===t.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&"none"!==t.dataLoss&&nm("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:rm(a)});var z=f(),E=new Um(g.transaction);
q&&q(z,function(F){return t.oldVersion<F&&t.newVersion>=F},E);
E.done.catch(function(F){e(F)})}catch(F){e(F)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){nm("IDB_UNEXPECTEDLY_CLOSED",{dbName:rm(a),dbVersion:t.version});m&&m()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function en(a,b,c){c=void 0===c?{}:c;return dn(a,b,c)}
function fn(a,b){b=void 0===b?{}:b;var c,d,e,f;return x(function(g){if(1==g.i)return ya(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.blocked)&&c.addEventListener("blocked",function(){e()}),v(g,Mm(c),4);
if(2!=g.i)return za(g,0);f=Aa(g);throw Cm(f,a,"",-1);})}
;function gn(a){return new Promise(function(b){Yl(function(){b()},a)})}
function hn(a,b){this.name=a;this.options=b;this.m=!0;this.s=this.o=0;this.j=500}
hn.prototype.l=function(a,b,c){c=void 0===c?{}:c;return en(a,b,c)};
hn.prototype.delete=function(a){a=void 0===a?{}:a;return fn(this.name,a)};
function jn(a,b){return new ym("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function kn(a,b){if(!b)throw Dm("openWithToken",rm(a.name));return ln(a)}
function ln(a){function b(){var f,g,h,k,m,q,r,w,t,z;return x(function(E){switch(E.i){case 1:return g=null!=(f=Error().stack)?f:"",ya(E,2),v(E,a.l(a.name,a.options.version,d),4);case 4:h=E.j;for(var F=a.options,O=[],N=p(Object.keys(F.Na)),Q=N.next();!Q.done;Q=N.next()){Q=Q.value;var da=F.Na[Q],U=void 0===da.hd?Number.MAX_VALUE:da.hd;!(h.i.version>=da.rb)||h.i.version>=U||h.i.objectStoreNames.contains(Q)||O.push(Q)}k=O;if(0===k.length){E.B(5);break}m=Object.keys(a.options.Na);q=h.objectStoreNames();
if(a.s<xk("ytidb_reopen_db_retries",0))return a.s++,h.close(),mm(new ym("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:q})),E.return(b());if(!(a.o<xk("ytidb_remake_db_retries",1))){E.B(6);break}a.o++;if(!M("ytidb_remake_db_enable_backoff_delay")){E.B(7);break}return v(E,gn(a.j),8);case 8:a.j*=2;case 7:return v(E,a.delete(),9);case 9:return mm(new ym("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:q})),E.return(b());
case 6:throw new zm(q,m);case 5:return E.return(h);case 2:r=Aa(E);if(r instanceof DOMException?"VersionError"!==r.name:"DOMError"in self&&r instanceof DOMError?"VersionError"!==r.name:!(r instanceof Object&&"message"in r)||"An attempt was made to open a database using a lower version than the existing version."!==r.message){E.B(10);break}return v(E,a.l(a.name,void 0,Object.assign({},d,{upgrade:void 0})),11);case 11:w=E.j;t=w.i.version;if(void 0!==a.options.version&&t>a.options.version+1)throw w.close(),
a.m=!1,jn(a,t);return E.return(w);case 10:throw c(),r instanceof Error&&!M("ytidb_async_stack_killswitch")&&(r.stack=r.stack+"\n"+g.substring(g.indexOf("\n")+1)),Cm(r,a.name,"",null!=(z=a.options.version)?z:-1);}})}
function c(){a.i===e&&(a.i=void 0)}
if(!a.m)throw jn(a);if(a.i)return a.i;var d={blocking:function(f){f.close()},
closed:c,yd:c,upgrade:a.options.upgrade};var e=b();a.i=e;return a.i}
;var mn=new hn("YtIdbMeta",{Na:{databases:{rb:1}},upgrade:function(a,b){b(1)&&Rm(a,"databases",{keyPath:"actualName"})}});
function nn(a,b){var c;return x(function(d){if(1==d.i)return v(d,kn(mn,b),2);c=d.j;return d.return(Qm(c,["databases"],{U:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Nm(f.i.put(a,void 0)).then(function(){})})}))})}
function on(a,b){var c;return x(function(d){if(1==d.i)return a?v(d,kn(mn,b),2):d.return();c=d.j;return d.return(c.delete("databases",a))})}
function pn(a,b){var c,d;return x(function(e){return 1==e.i?(c=[],v(e,kn(mn,b),2)):3!=e.i?(d=e.j,v(e,Qm(d,["databases"],{U:!0,mode:"readonly"},function(f){c.length=0;return Zm(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function qn(a){return pn(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function rn(a,b,c){return pn(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function sn(a){var b,c;return x(function(d){if(1==d.i)return b=pm("YtIdbMeta hasAnyMeta other"),v(d,pn(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.j;return d.return(0<c.length)})}
;var tn,un=new function(){}(new function(){});
function vn(){var a,b,c,d;return x(function(e){switch(e.i){case 1:a=em();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=bm)f=/WebKit\/([0-9]+)/.exec(Tb()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Tb()),f=!(f&&602<=parseInt(f[1],10)));if(f||Lc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
ya(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return v(e,nn(d,un),4);case 4:return v(e,on("yt-idb-test-do-not-use",un),5);case 5:return e.return(!0);case 2:return Aa(e),e.return(!1)}})}
function wn(){if(void 0!==tn)return tn;hm=!0;return tn=vn().then(function(a){hm=!1;var b;if(null!=(b=dm())&&b.i){var c;b={hasSucceededOnce:(null==(c=em())?void 0:c.hasSucceededOnce)||a};var d;null==(d=dm())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function xn(){var a=B("ytglobal.idbToken_")||void 0;return a?Promise.resolve(a):wn().then(function(b){(b=b?un:void 0)&&A("ytglobal.idbToken_",b);return b})}
;var yn=0;function zn(a,b){yn||(yn=Qh.V(function(){var c,d,e,f,g;return x(function(h){switch(h.i){case 1:return v(h,xn(),2);case 2:c=h.j;if(!c)return h.return();d=!0;ya(h,3);return v(h,rn(a,c,b),5);case 5:e=h.j;if(!e.length){d=!1;h.B(6);break}f=e[0];return v(h,fn(f.actualName),7);case 7:return v(h,on(f.actualName,c),6);case 6:za(h,4);break;case 3:g=Aa(h),mm(g),d=!1;case 4:Qh.ga(yn),yn=0,d&&zn(a,b),h.i=0}})}))}
function An(){var a;return x(function(b){return 1==b.i?v(b,xn(),2):(a=b.j)?b.return(sn(a)):b.return(!1)})}
new uh;function Bn(a){if(!om())throw a=new ym("AUTH_INVALID",{dbName:a}),mm(a),a;var b=pm();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Cn(a,b,c,d){var e,f,g,h,k,m;return x(function(q){switch(q.i){case 1:return f=null!=(e=Error().stack)?e:"",v(q,xn(),2);case 2:g=q.j;if(!g)throw h=Dm("openDbImpl",a,b),M("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),mm(h),h;qm(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Bn(a);ya(q,3);return v(q,nn(k,g),5);case 5:return v(q,en(k.actualName,b,d),6);case 6:return q.return(q.j);case 3:return m=Aa(q),ya(q,7),v(q,on(k.actualName,g),9);case 9:za(q,
8);break;case 7:Aa(q);case 8:throw m;}})}
function Dn(a,b,c){c=void 0===c?{}:c;return Cn(a,b,!1,c)}
function En(a,b,c){c=void 0===c?{}:c;return Cn(a,b,!0,c)}
function Fn(a,b){b=void 0===b?{}:b;var c,d;return x(function(e){if(1==e.i)return v(e,xn(),2);if(3!=e.i){c=e.j;if(!c)return e.return();qm(a);d=Bn(a);return v(e,fn(d.actualName,b),3)}return v(e,on(d.actualName,c),0)})}
function Gn(a,b,c){a=a.map(function(d){return x(function(e){return 1==e.i?v(e,fn(d.actualName,b),2):v(e,on(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Hn(){var a=void 0===a?{}:a;var b,c;return x(function(d){if(1==d.i)return v(d,xn(),2);if(3!=d.i){b=d.j;if(!b)return d.return();qm("LogsDatabaseV2");return v(d,qn(b),3)}c=d.j;return v(d,Gn(c,a,b),0)})}
function In(a,b){b=void 0===b?{}:b;var c;return x(function(d){if(1==d.i)return v(d,xn(),2);if(3!=d.i){c=d.j;if(!c)return d.return();qm(a);return v(d,fn(a,b),3)}return v(d,on(a,c),0)})}
;function Jn(a){this.Za=this.i=!1;this.potentialEsfErrorCounter=this.j=0;this.handleError=function(){};
this.Ea=function(){};
this.now=Date.now;this.La=!1;var b;this.xc=null!=(b=a.xc)?b:100;var c;this.tc=null!=(c=a.tc)?c:1;var d;this.qc=null!=(d=a.qc)?d:2592E6;var e;this.oc=null!=(e=a.oc)?e:12E4;var f;this.sc=null!=(f=a.sc)?f:5E3;var g;this.I=null!=(g=a.I)?g:void 0;this.fb=!!a.fb;var h;this.cb=null!=(h=a.cb)?h:.1;var k;this.jb=null!=(k=a.jb)?k:10;a.handleError&&(this.handleError=a.handleError);a.Ea&&(this.Ea=a.Ea);a.La&&(this.La=a.La);a.Za&&(this.Za=a.Za);this.J=a.J;this.aa=a.aa;this.N=a.N;this.M=a.M;this.ja=a.ja;this.Gb=
a.Gb;this.Fb=a.Fb;Kn(this)&&(!this.J||this.J("networkless_logging"))&&Ln(this)}
function Ln(a){Kn(a)&&!a.La&&(a.i=!0,a.fb&&Math.random()<=a.cb&&a.N.Lc(a.I),Mn(a),a.M.W()&&a.Qa(),a.M.ia(a.Gb,a.Qa.bind(a)),a.M.ia(a.Fb,a.Tb.bind(a)))}
l=Jn.prototype;l.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(Kn(this)&&this.i){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.N.set(d,this.I).then(function(e){d.id=e;c.M.W()&&Nn(c,d)}).catch(function(e){Nn(c,d);
On(c,e)})}else this.ja(a,b)};
l.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(Kn(this)&&this.i){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.J&&this.J("nwl_skip_retry")&&(e.skipRetry=c);if(this.M.W()||this.J&&this.J("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return x(function(k){if(1==k.i)return v(k,d.N.set(e,d.I).catch(function(m){On(d,m)}),2);
f(g,h);k.i=0})}}this.ja(a,b,e.skipRetry)}else this.N.set(e,this.I).catch(function(g){d.ja(a,b,e.skipRetry);
On(d,g)})}else this.ja(a,b,this.J&&this.J("nwl_skip_retry")&&c)};
l.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(Kn(this)&&this.i){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.N.Da(d.id,c.I):e=!0;c.M.ya&&c.J&&c.J("vss_network_hint")&&c.M.ya(!0);f(g,h)};
this.ja(d.url,d.options);this.N.set(d,this.I).then(function(g){d.id=g;e&&c.N.Da(d.id,c.I)}).catch(function(g){On(c,g)})}else this.ja(a,b)};
l.Qa=function(){var a=this;if(!Kn(this))throw Dm("throttleSend");this.j||(this.j=this.aa.V(function(){var b;return x(function(c){if(1==c.i)return v(c,a.N.ec("NEW",a.I),2);if(3!=c.i)return b=c.j,b?v(c,Nn(a,b),3):(a.Tb(),c.return());a.j&&(a.j=0,a.Qa());c.i=0})},this.xc))};
l.Tb=function(){this.aa.ga(this.j);this.j=0};
function Nn(a,b){var c,d;return x(function(e){switch(e.i){case 1:if(!Kn(a))throw c=Dm("immediateSend"),c;if(void 0===b.id){e.B(2);break}return v(e,a.N.Zc(b.id,a.I),3);case 3:(d=e.j)?b=d:a.Ea(Error("The request cannot be found in the database."));case 2:if(Pn(a,b,a.qc)){e.B(4);break}a.Ea(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.B(5);break}return v(e,a.N.Da(b.id,a.I),5);case 5:return e.return();case 4:b.skipRetry||(b=Qn(a,b));if(!b){e.B(0);break}if(!b.skipRetry||
void 0===b.id){e.B(8);break}return v(e,a.N.Da(b.id,a.I),8);case 8:a.ja(b.url,b.options,!!b.skipRetry),e.i=0}})}
function Qn(a,b){if(!Kn(a))throw Dm("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k;return x(function(m){switch(m.i){case 1:g=Rn(f);if(!(a.J&&a.J("nwl_consider_error_code")&&g||a.J&&!a.J("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.jb)){m.B(2);break}if(!a.M.mb){m.B(3);break}return v(m,a.M.mb(),3);case 3:if(a.M.W()){m.B(2);break}c(e,f);if(!a.J||!a.J("nwl_consider_error_code")||void 0===(null==(h=b)?void 0:h.id)){m.B(6);break}return v(m,a.N.Jb(b.id,a.I,!1),6);case 6:return m.return();case 2:if(a.J&&a.J("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.jb)return m.return();a.potentialEsfErrorCounter++;if(void 0===(null==(k=b)?void 0:k.id)){m.B(8);break}return b.sendCount<a.tc?v(m,a.N.Jb(b.id,a.I),12):v(m,a.N.Da(b.id,a.I),8);case 12:a.aa.V(function(){a.M.W()&&a.Qa()},a.sc);
case 8:c(e,f),m.i=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return x(function(h){if(1==h.i)return void 0===(null==(g=b)?void 0:g.id)?h.B(2):v(h,a.N.Da(b.id,a.I),2);a.M.ya&&a.J&&a.J("vss_network_hint")&&a.M.ya(!0);d(e,f);h.i=0})};
return b}
function Pn(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function Mn(a){if(!Kn(a))throw Dm("retryQueuedRequests");a.N.ec("QUEUED",a.I).then(function(b){b&&!Pn(a,b,a.oc)?a.aa.V(function(){return x(function(c){if(1==c.i)return void 0===b.id?c.B(2):v(c,a.N.Jb(b.id,a.I),2);Mn(a);c.i=0})}):a.M.W()&&a.Qa()})}
function On(a,b){a.Bc&&!a.M.W()?a.Bc(b):a.handleError(b)}
function Kn(a){return!!a.I||a.Za}
function Rn(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function Sn(a,b){this.version=a;this.args=b}
;function Tn(a,b){this.topic=a;this.i=b}
Tn.prototype.toString=function(){return this.topic};var Un=B("ytPubsub2Pubsub2Instance")||new K;K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.Ia;K.prototype.publish=K.prototype.ta;K.prototype.clear=K.prototype.clear;A("ytPubsub2Pubsub2Instance",Un);var Vn=B("ytPubsub2Pubsub2SubscribedKeys")||{};A("ytPubsub2Pubsub2SubscribedKeys",Vn);var Wn=B("ytPubsub2Pubsub2TopicToKeys")||{};A("ytPubsub2Pubsub2TopicToKeys",Wn);var Xn=B("ytPubsub2Pubsub2IsAsync")||{};A("ytPubsub2Pubsub2IsAsync",Xn);
A("ytPubsub2Pubsub2SkipSubKey",null);function Yn(a,b){var c=Zn();c&&c.publish.call(c,a.toString(),a,b)}
function $n(a){var b=ao,c=Zn();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=B("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(Vn[d])try{if(f&&b instanceof Tn&&b!=e)try{var h=b.i,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.ra){var m=new h;h.ra=m.version}var q=h.ra}catch(F){}if(!q||k.version!=q)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{q=Reflect;var r=q.construct;
var w=k.args,t=w.length;if(0<t){var z=Array(t);for(k=0;k<t;k++)z[k]=w[k];var E=z}else E=[];f=r.call(q,h,E)}catch(F){throw F.message="yt.pubsub2.Data.deserialize(): "+F.message,F;}}catch(F){throw F.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+F.message,F;}a.call(window,f)}catch(F){Dk(F)}},Xn[b.toString()]?B("yt.scheduler.instance")?Qh.V(g):Xk(g,0):g())});
Vn[d]=!0;Wn[b.toString()]||(Wn[b.toString()]=[]);Wn[b.toString()].push(d);return d}
function bo(){var a=co,b=$n(function(c){a.apply(void 0,arguments);eo(b)});
return b}
function eo(a){var b=Zn();b&&("number"===typeof a&&(a=[a]),fb(a,function(c){b.unsubscribeByKey(c);delete Vn[c]}))}
function Zn(){return B("ytPubsub2Pubsub2Instance")}
;function fo(a,b){hn.call(this,a,b);this.options=b;qm(a)}
u(fo,hn);function go(a,b){var c;return function(){c||(c=new fo(a,b));return c}}
fo.prototype.l=function(a,b,c){c=void 0===c?{}:c;return(this.options.Lb?En:Dn)(a,b,Object.assign({},c))};
fo.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Lb?In:Fn)(this.name,a)};
function ho(a,b){return go(a,b)}
;var io;
function jo(){if(io)return io();var a={};io=ho("LogsDatabaseV2",{Na:(a.LogsRequestsStore={rb:2},a),Lb:!1,upgrade:function(b,c,d){c(2)&&Rm(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.i.indexNames.contains("newRequest")&&d.i.deleteIndex("newRequest"),d.i.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.i.objectStoreNames.contains("sapisid")&&b.i.deleteObjectStore("sapisid");c(9)&&b.i.objectStoreNames.contains("SWHealthLog")&&b.i.deleteObjectStore("SWHealthLog")},
version:9});return io()}
;function ko(a){return kn(jo(),a)}
function lo(a,b){var c,d,e,f;return x(function(g){if(1==g.i)return c={startTime:P(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},v(g,ko(b),2);if(3!=g.i)return d=g.j,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:L("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),v(g,Tm(d,e),3);f=g.j;c.Ad=P();mo(c);return g.return(f)})}
function no(a,b){var c,d,e,f,g,h,k;return x(function(m){if(1==m.i)return c={startTime:P(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},v(m,ko(b),2);if(3!=m.i)return d=m.j,e=L("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,P()],h=IDBKeyRange.bound(f,g),k=void 0,v(m,Qm(d,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(q){return bn(q.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(r){r.getValue()&&(k=r.getValue(),"NEW"===a&&(k.status="QUEUED",
r.update(k)))})}),3);
c.Ad=P();mo(c);return m.return(k)})}
function oo(a,b){var c;return x(function(d){if(1==d.i)return v(d,ko(b),2);c=d.j;return d.return(Qm(c,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Nm(f.i.put(g,void 0)).then(function(){return g})})}))})}
function po(a,b,c){c=void 0===c?!0:c;var d;return x(function(e){if(1==e.i)return v(e,ko(b),2);d=e.j;return e.return(Qm(d,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",c&&(h.sendCount+=1),Nm(g.i.put(h,void 0)).then(function(){return h})):Hm.resolve(void 0)})}))})}
function qo(a,b){var c;return x(function(d){if(1==d.i)return v(d,ko(b),2);c=d.j;return d.return(c.delete("LogsRequestsStore",a))})}
function ro(a){var b,c;return x(function(d){if(1==d.i)return v(d,ko(a),2);b=d.j;c=P()-2592E6;return v(d,Qm(b,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(e){return Zm(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function so(){x(function(a){return v(a,Hn(),0)})}
function mo(a){M("nwl_csi_killswitch")||.01>=Math.random()&&Yn("nwl_transaction_latency_payload",a)}
;var to={},uo=ho("ServiceWorkerLogsDatabase",{Na:(to.SWHealthLog={rb:1},to),Lb:!0,upgrade:function(a,b){b(1)&&Rm(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).i.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function vo(a){return kn(uo(),a)}
function wo(a){var b,c;x(function(d){if(1==d.i)return v(d,vo(a),2);b=d.j;c=P()-2592E6;return v(d,Qm(b,["SWHealthLog"],{mode:"readwrite",U:!0},function(e){return Zm(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function xo(a){var b;return x(function(c){if(1==c.i)return v(c,vo(a),2);b=c.j;return v(c,b.clear("SWHealthLog"),0)})}
;var yo={},zo=0;function Ao(a){var b=new Image,c=""+zo++;yo[c]=b;b.onload=b.onerror=function(){delete yo[c]};
b.src=a}
;function Bo(){this.i=new Map;this.j=!1}
function Co(){if(!Bo.i){var a=B("yt.networkRequestMonitor.instance")||new Bo;A("yt.networkRequestMonitor.instance",a);Bo.i=a}return Bo.i}
Bo.prototype.requestComplete=function(a,b){b&&(this.j=!0);a=this.removeParams(a);this.i.get(a)||this.i.set(a,b)};
Bo.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.i.get(a))?!1:!1===a&&this.j?!0:null};
Bo.prototype.removeParams=function(a){return a.split("?")[0]};
Bo.prototype.removeParams=Bo.prototype.removeParams;Bo.prototype.isEndpointCFR=Bo.prototype.isEndpointCFR;Bo.prototype.requestComplete=Bo.prototype.requestComplete;Bo.getInstance=Co;var Do;function Eo(){Do||(Do=new Nl("yt.offline"));return Do}
function Fo(a){if(M("offline_error_handling")){var b=Eo().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Eo().set("errors",b,2592E3,!0)}}
;function Go(){Ue.call(this);var a=this;this.l=!1;this.j=Ph();this.j.ia("networkstatus-online",function(){if(a.l&&M("offline_error_handling")){var b=Eo().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new R(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;Dk(d)}Eo().set("errors",{},2592E3,!0)}}})}
u(Go,Ue);function Ho(){if(!Go.i){var a=B("yt.networkStatusManager.instance")||new Go;A("yt.networkStatusManager.instance",a);Go.i=a}return Go.i}
l=Go.prototype;l.W=function(){return this.j.W()};
l.ya=function(a){this.j.j=a};
l.Uc=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
l.Pc=function(){this.l=!0};
l.ia=function(a,b){return this.j.ia(a,b)};
l.mb=function(a){a=Nh(this.j,a);a.then(function(b){M("use_cfr_monitor")&&Co().requestComplete("generate_204",b)});
return a};
Go.prototype.sendNetworkCheckRequest=Go.prototype.mb;Go.prototype.listen=Go.prototype.ia;Go.prototype.enableErrorFlushing=Go.prototype.Pc;Go.prototype.getWindowStatus=Go.prototype.Uc;Go.prototype.networkStatusHint=Go.prototype.ya;Go.prototype.isNetworkAvailable=Go.prototype.W;Go.getInstance=Ho;function Io(a){a=void 0===a?{}:a;Ue.call(this);var b=this;this.j=this.s=0;this.l=Ho();var c=B("yt.networkStatusManager.instance.listen").bind(this.l);c&&(a.lb?(this.lb=a.lb,c("networkstatus-online",function(){Jo(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Jo(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){Ve(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Ve(b,"publicytnetworkstatus-offline")})))}
u(Io,Ue);Io.prototype.W=function(){var a=B("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.l)():!0};
Io.prototype.ya=function(a){var b=B("yt.networkStatusManager.instance.networkStatusHint").bind(this.l);b&&b(a)};
Io.prototype.mb=function(a){var b=this,c;return x(function(d){c=B("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.l);return M("skip_network_check_if_cfr")&&Co().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.ya((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.W())})):c?d.return(c(a)):d.return(!0)})};
function Jo(a,b){a.lb?a.j?(Qh.ga(a.s),a.s=Qh.V(function(){a.o!==b&&(Ve(a,b),a.o=b,a.j=P())},a.lb-(P()-a.j))):(Ve(a,b),a.o=b,a.j=P()):Ve(a,b)}
;var Ko;function Lo(){var a=Jn.call;Ko||(Ko=new Io({rr:!0,kr:!0}));a.call(Jn,this,{N:{Lc:ro,Da:qo,ec:no,Zc:oo,Jb:po,set:lo},M:Ko,handleError:Dk,Ea:Ek,ja:Mo,now:P,Bc:Fo,aa:am(),Gb:"publicytnetworkstatus-online",Fb:"publicytnetworkstatus-offline",fb:!0,cb:.1,jb:xk("potential_esf_error_limit",10),J:M,La:!(om()&&No())});this.l=new uh;M("networkless_immediately_drop_all_requests")&&so();In("LogsDatabaseV2")}
u(Lo,Jn);function Oo(){var a=B("yt.networklessRequestController.instance");a||(a=new Lo,A("yt.networklessRequestController.instance",a),M("networkless_logging")&&xn().then(function(b){a.I=b;Ln(a);a.l.resolve();a.fb&&Math.random()<=a.cb&&a.I&&wo(a.I);M("networkless_immediately_drop_sw_health_store")&&Po(a)}));
return a}
Lo.prototype.writeThenSend=function(a,b){b||(b={});om()||(this.i=!1);Jn.prototype.writeThenSend.call(this,a,b)};
Lo.prototype.sendThenWrite=function(a,b,c){b||(b={});om()||(this.i=!1);Jn.prototype.sendThenWrite.call(this,a,b,c)};
Lo.prototype.sendAndWrite=function(a,b){b||(b={});om()||(this.i=!1);Jn.prototype.sendAndWrite.call(this,a,b)};
Lo.prototype.awaitInitialization=function(){return this.l.promise};
function Po(a){var b;x(function(c){if(!a.I)throw b=Dm("clearSWHealthLogsDb"),b;return c.return(xo(a.I).catch(function(d){a.handleError(d)}))})}
function Mo(a,b,c){M("use_cfr_monitor")&&Qo(a,b);if(M("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(P())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(P())}if(c&&0===Object.keys(b).length){var e=void 0===e?"":e;var f=void 0===f?!1:f;if(a)if(e)gl(a,void 0,"POST",e);else if(L("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))gl(a,void 0,"GET","",void 0,void 0,f);else{b:{try{var g=new bb({url:a});if(g.l&&g.j||
g.m){var h=mc(nc(5,a)),k;if(!(k=!h||!h.endsWith("/aclk"))){var m=a.search(Bc),q=Ac(a,0,"ri",m);if(0>q)var r=null;else{var w=a.indexOf("&",q);if(0>w||w>m)w=m;r=decodeURIComponent(a.slice(q+3,-1!==w?w:0).replace(/\+/g," "))}k="1"!==r}var t=!k;break b}}catch(E){}t=!1}if(t){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var z=!0;break b}}catch(E){}z=!1}c=z?!0:!1}else c=!1;c||Ao(a)}}else dl(a,b)}
function Qo(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Co().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Co().requestComplete(a,!0);d(e,f)}}
function No(){return"www.youtube-nocookie.com"!==oc(document.location.toString())}
;var Ro=!1,ep=y.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Ro};A("ytNetworklessLoggingInitializationOptions",ep);function Dp(){var a;x(function(b){if(1==b.i)return v(b,xn(),2);a=b.j;if(!a||!om()&&!M("nwl_init_require_datasync_id_killswitch")||!No())return b.B(0);Ro=!0;ep.isNwlInitialized=Ro;return v(b,Oo().awaitInitialization(),0)})}
;function Ep(a){var b=this;this.config_=null;a?this.config_=a:Dl()&&(this.config_=El());Wl(function(){Tl(b)},5E3)}
Ep.prototype.isReady=function(){!this.config_&&Dl()&&(this.config_=El());return!!this.config_};
function Ul(a,b,c,d){function e(z){z=void 0===z?!1:z;var E;if(d.retry&&"www.youtube-nocookie.com"!=h&&(z||M("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(E=Rl(b,c,m,k)),E)){var F=g.onSuccess,O=g.onFetchSuccess;g.onSuccess=function(N,Q){Sl(E);F(N,Q)};
c.onFetchSuccess=function(N,Q){Sl(E);O(N,Q)}}try{z&&d.retry&&!d.lc.bypassNetworkless?(g.method="POST",d.lc.writeThenSend?Oo().writeThenSend(t,g):Oo().sendAndWrite(t,g)):M("web_all_payloads_via_jspb")?dl(t,g):(g.method="POST",g.postParams||(g.postParams={}),dl(t,g))}catch(N){if("InvalidAccessError"==N.name)E&&(Sl(E),E=0),Ek(Error("An extension is blocking network request."));
else throw N;}E&&Wl(function(){Tl(a)},5E3)}
!L("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Ek(new R("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new R("innertube xhrclient not ready",b,c,d);Dk(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(z,E){if(d.onSuccess)d.onSuccess(E)},
onFetchSuccess:function(z){if(d.onSuccess)d.onSuccess(z)},
onError:function(z,E){if(d.onError)d.onError(E)},
onFetchError:function(z){if(d.onError)d.onError(z)},
timeout:d.timeout,withCredentials:!0};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.Wc)&&(h=f);var k=a.config_.Yc||!1,m=Ll(k,h,d);Object.assign(g.headers,m);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var q="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,r={alt:"json"},w=a.config_.Xc&&f;w=w&&f.startsWith("Bearer");w||(r.key=a.config_.innertubeApiKey);var t=Qk(""+h+q,r||{},!0);(B("ytNetworklessLoggingInitializationOptions")?
ep.isNwlInitialized:Ro)?wn().then(function(z){e(z)}):e(!1)}
;var Fp=0,Gp=Nc?"webkit":Mc?"moz":Kc?"ms":Jc?"o":"";A("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++Fp});var Hp={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Ip(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Hp||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.i=a.pageX;this.j=a.pageY}}catch(e){}}
function Jp(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.i=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.j=a.clientY+b}}
Ip.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Ip.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Ip.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var qb=y.ytEventsEventsListeners||{};A("ytEventsEventsListeners",qb);var Kp=y.ytEventsEventsCounter||{count:0};A("ytEventsEventsCounter",Kp);
function Lp(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return pb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Qa(e[4])&&Qa(d)&&ub(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Mp=db(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Np(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Lp(a,b,c,d);if(e)return e;e=++Kp.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Ip(h);if(!df(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Ip(h);
h.currentTarget=a;return c.call(a,h)};
g=Ck(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Mp()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);qb[e]=[a,b,c,g,d];return e}
function Op(a){a&&("string"==typeof a&&(a=[a]),fb(a,function(b){if(b in qb){var c=qb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Mp()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete qb[b]}}))}
;var Pp=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function Qp(a){this.H=a;this.j=null;this.o=0;this.u=null;this.s=0;this.l=[];for(a=0;4>a;a++)this.l.push(0);this.m=0;this.L=Np(window,"mousemove",Xa(this.P,this));a=Xa(this.K,this);"function"===typeof a&&(a=Ck(a));this.R=window.setInterval(a,25)}
Za(Qp,J);Qp.prototype.P=function(a){void 0===a.i&&Jp(a);var b=a.i;void 0===a.j&&Jp(a);this.j=new $e(b,a.j)};
Qp.prototype.K=function(){if(this.j){var a=Pp();if(0!=this.o){var b=this.u,c=this.j,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.o);this.l[this.m]=.5<Math.abs((d-this.s)/this.s)?1:0;for(c=b=0;4>c;c++)b+=this.l[c]||0;3<=b&&this.H();this.s=d}this.o=a;this.u=this.j;this.m=(this.m+1)%4}};
Qp.prototype.D=function(){window.clearInterval(this.R);Op(this.L)};var Rp={};
function Sp(a){var b=void 0===a?{}:a;a=void 0===b.ed?!1:b.ed;b=void 0===b.Qc?!0:b.Qc;if(null==B("_lact",window)){var c=parseInt(L("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;A("_lact",c,window);A("_fact",c,window);-1==c&&Tp();Np(document,"keydown",Tp);Np(document,"keyup",Tp);Np(document,"mousedown",Tp);Np(document,"mouseup",Tp);a?Np(window,"touchmove",function(){Up("touchmove",200)},{passive:!0}):(Np(window,"resize",function(){Up("resize",200)}),b&&Np(window,"scroll",function(){Up("scroll",200)}));
new Qp(function(){Up("mouse",100)});
Np(document,"touchstart",Tp,{passive:!0});Np(document,"touchend",Tp,{passive:!0})}}
function Up(a,b){Rp[a]||(Rp[a]=!0,Qh.V(function(){Tp();Rp[a]=!1},b))}
function Tp(){null==B("_lact",window)&&Sp();var a=Date.now();A("_lact",a,window);-1==B("_fact",window)&&A("_fact",a,window);(a=B("ytglobal.ytUtilActivityCallback_"))&&a()}
function Vp(){var a=B("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var Wp=y.ytPubsubPubsubInstance||new K,Xp=y.ytPubsubPubsubSubscribedKeys||{},Yp=y.ytPubsubPubsubTopicToKeys||{},Zp=y.ytPubsubPubsubIsSynchronous||{};function $p(a,b){var c=aq();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Xp[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Zp[a]?f():Xk(f,0)}catch(g){Dk(g)}},void 0);
Xp[d]=!0;Yp[a]||(Yp[a]=[]);Yp[a].push(d);return d}return 0}
function bq(a){var b=aq();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),fb(a,function(c){b.unsubscribeByKey(c);delete Xp[c]}))}
function cq(a,b){var c=aq();c&&c.publish.apply(c,arguments)}
function dq(a){var b=aq();if(b)if(b.clear(a),a)eq(a);else for(var c in Yp)eq(c)}
function aq(){return y.ytPubsubPubsubInstance}
function eq(a){Yp[a]&&(a=Yp[a],fb(a,function(b){Xp[b]&&delete Xp[b]}),a.length=0)}
K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.Ia;K.prototype.publish=K.prototype.ta;K.prototype.clear=K.prototype.clear;A("ytPubsubPubsubInstance",Wp);A("ytPubsubPubsubTopicToKeys",Yp);A("ytPubsubPubsubIsSynchronous",Zp);A("ytPubsubPubsubSubscribedKeys",Xp);function fq(){this.store=[];this.i={}}
fq.prototype.storePayload=function(a,b){this.store.push({payload:b,keys:a});a=gq(a);this.i[a]?this.i[a]++:this.i[a]=1;return a};
fq.prototype.extractMatchingEntries=function(a){for(var b=[],c=[],d=p(this.store),e=d.next();!e.done;e=d.next()){e=e.value;a:{var f=a;var g=Object.keys(f);g=p(g);for(var h=g.next();!h.done;h=g.next())if(h=h.value,e.keys[h]!==f[h]){f=!1;break a}f=!0}f?(b.push(e.payload),this.i[gq(e.keys)]--):c.push(e)}this.store=c;a=hq(this,a);a=p(a);for(c=a.next();!c.done;c=a.next())c=c.value,0<this.i[c]&&Ek(new R("Transport IMS did not fully extract entries for key:",{sequence:c,ur:b.length,tr:this.i[c]}));return b};
fq.prototype.getSequenceCount=function(a){var b=hq(this,a);a=0;b=p(b);for(var c=b.next();!c.done;c=b.next())a+=this.i[c.value];return a};
function hq(a,b){var c=Object.keys(b),d="THIS_KEY_FIELD_NOT_FILLED",e="THIS_KEY_FIELD_NOT_FILLED",f="THIS_KEY_FIELD_NOT_FILLED";c=p(c);for(var g=c.next();!g.done;g=c.next())g=g.value,"auth"===g?d=iq(b.auth):"isJspb"===g?(e=b.isJspb,e=void 0===e?"undefined":e?"true":"false"):"cttAuthInfo"===g&&(f=iq(b.cttAuthInfo));b=[];d=[d,e,f];a=p(Object.keys(a.i));for(f=a.next();!f.done;f=a.next()){f=f.value;e=f.split("/");c=!0;for(g=0;g<d.length;g++)if("THIS_KEY_FIELD_NOT_FILLED"!==d[g]&&d[g]!==e[g]){c=!1;break}c&&
b.push(f)}return b}
fq.prototype.getSequenceCount=fq.prototype.getSequenceCount;fq.prototype.extractMatchingEntries=fq.prototype.extractMatchingEntries;fq.prototype.storePayload=fq.prototype.storePayload;function gq(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo].join("/")}
function iq(a){return void 0===a?"undefined":a}
;var jq=xk("initial_gel_batch_timeout",2E3),kq=Math.pow(2,16)-1,lq=void 0;function mq(){this.l=this.i=this.j=0}
var nq=new mq,oq=new mq,pq,qq=!0,rq=y.ytLoggingTransportGELQueue_||new Map;A("ytLoggingTransportGELQueue_",rq);var sq=y.ytLoggingTransportGELProtoQueue_||new Map;A("ytLoggingTransportGELProtoQueue_",sq);var tq=y.ytLoggingTransportTokensToCttTargetIds_||{};A("ytLoggingTransportTokensToCttTargetIds_",tq);var uq=y.ytLoggingTransportTokensToJspbCttTargetIds_||{};A("ytLoggingTransportTokensToJspbCttTargetIds_",uq);var vq={};function wq(){var a=B("yt.logging.ims");a||(a=new fq,A("yt.logging.ims",a));return a}
function xq(a,b){M("web_all_payloads_via_jspb")&&Ek(new R("transport.log called for JSON in JSPB only experiment"));if("log_event"===a.endpoint){yq(a);var c=zq(a);if(M("use_new_in_memory_storage")){vq[c]=!0;var d={cttAuthInfo:c,isJspb:!1};wq().storePayload(d,a.payload);Aq(b,[],c,!1,d)}else d=rq.get(c)||[],rq.set(c,d),d.push(a.payload),Aq(b,d,c)}}
function Bq(a,b){if("log_event"===a.endpoint){yq(void 0,a);var c=zq(a,!0);if(M("use_new_in_memory_storage")){vq[c]=!0;var d={cttAuthInfo:c,isJspb:!0};wq().storePayload(d,a.payload.toJSON());Aq(b,[],c,!0,d)}else d=sq.get(c)||[],sq.set(c,d),a=a.payload.toJSON(),d.push(a),Aq(b,d,c,!0)}}
function Aq(a,b,c,d,e){d=void 0===d?!1:d;a&&(lq=new a);a=xk("tvhtml5_logging_max_batch")||xk("web_logging_max_batch")||100;var f=P(),g=d?oq.l:nq.l;b=b.length;e&&(b=wq().getSequenceCount(e));b>=a?M("background_thread_flush_logs_due_to_batch_limit")?pq||(pq=Cq(function(){Dq({writeThenSend:!0},M("flush_only_full_queue")?c:void 0,d);pq=void 0},0)):Dq({writeThenSend:!0},M("flush_only_full_queue")?c:void 0,d):10<=f-g&&(Eq(d),d?oq.l=f:nq.l=f)}
function Fq(a,b){M("web_all_payloads_via_jspb")&&Ek(new R("transport.logIsolatedGelPayload called in JSPB only experiment"));if("log_event"===a.endpoint){yq(a);var c=zq(a),d=new Map;d.set(c,[a.payload]);b&&(lq=new b);return new rf(function(e,f){lq&&lq.isReady()?Gq(d,lq,e,f,{bypassNetworkless:!0},!0):e()})}}
function Hq(a,b){if("log_event"===a.endpoint){yq(void 0,a);var c=zq(a,!0),d=new Map;d.set(c,[a.payload.toJSON()]);b&&(lq=new b);return new rf(function(e){lq&&lq.isReady()?Iq(d,lq,e,{bypassNetworkless:!0},!0):e()})}}
function zq(a,b){var c="";if(a.Ka)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new gk;c.videoId?d.setVideoId(c.videoId):c.playlistId&&Od(d,2,hk,c.playlistId);uq[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),tq[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function Dq(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;!c&&M("web_all_payloads_via_jspb")&&Ek(new R("transport.flushLogs called for JSON in JSPB only experiment"));new rf(function(d,e){c?(Yk(oq.j),Yk(oq.i),oq.i=0):(Yk(nq.j),Yk(nq.i),nq.i=0);if(lq&&lq.isReady())if(M("use_new_in_memory_storage")){var f=a,g=c,h=lq;f=void 0===f?{}:f;g=void 0===g?!1:g;var k=new Map,m=new Map;if(void 0!==b)g?(e=wq().extractMatchingEntries({isJspb:g,cttAuthInfo:b}),k.set(b,e),Iq(k,h,d,f)):(k=wq().extractMatchingEntries({isJspb:g,
cttAuthInfo:b}),m.set(b,k),Gq(m,h,d,e,f));else if(g){e=p(Object.keys(vq));for(g=e.next();!g.done;g=e.next())m=g.value,g=wq().extractMatchingEntries({isJspb:!0,cttAuthInfo:m}),0<g.length&&k.set(m,g),delete vq[m];Iq(k,h,d,f)}else{k=p(Object.keys(vq));for(g=k.next();!g.done;g=k.next()){g=g.value;var q=wq().extractMatchingEntries({isJspb:!1,cttAuthInfo:g});0<q.length&&m.set(g,q);delete vq[g]}Gq(m,h,d,e,f)}}else f=a,k=c,h=lq,f=void 0===f?{}:f,k=void 0===k?!1:k,void 0!==b?k?(e=new Map,k=sq.get(b)||[],e.set(b,
k),Iq(e,h,d,f),sq.delete(b)):(k=new Map,m=rq.get(b)||[],k.set(b,m),Gq(k,h,d,e,f),rq.delete(b)):k?(Iq(sq,h,d,f),sq.clear()):(Gq(rq,h,d,e,f),rq.clear());else Eq(c),d()})}
function Eq(a){a=void 0===a?!1:a;if(M("web_gel_timeout_cap")&&(!a&&!nq.i||a&&!oq.i)){var b=Cq(function(){Dq({writeThenSend:!0},void 0,a)},6E4);
a?oq.i=b:nq.i=b}Yk(a?oq.j:nq.j);b=L("LOGGING_BATCH_TIMEOUT",xk("web_gel_debounce_ms",1E4));M("shorten_initial_gel_batch_timeout")&&qq&&(b=jq);b=Cq(function(){Dq({writeThenSend:!0},void 0,a)},b);
a?oq.j=b:nq.j=b}
function Gq(a,b,c,d,e,f){e=void 0===e?{}:e;var g=Math.round(P()),h=a.size,k={};a=p(a);for(var m=a.next();!m.done;k={Ta:k.Ta,sa:k.sa,Ga:k.Ga,Va:k.Va,Ua:k.Ua},m=a.next()){var q=p(m.value);m=q.next().value;q=q.next().value;k.sa=wb({context:Fl(b.config_||El())});if(!Pa(q)&&!M("throw_err_when_logevent_malformed_killswitch")){d();break}k.sa.events=q;(q=tq[m])&&Jq(k.sa,m,q);delete tq[m];k.Ga="visitorOnlyApprovedKey"===m;Kq(k.sa,g,k.Ga);Lq(e);k.Va=function(){h--;h||c()};
k.Ta=0;k.Ua=function(r){return function(){r.Ta++;if(e.bypassNetworkless&&M("log_errors_through_nwl_on_retry")&&1===r.Ta)try{Ul(b,"log_event",r.sa,Mq({writeThenSend:!0},r.Ga,r.Va,r.Ua,f)),qq=!1}catch(w){Dk(w),d()}h--;h||c()}}(k);
try{Ul(b,"log_event",k.sa,Mq(e,k.Ga,k.Va,k.Ua,f)),qq=!1}catch(r){Dk(r),d()}}}
function Iq(a,b,c,d,e){d=void 0===d?{}:d;var f=Math.round(P()),g=a.size,h=new Map([].concat(ia(a)));h=p(h);for(var k=h.next();!k.done;k=h.next()){var m=p(k.value).next().value,q=a.get(m);k=new ik;var r=Kl(b.config_||El());G(k,Ri,1,r);q=q?Nq(q):[];q=p(q);for(r=q.next();!r.done;r=q.next())Wd(k,3,Ij,r.value);(q=uq[m])&&Oq(k,m,q);delete uq[m];m="visitorOnlyApprovedKey"===m;Pq(k,f,m);Lq(d);k=ae(k);m=Mq(d,m,function(){g--;g||c()},function(){g--;
g||c()},e);
m.headers["Content-Type"]="application/json+protobuf";m.postBodyFormat="JSPB";m.postBody=k;Ul(b,"log_event","",m);qq=!1}}
function Lq(a){M("always_send_and_write")&&(a.writeThenSend=!1)}
function Mq(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,lc:a,Ka:b,gr:!!e,headers:{},postBodyFormat:"",postBody:""};Qq()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(P())));return a}
function Kq(a,b,c){Qq()||(a.requestTimeMs=String(b));M("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=L("EVENT_ID"))&&(c=Rq(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Pq(a,b,c){Qq()||D(a,2,b);if(!c&&(b=L("EVENT_ID"))){c=Rq();var d=new Lj;D(d,1,b);D(d,2,c);G(a,Lj,5,d)}}
function Rq(){var a=L("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*kq/2));a++;a>kq&&(a=1);uk("BATCH_CLIENT_COUNTER",a);return a}
function Jq(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Oq(a,b,c){if(Xd(c,1===Pd(c,hk)?1:-1))var d=1;else if(c.getPlaylistId())d=2;else return;G(a,gk,4,c);a=Qd(a,Ri,1)||new Ri;c=Qd(a,Pi,3)||new Pi;var e=new Oi;e.setToken(b);D(e,1,d);Wd(c,12,Oi,e);G(a,Pi,3,c)}
function Nq(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new Ij(a[c]))}catch(d){Dk(new R("Transport failed to deserialize "+String(a[c])))}return b}
function yq(a,b){if(B("yt.logging.transport.enableScrapingForTest")){var c=B("yt.logging.transport.scrapedPayloadsForTesting"),d=B("yt.logging.transport.payloadToScrape","");b&&(b=B("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);a&&a.payload[d]&&c.push((null==a?void 0:a.payload)[d]);A("yt.logging.transport.scrapedPayloadsForTesting",c)}}
function Qq(){return M("use_request_time_ms_header")||M("lr_use_request_time_ms_header")}
function Cq(a,b){return M("transport_use_scheduler")?Wl(a,b):Xk(a,b)}
;var Sq=y.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",Sq);
function Tq(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||P());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;M("enable_unknown_lact_fix_on_html5")&&Sp();a=Vp();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};M("log_sequence_info_on_gel_web")&&d.ba&&(a=e.context,b=d.ba,b={index:Uq(b),groupKey:b},a.sequence=b,d.ac&&delete Sq[d.ba]);(d.uc?Fq:xq)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,Ka:d.Ka},c)}
function Vq(a){Dq(void 0,void 0,void 0===a?!1:a)}
function Uq(a){Sq[a]=a in Sq?Sq[a]+1:0;return Sq[a]}
;var Wq=y.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",Wq);function Xq(a,b,c){c=void 0===c?{}:c;var d=Math.round(c.timestamp||P());D(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=Vp();d=new Hj;D(d,1,c.timestamp||!isFinite(e)?-1:e);if(M("log_sequence_info_on_gel_web")&&c.ba){e=c.ba;var f=Uq(e),g=new Gj;D(g,2,f);D(g,1,e);G(d,Gj,3,g);c.ac&&delete Wq[c.ba]}G(a,Hj,33,d);(c.uc?Hq:Bq)({endpoint:"log_event",payload:a,cttAuthInfo:c.cttAuthInfo,Ka:c.Ka},b)}
;function Yq(a,b){b=void 0===b?{}:b;var c=!1;L("ytLoggingEventsDefaultDisabled",!1)&&(c=!0);Xq(a,c?null:Ep,b)}
;function Zq(a,b){var c=new Ij;Ud(c,xj,72,Jj,a);Yq(c,b)}
function $q(a,b,c){var d=new Ij;Ud(d,wj,73,Jj,a);c?Xq(d,c,b):Yq(d,b)}
function ar(a,b,c){var d=new Ij;Ud(d,vj,78,Jj,a);c?Xq(d,c,b):Yq(d,b)}
function br(a,b,c){var d=new Ij;Ud(d,yj,208,Jj,a);c?Xq(d,c,b):Yq(d,b)}
function cr(a,b,c){var d=new Ij;Ud(d,oj,156,Jj,a);c?Xq(d,c,b):Yq(d,b)}
function dr(a,b,c){var d=new Ij;Ud(d,sj,215,Jj,a);c?Xq(d,c,b):Yq(d,b)}
function er(a,b,c){var d=new Ij;Ud(d,nj,111,Jj,a);c?Xq(d,c,b):Yq(d,b)}
;function lm(a,b,c){c=void 0===c?{}:c;if(M("migrate_events_to_ts")){c=void 0===c?{}:c;var d=Ep;L("ytLoggingEventsDefaultDisabled",!1)&&Ep===Ep&&(d=null);M("web_all_payloads_via_jspb")&&Ek(new R("Logs should be translated to JSPB but are sent as JSON instead",a));Tq(a,b,d,c)}else d=Ep,L("ytLoggingEventsDefaultDisabled",!1)&&Ep==Ep&&(d=null),Tq(a,b,d,c)}
;var fr=[{Db:function(a){return"Cannot read property '"+a.key+"'"},
ib:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Db:function(a){return"Cannot call '"+a.key+"'"},
ib:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Db:function(a){return a.key+" is not defined"},
ib:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var hr={oa:[],na:[{callback:gr,weight:500}]};function gr(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function ir(){this.na=[];this.oa=[]}
var jr;function kr(){if(!jr){var a=jr=new ir;a.oa.length=0;a.na.length=0;hr.oa&&a.oa.push.apply(a.oa,hr.oa);hr.na&&a.na.push.apply(a.na,hr.na)}return jr}
;var lr=new K;function mr(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=nr(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=nr(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=nr(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function nr(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function or(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=pr(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=mr(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?pr(e+".ve",f,g,h):0;d+=g;d+=pr(e,a[e],b,c);if(500<d)break}}else c[b]=qr(a),d+=c[b].length;else c[b]=qr(a),d+=c[b].length;return d}
function pr(a,b,c,d){c+="."+a;a=qr(b);d[c]=a;return c.length+a.length}
function qr(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;var rr=new Set,sr=0,tr=0,ur=0,vr=[],wr=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function km(a){xr(a)}
function yr(a){xr(a,"WARNING")}
function xr(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||L("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||L("INNERTUBE_CONTEXT_CLIENT_VERSION");var g=f||{},h=void 0===b?"ERROR":b;h=void 0===h?"ERROR":h;if(a){a.hasOwnProperty("level")&&a.level&&(h=a.level);if(M("console_log_js_exceptions")){var k=[];k.push("Name: "+a.name);k.push("Message: "+a.message);a.hasOwnProperty("params")&&k.push("Error Params: "+JSON.stringify(a.params));a.hasOwnProperty("args")&&k.push("Error args: "+JSON.stringify(a.args));
k.push("File name: "+a.fileName);k.push("Stacktrace: "+a.stack);window.console.log(k.join("\n"),a)}if(!(5<=sr)){var m=vr,q=ne(a),r=q.message||"Unknown Error",w=q.name||"UnknownError",t=q.stack||a.j||"Not available";if(t.startsWith(w+": "+r)){var z=t.split("\n");z.shift();t=z.join("\n")}var E=q.lineNumber||"Not available",F=q.fileName||"Not available",O=t,N=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var Q=0;Q<a.args.length&&!(N=or(a.args[Q],"params."+Q,g,N),500<=N);Q++);else if(a.hasOwnProperty("params")&&
a.params){var da=a.params;if("object"===typeof a.params)for(var U in da){if(da[U]){var mb="params."+U,Wa=qr(da[U]);g[mb]=Wa;N+=mb.length+Wa.length;if(500<N)break}}else g.params=qr(da)}if(m.length)for(var ma=0;ma<m.length&&!(N=or(m[ma],"params.context."+ma,g,N),500<=N);ma++);navigator.vendor&&!g.hasOwnProperty("vendor")&&(g["device.vendor"]=navigator.vendor);var H={message:r,name:w,lineNumber:E,fileName:F,stack:O,params:g,sampleWeight:1},la=Number(a.columnNumber);isNaN(la)||(H.lineNumber=H.lineNumber+
":"+la);if("IGNORED"===a.level)var fa=0;else a:{for(var ue=kr(),ve=p(ue.oa),pd=ve.next();!pd.done;pd=ve.next()){var oa=pd.value;if(H.message&&H.message.match(oa.sr)){fa=oa.weight;break a}}for(var So=p(ue.na),Mj=So.next();!Mj.done;Mj=So.next()){var To=Mj.value;if(To.callback(H)){fa=To.weight;break a}}fa=1}H.sampleWeight=fa;for(var Uo=p(fr),Nj=Uo.next();!Nj.done;Nj=Uo.next()){var Oj=Nj.value;if(Oj.ib[H.name])for(var Vo=p(Oj.ib[H.name]),Pj=Vo.next();!Pj.done;Pj=Vo.next()){var Wo=Pj.value,Ig=H.message.match(Wo.regexp);
if(Ig){H.params["params.error.original"]=Ig[0];for(var Qj=Wo.groups,Xo={},qd=0;qd<Qj.length;qd++)Xo[Qj[qd]]=Ig[qd+1],H.params["params.error."+Qj[qd]]=Ig[qd+1];H.message=Oj.Db(Xo);break}}}H.params||(H.params={});var Yo=kr();H.params["params.errorServiceSignature"]="msg="+Yo.oa.length+"&cb="+Yo.na.length;H.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(H.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));Db("sample").constructor!==
Bb&&(H.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(H);if(0!==H.sampleWeight&&!rr.has(H.message)){if("ERROR"===h){lr.ta("handleError",H);if(M("record_app_crashed_web")&&0===ur&&1===H.sampleWeight)if(ur++,M("errors_via_jspb")){var Rj=new kj;D(Rj,1,1);if(!M("report_client_error_with_app_crash_ks")){var Zo=new fj;D(Zo,1,H.message);var $o=new gj;G($o,fj,3,Zo);var ap=new hj;G(ap,gj,5,$o);var bp=new ij;G(bp,hj,9,ap);G(Rj,ij,4,bp)}var cp=new Ij;Ud(cp,kj,20,
Jj,Rj);Yq(cp)}else{var dp={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};M("report_client_error_with_app_crash_ks")||(dp.systemHealth={crashData:{clientError:{logMessage:{message:H.message}}}});lm("appCrashed",dp)}tr++}else"WARNING"===h&&lr.ta("handleWarning",H);if(M("kevlar_gel_error_routing"))a:{var we=h;if(M("errors_via_jspb")){if(zr())var fp=void 0;else{var rd=new cj;D(rd,1,H.stack);H.fileName&&D(rd,4,H.fileName);var Eb=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Eb.length&&(1!==
Eb.length||isNaN(Number(Eb[0]))?2!==Eb.length||isNaN(Number(Eb[0]))||isNaN(Number(Eb[1]))||(D(rd,2,Number(Eb[0])),D(rd,3,Number(Eb[1]))):D(rd,2,Number(Eb[0])));var xc=new fj;D(xc,1,H.message);D(xc,3,H.name);D(xc,6,H.sampleWeight);"ERROR"===we?D(xc,2,2):"WARNING"===we?D(xc,2,1):D(xc,2,0);var Sj=new dj;D(Sj,1,!0);Ud(Sj,cj,3,ej,rd);var Zb=new $i;D(Zb,3,window.location.href);for(var gp=L("FEXP_EXPERIMENTS",[]),Tj=0;Tj<gp.length;Tj++){var vv=gp[Tj];Dd(Zb);Nd(Zb,5,2,!1).push(vv)}var Uj=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");
if(!vk()&&Uj)for(var hp=p(Object.keys(Uj)),yc=hp.next();!yc.done;yc=hp.next()){var ip=yc.value,Vj=new bj;D(Vj,1,ip);Vj.setValue(String(Uj[ip]));Wd(Zb,4,bj,Vj)}var Wj=H.params;if(Wj){var jp=p(Object.keys(Wj));for(yc=jp.next();!yc.done;yc=jp.next()){var kp=yc.value,Xj=new bj;D(Xj,1,"client."+kp);Xj.setValue(String(Wj[kp]));Wd(Zb,4,bj,Xj)}}var lp=L("SERVER_NAME"),mp=L("SERVER_VERSION");if(lp&&mp){var Yj=new bj;D(Yj,1,"server.name");Yj.setValue(lp);Wd(Zb,4,bj,Yj);var Zj=new bj;D(Zj,1,"server.version");
Zj.setValue(mp);Wd(Zb,4,bj,Zj)}var Jg=new gj;G(Jg,$i,1,Zb);G(Jg,dj,2,Sj);G(Jg,fj,3,xc);fp=Jg}var np=fp;if(!np)break a;var op=new Ij;Ud(op,gj,163,Jj,np);Yq(op)}else{if(zr())var pp=void 0;else{var xe={stackTrace:H.stack};H.fileName&&(xe.filename=H.fileName);var Fb=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Fb.length&&(1!==Fb.length||isNaN(Number(Fb[0]))?2!==Fb.length||isNaN(Number(Fb[0]))||isNaN(Number(Fb[1]))||(xe.lineNumber=Number(Fb[0]),xe.columnNumber=Number(Fb[1])):xe.lineNumber=
Number(Fb[0]));var ak={level:"ERROR_LEVEL_UNKNOWN",message:H.message,errorClassName:H.name,sampleWeight:H.sampleWeight};"ERROR"===we?ak.level="ERROR_LEVEL_ERROR":"WARNING"===we&&(ak.level="ERROR_LEVEL_WARNNING");var wv={isObfuscated:!0,browserStackInfo:xe},sd={pageUrl:window.location.href,kvPairs:[]};L("FEXP_EXPERIMENTS")&&(sd.experimentIds=L("FEXP_EXPERIMENTS"));var bk=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!vk()&&bk)for(var qp=p(Object.keys(bk)),zc=qp.next();!zc.done;zc=qp.next()){var rp=
zc.value;sd.kvPairs.push({key:rp,value:String(bk[rp])})}var ck=H.params;if(ck){var sp=p(Object.keys(ck));for(zc=sp.next();!zc.done;zc=sp.next()){var tp=zc.value;sd.kvPairs.push({key:"client."+tp,value:String(ck[tp])})}}var up=L("SERVER_NAME"),vp=L("SERVER_VERSION");up&&vp&&(sd.kvPairs.push({key:"server.name",value:up}),sd.kvPairs.push({key:"server.version",value:vp}));pp={errorMetadata:sd,stackTrace:wv,logMessage:ak}}var wp=pp;if(!wp)break a;lm("clientError",wp)}if("ERROR"===we||M("errors_flush_gel_always_killswitch"))b:if(M("migrate_events_to_ts"))c:{if(M("web_fp_via_jspb")&&
(Vq(!0),!M("web_fp_via_jspb_and_json")))break c;Vq()}else{if(M("web_fp_via_jspb")&&(Vq(!0),!M("web_fp_via_jspb_and_json")))break b;Vq()}}if(!M("suppress_error_204_logging")){var ye=H.params||{},$b={urlParams:{a:"logerror",t:"jserror",type:H.name,msg:H.message.substr(0,250),line:H.lineNumber,level:h,"client.name":ye.name},postParams:{url:L("PAGE_NAME",window.location.href),file:H.fileName},method:"POST"};ye.version&&($b["client.version"]=ye.version);if($b.postParams){H.stack&&($b.postParams.stack=
H.stack);for(var xp=p(Object.keys(ye)),dk=xp.next();!dk.done;dk=xp.next()){var yp=dk.value;$b.postParams["client."+yp]=ye[yp]}var ek=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(ek)for(var zp=p(Object.keys(ek)),fk=zp.next();!fk.done;fk=zp.next()){var Ap=fk.value;$b.postParams[Ap]=ek[Ap]}var Bp=L("SERVER_NAME"),Cp=L("SERVER_VERSION");Bp&&Cp&&($b.postParams["server.name"]=Bp,$b.postParams["server.version"]=Cp)}dl(L("ECATCHER_REPORT_HOST","")+"/error_204",$b)}try{rr.add(H.message)}catch($w){}sr++}}}}
function zr(){for(var a=p(wr),b=a.next();!b.done;b=a.next())if(cm(b.value.toLowerCase()))return!0;return!1}
function Ar(a){var b=Ja.apply(1,arguments);a.args||(a.args=[]);a.args.push.apply(a.args,ia(b))}
;function Br(){this.register=new Map}
function Cr(a){a=p(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.xr("ABORTED")}
Br.prototype.clear=function(){Cr(this);this.register.clear()};
var Dr=new Br;var Er=Date.now().toString();
function Fr(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Er)for(a=1,b=0;b<Er.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Er.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Gr=y.ytLoggingDocDocumentNonce_;Gr||(Gr=Fr(),A("ytLoggingDocDocumentNonce_",Gr));var Hr=Gr;var Ir={ai:0,ue:1,Fe:2,Xl:3,ci:4,uq:5,Nm:6,Ao:7,Sn:8,oo:9,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS",9:"RICH_GRID_WATCH"};function Jr(a){this.G=a}
function Kr(a){return new Jr({trackingParams:a})}
Jr.prototype.getAsJson=function(){var a={};void 0!==this.G.trackingParams?a.trackingParams=this.G.trackingParams:(a.veType=this.G.veType,void 0!==this.G.veCounter&&(a.veCounter=this.G.veCounter),void 0!==this.G.elementIndex&&(a.elementIndex=this.G.elementIndex));void 0!==this.G.dataElement&&(a.dataElement=this.G.dataElement.getAsJson());void 0!==this.G.youtubeData&&(a.youtubeData=this.G.youtubeData);return a};
Jr.prototype.getAsJspb=function(){var a=new mj;if(void 0!==this.G.trackingParams){var b=this.G.trackingParams;if(null!=b)if("string"===typeof b)b=b?new id(b,gd):jd();else if(b.constructor!==id)if(fd(b))b=b.length?new id(new Uint8Array(b),gd):jd();else throw Error();D(a,1,b)}else void 0!==this.G.veType&&D(a,2,this.G.veType),void 0!==this.G.veCounter&&D(a,6,this.G.veCounter),void 0!==this.G.elementIndex&&D(a,3,this.G.elementIndex);void 0!==this.G.dataElement&&(b=this.G.dataElement.getAsJspb(),G(a,mj,
7,b));void 0!==this.G.youtubeData&&G(a,Di,8,this.G.jspbYoutubeData);return a};
Jr.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
Jr.prototype.isClientVe=function(){return!this.G.trackingParams&&!!this.G.veType};function Lr(a){a=void 0===a?0:a;return 0===a?"client-screen-nonce":"client-screen-nonce."+a}
function Mr(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Nr(a){return L(Mr(void 0===a?0:a))}
A("yt_logging_screen.getRootVeType",Nr);function Or(a){return(a=Nr(void 0===a?0:a))?new Jr({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null}
function Pr(){var a=L("csn-to-ctt-auth-info");a||(a={},uk("csn-to-ctt-auth-info",a));return a}
function Qr(a){a=L(Lr(void 0===a?0:a));if(!a&&!L("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
A("yt_logging_screen.getCurrentCsn",Qr);function Rr(a,b,c){var d=Pr();(c=Qr(c))&&delete d[c];b&&(d[a]=b)}
function Sr(a){return Pr()[a]}
A("yt_logging_screen.getCttAuthInfo",Sr);
function Tr(a,b,c,d){c=void 0===c?0:c;if(a!==L(Lr(c))||b!==L(Mr(c)))if(Rr(a,d,c),uk(Lr(c),a),uk(Mr(c),b),b=function(){setTimeout(function(){if(a)if(M("web_time_via_jspb")){var e=new nj;D(e,1,Hr);D(e,2,a);M("use_default_heartbeat_client")?er(e):er(e,void 0,Ep)}else e={clientDocumentNonce:Hr,clientScreenNonce:a},M("use_default_heartbeat_client")?lm("foregroundHeartbeatScreenAssociated",e):Tq("foregroundHeartbeatScreenAssociated",e,Ep)},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()}
A("yt_logging_screen.setCurrentScreen",Tr);var Ur=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};A("yt.msgs_",Ur);function Vr(a){pk(Ur,arguments)}
;var Wr={te:3611,Ed:27686,Fd:85013,Gd:23462,Id:157557,Jd:42016,Kd:62407,Ld:26926,Hd:43781,Md:51236,Nd:79148,Od:50160,Pd:77504,be:153587,ce:87907,de:18630,ee:54445,ge:80935,he:152172,ie:105675,je:150723,ke:37521,le:147285,me:47786,ne:98349,oe:123695,pe:6827,qe:29434,re:7282,se:124448,xe:32276,we:76278,ye:147868,ze:147869,Ae:93911,Be:106531,Ce:27259,De:27262,Ee:27263,Ge:21759,He:27107,Ie:62936,Je:160866,Ke:49568,Le:160789,Me:38408,Ne:80637,Oe:68727,Pe:68728,Qe:80353,Re:80356,Se:74610,Te:45707,Ue:83962,
Ve:83970,We:46713,Xe:89711,Ye:74612,Ze:155792,af:93265,bf:74611,cf:131380,ef:128979,ff:139311,gf:128978,df:131391,hf:105350,kf:139312,lf:134800,jf:131392,nf:113533,pf:93252,qf:99357,sf:94521,tf:114252,uf:113532,vf:94522,rf:94583,wf:88E3,xf:139580,yf:93253,zf:93254,Af:94387,Bf:94388,Cf:93255,Df:97424,mf:72502,Ef:110111,Ff:76019,Hf:117092,If:117093,Gf:89431,Jf:110466,Kf:77240,Lf:60508,Mf:148123,Nf:148124,Of:137401,Pf:137402,Qf:137046,Rf:73393,Sf:113534,Tf:92098,Uf:131381,Vf:84517,Wf:83759,Xf:162711,
Yf:162712,Zf:80357,ag:86113,cg:72598,dg:72733,eg:107349,fg:124275,gg:118203,hg:133275,ig:160157,jg:152569,kg:156651,lg:133274,mg:160159,ng:160158,og:133272,pg:133273,qg:133276,rg:144507,sg:143247,tg:156652,ug:143248,vg:143249,wg:143250,xg:143251,yg:156653,zg:144401,Bg:117431,Ag:133797,Cg:153964,Dg:128572,Eg:133405,Fg:117429,Gg:117430,Hg:117432,Ig:120080,Jg:117259,Kg:156655,Lg:156654,Mg:121692,Ng:145656,Og:156656,Pg:145655,Qg:145653,Rg:145654,Sg:145657,Tg:132972,Ug:133051,Vg:133658,Wg:132971,Xg:97615,
Zg:143359,Yg:143356,bh:143361,ah:143358,eh:143360,dh:143357,fh:142303,gh:143353,hh:143354,ih:144479,jh:143355,kh:31402,mh:133624,nh:146477,oh:133623,ph:133622,lh:133621,qh:84774,sh:160801,rh:95117,th:150497,uh:98930,vh:98931,wh:98932,xh:153320,yh:153321,zh:43347,Ah:129889,Bh:149123,Ch:45474,Dh:100352,Eh:84758,Fh:98443,Gh:117985,Hh:74613,Ih:155911,Jh:74614,Kh:64502,Lh:136032,Mh:74615,Nh:74616,Oh:122224,Ph:74617,Qh:77820,Rh:74618,Sh:93278,Th:93274,Uh:93275,Vh:93276,Wh:22110,Xh:29433,Yh:133798,Zh:132295,
bi:120541,di:82047,fi:113550,gi:75836,hi:75837,ii:42352,ji:84512,ki:76065,li:75989,si:51879,ti:16623,vi:32594,wi:27240,xi:32633,yi:74858,zi:156999,Bi:3945,Ai:16989,Ci:45520,Di:25488,Ei:25492,Fi:25494,Gi:55760,Hi:14057,Ii:18451,Ji:57204,Ki:57203,Li:17897,Mi:57205,Ni:18198,Oi:17898,Pi:17909,Qi:43980,Ri:46220,Si:11721,Ti:147994,Ui:49954,Vi:96369,Wi:3854,Xi:151633,Yi:56251,Zi:159108,aj:25624,bj:152036,sj:16906,tj:99999,uj:68172,vj:27068,wj:47973,xj:72773,yj:26970,zj:26971,Aj:96805,Bj:17752,Cj:73233,Dj:109512,
Ej:22256,Fj:14115,Gj:22696,Hj:89278,Ij:89277,Jj:109513,Kj:43278,Lj:43459,Mj:43464,Nj:89279,Oj:43717,Pj:55764,Qj:22255,Rj:147912,Sj:89281,Tj:40963,Uj:43277,Vj:43442,Wj:91824,Xj:120137,Yj:96367,Zj:36850,ak:72694,bk:37414,ck:36851,ek:124863,dk:121343,fk:73491,gk:54473,hk:43375,ik:46674,jk:143815,kk:139095,lk:144402,mk:149968,nk:149969,pk:32473,qk:72901,rk:72906,sk:50947,tk:50612,uk:50613,vk:50942,wk:84938,xk:84943,yk:84939,zk:84941,Ak:84944,Bk:84940,Ck:84942,Dk:35585,Ek:51926,Fk:79983,Gk:63238,Hk:18921,
Ik:63241,Jk:57893,Kk:41182,Lk:135732,Mk:33424,Nk:22207,Ok:42993,Pk:36229,Qk:22206,Rk:22205,Sk:18993,Tk:19001,Uk:18990,Vk:18991,Wk:18997,Xk:18725,Yk:19003,Zk:36874,al:44763,bl:33427,dl:67793,fl:22182,il:37091,jl:34650,kl:50617,ll:47261,ml:22287,nl:25144,ol:97917,pl:62397,ql:150871,rl:150874,sl:125598,ul:137935,vl:36961,wl:108035,xl:27426,yl:27857,zl:27846,Al:27854,Bl:69692,Cl:61411,Dl:39299,El:38696,Fl:62520,Gl:36382,Hl:108701,Il:50663,Jl:36387,Kl:14908,Ll:37533,Ml:105443,Nl:61635,Ol:62274,Pl:161670,
Ql:133818,Rl:65702,Sl:65703,Tl:65701,Ul:76256,Vl:37671,Wl:49953,Yl:36216,Zl:28237,am:39553,bm:29222,cm:26107,dm:38050,em:26108,gm:120745,fm:26109,hm:26110,im:66881,jm:28236,km:14586,lm:160598,mm:57929,nm:74723,om:44098,pm:44099,sm:23528,tm:61699,qm:134104,rm:134103,um:59149,vm:101951,wm:97346,xm:118051,ym:95102,zm:64882,Am:119505,Bm:63595,Cm:63349,Dm:95101,Em:75240,Fm:27039,Gm:68823,Hm:21537,Im:83464,Jm:75707,Km:83113,Lm:101952,Mm:101953,Om:79610,Pm:125755,Qm:24402,Rm:24400,Sm:32925,Um:57173,Tm:156421,
Vm:122502,Wm:145268,Xm:138480,Ym:64423,Zm:64424,an:33986,bn:100828,cn:129089,dn:21409,hn:135155,jn:135156,kn:135157,ln:135158,mn:158225,nn:135159,pn:135160,qn:135161,sn:135162,tn:135163,rn:158226,un:158227,vn:135164,wn:135165,xn:135166,en:11070,fn:11074,gn:17880,yn:14001,An:30709,Bn:30707,Cn:30711,Dn:30710,En:30708,zn:26984,Fn:146143,Gn:63648,Hn:63649,In:111059,Jn:5754,Kn:20445,Ln:151308,Mn:151152,On:130975,Nn:130976,Pn:110386,Qn:113746,Rn:66557,Tn:17310,Un:28631,Vn:21589,Wn:154946,Xn:68012,Yn:162617,
Zn:60480,ao:138664,bo:141121,co:31571,eo:141978,fo:150105,ho:150106,jo:150107,ko:150108,lo:76980,mo:41577,no:45469,po:38669,qo:13768,ro:13777,so:141842,to:62985,uo:4724,vo:59369,wo:43927,xo:43928,yo:12924,zo:100355,Co:56219,Do:27669,Eo:10337,Bo:47896,Fo:122629,Ho:139723,Go:139722,Io:121258,Jo:107598,Ko:127991,Lo:96639,Mo:107536,No:130169,Oo:96661,Po:145188,Qo:96658,Ro:116646,So:159428,To:121122,Uo:96660,Vo:127738,Wo:127083,Xo:155281,Yo:162959,Zo:147842,ap:104443,bp:96659,cp:147595,ep:106442,fp:162776,
gp:134840,hp:63667,ip:63668,jp:63669,kp:130686,lp:147036,mp:78314,np:147799,qp:148649,rp:55761,sp:127098,tp:134841,up:96368,vp:67374,wp:48992,xp:146176,yp:49956,zp:31961,Ap:26388,Bp:23811,Cp:5E4,Dp:126250,Ep:96370,Fp:47355,Gp:47356,Hp:37935,Ip:45521,Jp:21760,Kp:83769,Lp:49977,Mp:49974,Np:93497,Op:93498,Pp:34325,Qp:140759,Rp:115803,Sp:123707,Tp:100081,Up:35309,Vp:68314,Wp:25602,Xp:100339,Yp:143516,Zp:59018,aq:18248,bq:50625,cq:9729,fq:37168,gq:37169,hq:21667,iq:16749,jq:18635,kq:39305,lq:18046,mq:53969,
nq:8213,oq:93926,pq:102852,qq:110099,rq:22678,sq:69076,tq:137575,wq:139224,xq:100856,yq:154430,zq:17736,Aq:3832,Bq:147111,Cq:55759,Dq:64031,Jq:93044,Kq:93045,Lq:34388,Mq:17657,Nq:17655,Oq:39579,Pq:39578,Qq:77448,Rq:8196,Sq:11357,Tq:69877,Uq:8197,Vq:156512,Wq:161613,Xq:156509,Yq:161612,Zq:161614,br:82039};function Xr(){var a=vb(Yr),b;return(new rf(function(c,d){a.onSuccess=function(e){Wk(e)?c(new Zr(e)):d(new $r("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new $r("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new $r("Request timed out","net.timeout",e))};
b=dl("//googleads.g.doubleclick.net/pagead/id",a)})).ob(function(c){c instanceof yf&&b.abort();
return wf(c)})}
function $r(a,b,c){ab.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
u($r,ab);function Zr(a){this.xhr=a}
;function as(){this.i=0;this.ka=null}
as.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.ka))&&"function"===typeof a.then?a:bs(a):2===this.i&&b?(a=b.call(c,this.ka))&&"function"===typeof a.then?a:cs(a):this};
as.prototype.getValue=function(){return this.ka};
as.prototype.$goog_Thenable=!0;function cs(a){var b=new as;a=void 0===a?null:a;b.i=2;b.ka=void 0===a?null:a;return b}
function bs(a){var b=new as;a=void 0===a?null:a;b.i=1;b.ka=void 0===a?null:a;return b}
;function ds(a,b){if(a)return a[b.name]}
;function es(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:Rk(a)?"same-origin":"cors",credentials:Rk(a)?"same-origin":"include"};b={};for(var d=p(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function fs(){return lg()||bm&&cm("applewebkit")&&!cm("version")&&(!cm("safari")||cm("gsa/"))||Oc&&cm("version/")?!0:L("EOM_VISITOR_DATA")?!1:!0}
;function gs(a){a:{var b=a.raw_embedded_player_response;if(!b&&(a=a.embedded_player_response))try{b=JSON.parse(a)}catch(d){b="EMBEDDED_PLAYER_MODE_UNKNOWN";break a}if(b)b:{for(var c in Xi)if(Xi[c]==b.embeddedPlayerMode){b=Xi[c];break b}b="EMBEDDED_PLAYER_MODE_UNKNOWN"}else b="EMBEDDED_PLAYER_MODE_UNKNOWN"}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function hs(a){ab.call(this,a.message||a.description||a.name);this.isMissing=a instanceof is;this.isTimeout=a instanceof $r&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof yf}
u(hs,ab);hs.prototype.name="BiscottiError";function is(){ab.call(this,"Biscotti ID is missing from server")}
u(is,ab);is.prototype.name="BiscottiMissingError";var Yr={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},js=null;function ks(){if(M("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!fs())return Error("User has not consented - not fetching biscotti id.");var a=L("PLAYER_VARS",{});if("1"==tb(a))return Error("Biscotti ID is not available in private embed mode");if(gs(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Gk(){var a=ks();if(void 0!==a)return wf(a);js||(js=Xr().then(ls).ob(function(b){return ms(2,b)}));
return js}
function ls(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new is;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new is;a=a.id;Hk(a);js=bs(a);ns(18E5,2);return a}
function ms(a,b){b=new hs(b);Hk("");js=cs(b);0<a&&ns(12E4,a-1);throw b;}
function ns(a,b){Xk(function(){Xr().then(ls,function(c){return ms(b,c)}).ob(cb)},a)}
function os(){try{var a=B("yt.ads.biscotti.getId_");return a?a():Gk()}catch(b){return wf(b)}}
;function ps(a){if("1"!=tb(L("PLAYER_VARS",{}))){a&&Fk();try{os().then(function(){},function(){}),Xk(ps,18E5)}catch(b){Dk(b)}}}
;function qs(){this.wd=!0}
function rs(a){var b={},c=ng([]);c&&(b.Authorization=c,c=a=null==a?void 0:a.sessionIndex,void 0===c&&(c=Number(L("SESSION_INDEX",0)),c=isNaN(c)?0:c),M("voice_search_auth_header_removal")||(b["X-Goog-AuthUser"]=c),"INNERTUBE_HOST_OVERRIDE"in tk||(b["X-Origin"]=window.location.origin),void 0===a&&"DELEGATED_SESSION_ID"in tk&&(b["X-Goog-PageId"]=L("DELEGATED_SESSION_ID")));return b}
;var ss={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};var ts=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function us(){var a=void 0===a?window.location.href:a;if(M("kevlar_disable_theme_param"))return null;mc(nc(5,a));try{var b=Pk(a).theme;return ts.get(b)||null}catch(c){}return null}
;function vs(){this.i={};if(this.j=pl()){var a=jg.get("CONSISTENCY",void 0);a&&ws(this,{encryptedTokenJarContents:a})}}
vs.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.ha.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=p(b);for(c=e.next();!c.done;c=e.next())delete this.i[c.value.encryptedTokenJarContents];ws(this,a)}};
function ws(a,b){if(b.encryptedTokenJarContents&&(a.i[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.i[b.encryptedTokenJarContents]},1E3*c);
a.j&&nl("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var xs=window.location.hostname.split(".").slice(-2).join(".");function ys(){var a=L("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===L("INNERTUBE_CLIENT_NAME")&&(this.i=zs(this))&&(a=this.i.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.j=void 0)}
var As;ys.getInstance=function(){As=B("yt.clientLocationService.instance");As||(As=new ys,A("yt.clientLocationService.instance",As));return As};
l=ys.prototype;l.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.j?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.j.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.j.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.j.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
l.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.j=void 0,"TVHTML5"===L("INNERTUBE_CLIENT_NAME")?(this.i=zs(this))&&this.i.set("yt-location-playability-token",a,15552E3):nl("YT_CL",JSON.stringify({loctok:a}),15552E3,xs,!0))};
function zs(a){return void 0===a.i?new Nl("yt-client-location"):a.i}
l.clearLocationPlayabilityToken=function(a){"TVHTML5"===a?(this.i=zs(this))&&this.i.remove("yt-location-playability-token"):ol("YT_CL")};
l.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===L("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.j=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
l.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function Bs(a,b){var c,d=null==(c=ds(a,Wi))?void 0:c.signal;if(d&&b.Pa&&(c=b.Pa[d]))return c();var e;if((c=null==(e=ds(a,Ui))?void 0:e.request)&&b.Nc&&(e=b.Nc[c]))return e();for(var f in a)if(b.Wb[f]&&(a=b.Wb[f]))return a()}
;var Cs=Symbol("injectionDeps");function Ds(a){this.name=a}
Ds.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Es(){this.key=Fs}
function Gs(){this.providers=new Map;this.i=new Map}
Gs.prototype.resolve=function(a){return a instanceof Es?Hs(this,a.key,[],!0):Hs(this,a,[])};
function Hs(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.providers.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.providers.get(b);c.push(b);if(d.Ac)var e=d.Ac;else if(d.Dd)e=d[Cs]?Is(a,d[Cs],c):[],e=d.Dd.apply(d,ia(e));else if(d.zc){e=d.zc;var f=e[Cs]?Is(a,e[Cs],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ia(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Cr||a.i.set(b,e);
return e}
function Is(a,b,c){return b?b.map(function(d){return d instanceof Es?Hs(a,d.key,c,!0):Hs(a,d,c)}):[]}
;var Js;function Ks(){Js||(Js=new Gs);return Js}
;function Ls(a){return function(){return new a}}
;var Ms={},Ns=(Ms.WEB_UNPLUGGED="^unplugged/",Ms.WEB_UNPLUGGED_ONBOARDING="^unplugged/",Ms.WEB_UNPLUGGED_OPS="^unplugged/",Ms.WEB_UNPLUGGED_PUBLIC="^unplugged/",Ms.WEB_CREATOR="^creator/",Ms.WEB_KIDS="^kids/",Ms.WEB_EXPERIMENTS="^experiments/",Ms.WEB_MUSIC="^music/",Ms.WEB_REMIX="^music/",Ms.WEB_MUSIC_EMBEDDED_PLAYER="^music/",Ms.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",Ms);
function Os(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=Ns[b];if(c){var d=new RegExp(c),e=p(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(Ns).forEach(function(g){var h=p(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=p(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function Ps(){}
Ps.prototype.o=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?ss:c;var d=a.clickTrackingParams,e=this.m,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=L("INNERTUBE_CONTEXT");if(g){g=wb(g);M("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=L("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;rl.getInstance();var m="USER_INTERFACE_THEME_LIGHT";ul(165)?m="USER_INTERFACE_THEME_DARK":ul(174)?m="USER_INTERFACE_THEME_LIGHT":!M("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(m="USER_INTERFACE_THEME_DARK");k=k?m:us()||m;h.userInterfaceTheme=k;if(!f){if(k=
Bl())h.connectionType=k;M("web_log_effective_connection_type")&&(k=Cl())&&(g.client.effectiveConnectionType=k)}var q;if(M("web_log_memory_total_kbytes")&&(null==(q=y.navigator)?0:q.deviceMemory)){var r;q=null==(r=y.navigator)?void 0:r.deviceMemory;g.client.memoryTotalKbytes=""+1E6*q}r=Pk(y.location.href);!M("web_populate_internal_geo_killswitch")&&r.internalcountrycode&&(h.internalGeo=r.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:y.location.href},M("kevlar_woffle")&&
ll.i&&(r=ll.i,h.mainAppWebInfo.pwaInstallabilityStatus=!r.i&&r.j?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=ml(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):"TVHTML5"===h.clientName&&(!M("web_lr_app_quality_killswitch")&&(r=L("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:r})),r=L("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||
{},{certificationScope:r}));if(!M("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var w=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(mb){}w=void 0}w&&(h.timeZone=w)}(w=yk())?h.experimentsToken=w:delete h.experimentsToken;w=zk();vs.i||(vs.i=new vs);h=vs.i.i;r=[];q=0;for(var t in h)r[q++]=h[t];g.request=Object.assign({},g.request,{internalExperimentFlags:w,consistencyTokenJars:r});!M("web_prequest_context_killswitch")&&(t=L("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&
(g.request.externalPrequestContext=t);w=rl.getInstance();t=ul(58);w=w.get("gsml","");g.user=Object.assign({},g.user);t&&(g.user.enableSafetyMode=t);w&&(g.user.lockedSafetyMode=!0);M("warm_op_csn_cleanup")?e&&(f=Qr())&&(g.clientScreenNonce=f):!f&&(f=Qr())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=B("yt.mdx.remote.remoteClient_"))g.remoteClient=d;ys.getInstance().setLocationOnInnerTubeContext(g);try{var z=Sk(),E=z.bid;delete z.bid;g.adSignalsInfo={params:[],bid:E};var F=
p(Object.entries(z));for(var O=F.next();!O.done;O=F.next()){var N=p(O.value),Q=N.next().value,da=N.next().value;z=Q;E=da;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:z,value:""+E})}}catch(mb){xr(mb)}F=g}else xr(Error("Error: No InnerTubeContext shell provided in ytconfig.")),F={};F={context:F};if(O=this.i(a)){this.j(F,O,b);var U;b="/youtubei/v1/"+Os(this.l());(O=null==(U=ds(a.commandMetadata,Vi))?void 0:U.apiUrl)&&(b=O);U=b;(b=L("INNERTUBE_HOST_OVERRIDE"))&&(U=String(b)+String(pc(U)));b=
{};b.key=L("INNERTUBE_API_KEY");M("json_condensed_response")&&(b.prettyPrint="false");U=Qk(U,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:U,za:es(U),ha:F,config:a};a.config.Ya?a.config.Ya.identity=c:a.config.Ya={identity:c};return a}xr(new R("Error: Failed to create Request from Command.",a))};
ea.Object.defineProperties(Ps.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!1}}});function Qs(){}
u(Qs,Ps);Qs.prototype.o=function(){return{input:"/getDatasyncIdsEndpoint",za:es("/getDatasyncIdsEndpoint","GET"),ha:{}}};
Qs.prototype.l=function(){return[]};
Qs.prototype.i=function(){};
Qs.prototype.j=function(){};var Rs={},Ss=(Rs.GET_DATASYNC_IDS=Ls(Qs),Rs);function Ts(a){var b=Ja.apply(1,arguments);if(!Us(a)||b.some(function(d){return!Us(d)}))throw Error("Only objects may be merged.");
b=p(b);for(var c=b.next();!c.done;c=b.next())Vs(a,c.value);return a}
function Vs(a,b){for(var c in b)if(Us(b[c])){if(c in a&&!Us(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Vs(a[c],b[c])}else if(Ws(b[c])){if(c in a&&!Ws(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Xs(a[c],b[c])}else a[c]=b[c];return a}
function Xs(a,b){b=p(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Us(c)?a.push(Vs({},c)):Ws(c)?a.push(Xs([],c)):a.push(c);return a}
function Us(a){return"object"===typeof a&&!Array.isArray(a)}
function Ws(a){return"object"===typeof a&&Array.isArray(a)}
;function Ys(a,b){Sn.call(this,1,arguments);this.timer=b}
u(Ys,Sn);var Zs=new Tn("aft-recorded",Ys);var $s=window;function at(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var S=$s.performance||$s.mozPerformance||$s.msPerformance||$s.webkitPerformance||new at;var bt=!1,ct={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Xa(S.clearResourceTimings||S.webkitClearResourceTimings||S.mozClearResourceTimings||S.msClearResourceTimings||S.oClearResourceTimings||cb,S);function dt(a){var b=et("aft",a);if(b)return b;b=L((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=et(b[d],a);if(e)return e}return NaN}
function ft(){var a;if(M("csi_use_performance_navigation_timing")||M("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==S?void 0:null==(a=S.getEntriesByType)?void 0:null==(b=a.call(S,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=gt(e.requestStart),e.responseEnd=gt(e.responseEnd),e.redirectStart=gt(e.redirectStart),e.redirectEnd=gt(e.redirectEnd),e.domainLookupEnd=gt(e.domainLookupEnd),e.connectStart=gt(e.connectStart),e.connectEnd=
gt(e.connectEnd),e.responseStart=gt(e.responseStart),e.secureConnectionStart=gt(e.secureConnectionStart),e.domainLookupStart=gt(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=S.timing}else a=S.timing;return a}
function ht(){return(M("csi_use_time_origin")||M("csi_use_time_origin_tvhtml5"))&&S.timeOrigin?Math.floor(S.timeOrigin):S.timing.navigationStart}
function gt(a){return Math.round(ht()+a)}
function jt(a){var b;(b=B("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},A("ytcsi."+(a||"")+"data_",b));return b}
function kt(a){a=jt(a);a.info||(a.info={});return a.info}
function lt(a){a=jt(a);a.metadata||(a.metadata={});return a.metadata}
function mt(a){a=jt(a);a.tick||(a.tick={});return a.tick}
function et(a,b){if(a=mt(b)[a])return"number"===typeof a?a:a[a.length-1]}
function nt(a){a=jt(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function ot(a){a=nt(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function pt(a){a=nt(a);a.jspbInfos||(a.jspbInfos=[]);return a.jspbInfos}
function qt(a){var b=jt(a).nonce;b||(b=Fr(),jt(a).nonce=b);return b}
function rt(a){var b=et("_start",a),c=dt(a);b&&c&&!bt&&(Yn(Zs,new Ys(Math.round(c-b),a)),bt=!0)}
function st(a,b){for(var c=p(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!st(a[d],b[d]))return!1;return!0}
;function tt(){if(S.getEntriesByType){var a=S.getEntriesByType("paint");if(a=kb(a,function(b){return"first-paint"===b.name}))return gt(a.startTime)}a=S.timing;
return a.bd?Math.max(0,a.bd):0}
;function ut(){var a=B("ytcsi.debug");a||(a=[],A("ytcsi.debug",a),A("ytcsi.reference",{}));return a}
function vt(a){a=a||"";var b=B("ytcsi.reference");b||(ut(),b=B("ytcsi.reference"));if(b[a])return b[a];var c=ut(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var T={},wt=(T.auto_search="LATENCY_ACTION_AUTO_SEARCH",T.ad_to_ad="LATENCY_ACTION_AD_TO_AD",T.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",T["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",T.app_startup="LATENCY_ACTION_APP_STARTUP",T["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",T["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",T["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",T["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",T.browse="LATENCY_ACTION_BROWSE",
T.cast_splash="LATENCY_ACTION_CAST_SPLASH",T.channels="LATENCY_ACTION_CHANNELS",T.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",T["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",T["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",T["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",T["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",T["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",T["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",
T["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",T["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",T["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",T["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",T["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",T["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",T["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",T.chips="LATENCY_ACTION_CHIPS",
T["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",T["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",T["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",T.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",T.embed="LATENCY_ACTION_EMBED",T.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",T.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",T.explore="LATENCY_ACTION_EXPLORE",T.home=
"LATENCY_ACTION_HOME",T.library="LATENCY_ACTION_LIBRARY",T.live="LATENCY_ACTION_LIVE",T.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",T.onboarding="LATENCY_ACTION_ONBOARDING",T.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",T.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",T.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",T.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",T["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",T["post.edit"]=
"LATENCY_ACTION_CREATOR_POST_EDIT",T.prebuffer="LATENCY_ACTION_PREBUFFER",T.prefetch="LATENCY_ACTION_PREFETCH",T.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",T.profile_switcher="LATENCY_ACTION_LOGIN",T.reel_watch="LATENCY_ACTION_REEL_WATCH",T.results="LATENCY_ACTION_RESULTS",T["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",T.search_ui="LATENCY_ACTION_SEARCH_UI",T.search_suggest="LATENCY_ACTION_SUGGEST",T.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",T.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",
T.seek="LATENCY_ACTION_PLAYER_SEEK",T.settings="LATENCY_ACTION_SETTINGS",T.store="LATENCY_ACTION_STORE",T.tenx="LATENCY_ACTION_TENX",T.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",T.watch="LATENCY_ACTION_WATCH",T.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",T["watch,watch7"]="LATENCY_ACTION_WATCH",T["watch,watch7_html5"]="LATENCY_ACTION_WATCH",T["watch,watch7ad"]="LATENCY_ACTION_WATCH",T["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",T.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",T.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",
T["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",T["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",T["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",T["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",T["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",T["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",T["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",T["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",
T["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",T.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",T.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",T.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",T),V={},xt=(V.ad_allowed="adTypesAllowed",V.yt_abt="adBreakType",V.ad_cpn="adClientPlaybackNonce",V.ad_docid="adVideoId",V.yt_ad_an="adNetworks",V.ad_at="adType",V.aida="appInstallDataAgeMs",V.browse_id="browseId",V.p="httpProtocol",V.t="transportProtocol",
V.cs="commandSource",V.cpn="clientPlaybackNonce",V.ccs="creatorInfo.creatorCanaryState",V.ctop="creatorInfo.topEntityType",V.csn="clientScreenNonce",V.docid="videoId",V.GetHome_rid="requestIds",V.GetSearch_rid="requestIds",V.GetPlayer_rid="requestIds",V.GetWatchNext_rid="requestIds",V.GetBrowse_rid="requestIds",V.GetLibrary_rid="requestIds",V.is_continuation="isContinuation",V.is_nav="isNavigation",V.b_p="kabukiInfo.browseParams",V.is_prefetch="kabukiInfo.isPrefetch",V.is_secondary_nav="kabukiInfo.isSecondaryNav",
V.nav_type="kabukiInfo.navigationType",V.prev_browse_id="kabukiInfo.prevBrowseId",V.query_source="kabukiInfo.querySource",V.voz_type="kabukiInfo.vozType",V.yt_lt="loadType",V.mver="creatorInfo.measurementVersion",V.yt_ad="isMonetized",V.nr="webInfo.navigationReason",V.nrsu="navigationRequestedSameUrl",V.pnt="performanceNavigationTiming",V.prt="playbackRequiresTap",V.plt="playerInfo.playbackType",V.pis="playerInfo.playerInitializedState",V.paused="playerInfo.isPausedOnLoad",V.yt_pt="playerType",V.fmt=
"playerInfo.itag",V.yt_pl="watchInfo.isPlaylist",V.yt_pre="playerInfo.preloadType",V.yt_ad_pr="prerollAllowed",V.pa="previousAction",V.yt_red="isRedSubscriber",V.rce="mwebInfo.responseContentEncoding",V.rc="resourceInfo.resourceCache",V.scrh="screenHeight",V.scrw="screenWidth",V.st="serverTimeMs",V.ssdm="shellStartupDurationMs",V.br_trs="tvInfo.bedrockTriggerState",V.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",V.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",V.label="tvInfo.label",
V.is_mdx="tvInfo.isMdx",V.preloaded="tvInfo.isPreloaded",V.aac_type="tvInfo.authAccessCredentialType",V.upg_player_vis="playerInfo.visibilityState",V.query="unpluggedInfo.query",V.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",V.yt_vst="videoStreamType",V.vph="viewportHeight",V.vpw="viewportWidth",V.yt_vis="isVisible",V.rcl="mwebInfo.responseContentLength",V.GetSettings_rid="requestIds",V.GetTrending_rid="requestIds",V.GetMusicSearchSuggestions_rid="requestIds",V.REQUEST_ID="requestIds",V),
zt="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),At={},Bt=(At.ccs="CANARY_STATE_",At.mver="MEASUREMENT_VERSION_",At.pis="PLAYER_INITIALIZED_STATE_",At.yt_pt="LATENCY_PLAYER_",At.pa="LATENCY_ACTION_",At.ctop="TOP_ENTITY_TYPE_",
At.yt_vst="VIDEO_STREAM_TYPE_",At),Ct="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");function Dt(a){return wt[a]||"LATENCY_ACTION_UNKNOWN"}
function Et(a,b,c){c=nt(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in xt){c=xt[a];0<=eb(zt,c)&&(b=!!b);a in Bt&&"string"===typeof b&&(b=Bt[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Ts({},d)}0<=eb(Ct,a)||yr(new R("Unknown label logged with GEL CSI",a))}
;var W={LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING:179,LATENCY_ACTION_KIDS_PROFILE_SWITCHER:90,LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER:100,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC:46,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR:37,LATENCY_ACTION_SPINNER_DISPLAYED:14,LATENCY_ACTION_PLAYABILITY_CHECK:10,LATENCY_ACTION_PROCESS:9,LATENCY_ACTION_APP_STARTUP:5,LATENCY_ACTION_COMMERCE_TRANSACTION:184,LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC:173,LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC:172,
LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC:171,LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC:170,LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC:169,LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC:168,LATENCY_ACTION_GET_OFFERS_RPC:167,LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC:166,LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC:165,LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC:164,LATENCY_ACTION_GET_OFFER_DETAILS_RPC:163,LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC:162,LATENCY_ACTION_GET_TIP_MODULE_RPC:161,LATENCY_ACTION_HANDLE_TRANSACTION_RPC:160,
LATENCY_ACTION_COMPLETE_TRANSACTION_RPC:159,LATENCY_ACTION_GET_CART_RPC:158,LATENCY_ACTION_THUMBNAIL_FETCH:156,LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK:154,LATENCY_ACTION_SHARE_VIDEO:153,LATENCY_ACTION_AD_TO_VIDEO_INT:152,LATENCY_ACTION_ABANDONED_BROWSE:151,LATENCY_ACTION_PLAYER_ROTATION:150,LATENCY_ACTION_GENERIC_WEB_VIEW:183,LATENCY_ACTION_SHOPPING_IN_APP:124,LATENCY_ACTION_PLAYER_ATTESTATION:121,LATENCY_ACTION_PLAYER_SEEK:119,LATENCY_ACTION_SUPER_STICKER_BUY_FLOW:114,LATENCY_ACTION_DOWNLOADS_DATA_ACCESS:180,
LATENCY_ACTION_BLOCKS_PERFORMANCE:148,LATENCY_ACTION_ASSISTANT_QUERY:138,LATENCY_ACTION_ASSISTANT_SETTINGS:137,LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF:129,LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF:128,LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE:127,LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION:123,LATENCY_ACTION_NETWORKLESS_PERFORMANCE:122,LATENCY_ACTION_DOWNLOADS_EXPANSION:133,LATENCY_ACTION_ENTITY_TRANSFORM:131,LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER:96,LATENCY_ACTION_EMBEDS_SET_VIDEO:95,
LATENCY_ACTION_SETTINGS:93,LATENCY_ACTION_ABANDONED_STARTUP:81,LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY:80,LATENCY_ACTION_MEDIA_BROWSER_SEARCH:79,LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE:78,LATENCY_ACTION_WHO_IS_WATCHING:77,LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH:76,LATENCY_ACTION_LITE_SWITCH_ACCOUNT:73,LATENCY_ACTION_ELEMENTS_PERFORMANCE:70,LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION:69,LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION:65,LATENCY_ACTION_OFFLINE_STORE_START:61,LATENCY_ACTION_REEL_EDITOR:58,
LATENCY_ACTION_CHANNEL_SUBSCRIBE:56,LATENCY_ACTION_CHANNEL_PREVIEW:55,LATENCY_ACTION_PREFETCH:52,LATENCY_ACTION_ABANDONED_WATCH:45,LATENCY_ACTION_LOAD_COMMENT_REPLIES:26,LATENCY_ACTION_LOAD_COMMENTS:25,LATENCY_ACTION_EDIT_COMMENT:24,LATENCY_ACTION_NEW_COMMENT:23,LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING:19,LATENCY_ACTION_EMBED:18,LATENCY_ACTION_MDX_LAUNCH:15,LATENCY_ACTION_RESOLVE_URL:13,LATENCY_ACTION_CAST_SPLASH:149,LATENCY_ACTION_MDX_STREAM_TRANSFER:178,LATENCY_ACTION_MDX_CAST:120,LATENCY_ACTION_MDX_COMMAND:12,
LATENCY_ACTION_REEL_SELECT_SEGMENT:136,LATENCY_ACTION_ACCELERATED_EFFECTS:145,LATENCY_ACTION_EDIT_AUDIO_GEN:182,LATENCY_ACTION_UPLOAD_AUDIO_MIXER:147,LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING:157,LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING:146,LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK:130,LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD:125,LATENCY_ACTION_SHORTS_VIDEO_INGESTION:155,LATENCY_ACTION_SHORTS_GALLERY:107,LATENCY_ACTION_SHORTS_TRIM:105,LATENCY_ACTION_SHORTS_EDIT:104,LATENCY_ACTION_SHORTS_CAMERA:103,
LATENCY_ACTION_PARENT_TOOLS_DASHBOARD:102,LATENCY_ACTION_PARENT_TOOLS_COLLECTION:101,LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS:116,LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS:115,LATENCY_ACTION_MUSIC_ALBUM_DETAIL:72,LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL:71,LATENCY_ACTION_STORE:175,LATENCY_ACTION_CHIPS:68,LATENCY_ACTION_SEARCH_ZERO_STATE:67,LATENCY_ACTION_LIVE_PAGINATION:117,LATENCY_ACTION_LIVE:20,LATENCY_ACTION_PREBUFFER:40,LATENCY_ACTION_TENX:39,LATENCY_ACTION_KIDS_PROFILE_SETTINGS:94,LATENCY_ACTION_KIDS_WATCH_IT_AGAIN:92,
LATENCY_ACTION_KIDS_SECRET_CODE:91,LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS:89,LATENCY_ACTION_KIDS_ONBOARDING:88,LATENCY_ACTION_KIDS_VOICE_SEARCH:82,LATENCY_ACTION_KIDS_CURATED_COLLECTION:62,LATENCY_ACTION_KIDS_LIBRARY:53,LATENCY_ACTION_CREATOR_PROMOTION_LIST:186,LATENCY_ACTION_CREATOR_PROMOTION_EDIT:185,LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS:38,LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION:74,LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING:141,LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS:142,LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC:51,
LATENCY_ACTION_CREATOR_VIDEO_EDITOR:50,LATENCY_ACTION_CREATOR_VIDEO_EDIT:36,LATENCY_ACTION_CREATOR_VIDEO_COMMENTS:34,LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS:33,LATENCY_ACTION_CREATOR_SONG_ANALYTICS:176,LATENCY_ACTION_CREATOR_POST_LIST:112,LATENCY_ACTION_CREATOR_POST_EDIT:110,LATENCY_ACTION_CREATOR_POST_COMMENTS:111,LATENCY_ACTION_CREATOR_LIVE_STREAMING:108,LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT:174,LATENCY_ACTION_CREATOR_DIALOG_UPLOADS:86,LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES:87,LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS:32,
LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS:48,LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS:139,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT:177,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC:99,LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION:43,LATENCY_ACTION_CREATOR_CHANNEL_EDITING:113,LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD:49,LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT:44,LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS:66,LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS:31,LATENCY_ACTION_CREATOR_ARTIST_PROFILE:85,LATENCY_ACTION_CREATOR_ARTIST_CONCERTS:84,
LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS:83,LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE:140,LATENCY_ACTION_EXPERIMENTAL_WATCH_UI:181,LATENCY_ACTION_STORYBOARD_THUMBNAILS:118,LATENCY_ACTION_SEARCH_THUMBNAILS:59,LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD:54,LATENCY_ACTION_VOICE_ASSISTANT:47,LATENCY_ACTION_SEARCH_UI:35,LATENCY_ACTION_SUGGEST:30,LATENCY_ACTION_AUTO_SEARCH:126,LATENCY_ACTION_DOWNLOADS:98,LATENCY_ACTION_EXPLORE:75,LATENCY_ACTION_VIDEO_LIST:63,LATENCY_ACTION_HOME_RESUME:60,LATENCY_ACTION_SUBSCRIPTIONS_LIST:57,
LATENCY_ACTION_THUMBNAIL_LOAD:42,LATENCY_ACTION_FIRST_THUMBNAIL_LOAD:29,LATENCY_ACTION_SUBSCRIPTIONS_FEED:109,LATENCY_ACTION_SUBSCRIPTIONS:28,LATENCY_ACTION_TRENDING:27,LATENCY_ACTION_LIBRARY:21,LATENCY_ACTION_VIDEO_THUMBNAIL:8,LATENCY_ACTION_SHOW_MORE:7,LATENCY_ACTION_VIDEO_PREVIEW:6,LATENCY_ACTION_AD_TO_AD:22,LATENCY_ACTION_VIDEO_TO_AD:17,LATENCY_ACTION_AD_TO_VIDEO:16,LATENCY_ACTION_DIRECT_PLAYBACK:132,LATENCY_ACTION_PREBUFFER_VIDEO:144,LATENCY_ACTION_PREFETCH_VIDEO:143,LATENCY_ACTION_STARTUP:106,
LATENCY_ACTION_ONBOARDING:135,LATENCY_ACTION_LOGIN:97,LATENCY_ACTION_REEL_WATCH:41,LATENCY_ACTION_WATCH:3,LATENCY_ACTION_RESULTS:2,LATENCY_ACTION_CHANNELS:4,LATENCY_ACTION_HOME:1,LATENCY_ACTION_BROWSE:11,LATENCY_ACTION_USER_ACTION:189,LATENCY_ACTION_INFRASTRUCTURE:188,LATENCY_ACTION_PAGE_NAVIGATION:187,LATENCY_ACTION_UNKNOWN:0};W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING";W[W.LATENCY_ACTION_KIDS_PROFILE_SWITCHER]="LATENCY_ACTION_KIDS_PROFILE_SWITCHER";
W[W.LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER]="LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER";W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC";W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR";W[W.LATENCY_ACTION_SPINNER_DISPLAYED]="LATENCY_ACTION_SPINNER_DISPLAYED";W[W.LATENCY_ACTION_PLAYABILITY_CHECK]="LATENCY_ACTION_PLAYABILITY_CHECK";W[W.LATENCY_ACTION_PROCESS]="LATENCY_ACTION_PROCESS";
W[W.LATENCY_ACTION_APP_STARTUP]="LATENCY_ACTION_APP_STARTUP";W[W.LATENCY_ACTION_COMMERCE_TRANSACTION]="LATENCY_ACTION_COMMERCE_TRANSACTION";W[W.LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC]="LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC";W[W.LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC]="LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC";W[W.LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC]="LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC";W[W.LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC]="LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC";
W[W.LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC]="LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC";W[W.LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC]="LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC";W[W.LATENCY_ACTION_GET_OFFERS_RPC]="LATENCY_ACTION_GET_OFFERS_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC";W[W.LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC]="LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC";
W[W.LATENCY_ACTION_GET_OFFER_DETAILS_RPC]="LATENCY_ACTION_GET_OFFER_DETAILS_RPC";W[W.LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC]="LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_TIP_MODULE_RPC]="LATENCY_ACTION_GET_TIP_MODULE_RPC";W[W.LATENCY_ACTION_HANDLE_TRANSACTION_RPC]="LATENCY_ACTION_HANDLE_TRANSACTION_RPC";W[W.LATENCY_ACTION_COMPLETE_TRANSACTION_RPC]="LATENCY_ACTION_COMPLETE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_CART_RPC]="LATENCY_ACTION_GET_CART_RPC";
W[W.LATENCY_ACTION_THUMBNAIL_FETCH]="LATENCY_ACTION_THUMBNAIL_FETCH";W[W.LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK]="LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_SHARE_VIDEO]="LATENCY_ACTION_SHARE_VIDEO";W[W.LATENCY_ACTION_AD_TO_VIDEO_INT]="LATENCY_ACTION_AD_TO_VIDEO_INT";W[W.LATENCY_ACTION_ABANDONED_BROWSE]="LATENCY_ACTION_ABANDONED_BROWSE";W[W.LATENCY_ACTION_PLAYER_ROTATION]="LATENCY_ACTION_PLAYER_ROTATION";W[W.LATENCY_ACTION_GENERIC_WEB_VIEW]="LATENCY_ACTION_GENERIC_WEB_VIEW";
W[W.LATENCY_ACTION_SHOPPING_IN_APP]="LATENCY_ACTION_SHOPPING_IN_APP";W[W.LATENCY_ACTION_PLAYER_ATTESTATION]="LATENCY_ACTION_PLAYER_ATTESTATION";W[W.LATENCY_ACTION_PLAYER_SEEK]="LATENCY_ACTION_PLAYER_SEEK";W[W.LATENCY_ACTION_SUPER_STICKER_BUY_FLOW]="LATENCY_ACTION_SUPER_STICKER_BUY_FLOW";W[W.LATENCY_ACTION_DOWNLOADS_DATA_ACCESS]="LATENCY_ACTION_DOWNLOADS_DATA_ACCESS";W[W.LATENCY_ACTION_BLOCKS_PERFORMANCE]="LATENCY_ACTION_BLOCKS_PERFORMANCE";W[W.LATENCY_ACTION_ASSISTANT_QUERY]="LATENCY_ACTION_ASSISTANT_QUERY";
W[W.LATENCY_ACTION_ASSISTANT_SETTINGS]="LATENCY_ACTION_ASSISTANT_SETTINGS";W[W.LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF";W[W.LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF";W[W.LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE]="LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE";W[W.LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION]="LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION";
W[W.LATENCY_ACTION_NETWORKLESS_PERFORMANCE]="LATENCY_ACTION_NETWORKLESS_PERFORMANCE";W[W.LATENCY_ACTION_DOWNLOADS_EXPANSION]="LATENCY_ACTION_DOWNLOADS_EXPANSION";W[W.LATENCY_ACTION_ENTITY_TRANSFORM]="LATENCY_ACTION_ENTITY_TRANSFORM";W[W.LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER]="LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER";W[W.LATENCY_ACTION_EMBEDS_SET_VIDEO]="LATENCY_ACTION_EMBEDS_SET_VIDEO";W[W.LATENCY_ACTION_SETTINGS]="LATENCY_ACTION_SETTINGS";W[W.LATENCY_ACTION_ABANDONED_STARTUP]="LATENCY_ACTION_ABANDONED_STARTUP";
W[W.LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY]="LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY";W[W.LATENCY_ACTION_MEDIA_BROWSER_SEARCH]="LATENCY_ACTION_MEDIA_BROWSER_SEARCH";W[W.LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE]="LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE";W[W.LATENCY_ACTION_WHO_IS_WATCHING]="LATENCY_ACTION_WHO_IS_WATCHING";W[W.LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH]="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH";W[W.LATENCY_ACTION_LITE_SWITCH_ACCOUNT]="LATENCY_ACTION_LITE_SWITCH_ACCOUNT";
W[W.LATENCY_ACTION_ELEMENTS_PERFORMANCE]="LATENCY_ACTION_ELEMENTS_PERFORMANCE";W[W.LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION]="LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION";W[W.LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION]="LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION";W[W.LATENCY_ACTION_OFFLINE_STORE_START]="LATENCY_ACTION_OFFLINE_STORE_START";W[W.LATENCY_ACTION_REEL_EDITOR]="LATENCY_ACTION_REEL_EDITOR";W[W.LATENCY_ACTION_CHANNEL_SUBSCRIBE]="LATENCY_ACTION_CHANNEL_SUBSCRIBE";
W[W.LATENCY_ACTION_CHANNEL_PREVIEW]="LATENCY_ACTION_CHANNEL_PREVIEW";W[W.LATENCY_ACTION_PREFETCH]="LATENCY_ACTION_PREFETCH";W[W.LATENCY_ACTION_ABANDONED_WATCH]="LATENCY_ACTION_ABANDONED_WATCH";W[W.LATENCY_ACTION_LOAD_COMMENT_REPLIES]="LATENCY_ACTION_LOAD_COMMENT_REPLIES";W[W.LATENCY_ACTION_LOAD_COMMENTS]="LATENCY_ACTION_LOAD_COMMENTS";W[W.LATENCY_ACTION_EDIT_COMMENT]="LATENCY_ACTION_EDIT_COMMENT";W[W.LATENCY_ACTION_NEW_COMMENT]="LATENCY_ACTION_NEW_COMMENT";
W[W.LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING]="LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING";W[W.LATENCY_ACTION_EMBED]="LATENCY_ACTION_EMBED";W[W.LATENCY_ACTION_MDX_LAUNCH]="LATENCY_ACTION_MDX_LAUNCH";W[W.LATENCY_ACTION_RESOLVE_URL]="LATENCY_ACTION_RESOLVE_URL";W[W.LATENCY_ACTION_CAST_SPLASH]="LATENCY_ACTION_CAST_SPLASH";W[W.LATENCY_ACTION_MDX_STREAM_TRANSFER]="LATENCY_ACTION_MDX_STREAM_TRANSFER";W[W.LATENCY_ACTION_MDX_CAST]="LATENCY_ACTION_MDX_CAST";W[W.LATENCY_ACTION_MDX_COMMAND]="LATENCY_ACTION_MDX_COMMAND";
W[W.LATENCY_ACTION_REEL_SELECT_SEGMENT]="LATENCY_ACTION_REEL_SELECT_SEGMENT";W[W.LATENCY_ACTION_ACCELERATED_EFFECTS]="LATENCY_ACTION_ACCELERATED_EFFECTS";W[W.LATENCY_ACTION_EDIT_AUDIO_GEN]="LATENCY_ACTION_EDIT_AUDIO_GEN";W[W.LATENCY_ACTION_UPLOAD_AUDIO_MIXER]="LATENCY_ACTION_UPLOAD_AUDIO_MIXER";W[W.LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING]="LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING";W[W.LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING]="LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING";
W[W.LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK]="LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK";W[W.LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD]="LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD";W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION";W[W.LATENCY_ACTION_SHORTS_GALLERY]="LATENCY_ACTION_SHORTS_GALLERY";W[W.LATENCY_ACTION_SHORTS_TRIM]="LATENCY_ACTION_SHORTS_TRIM";W[W.LATENCY_ACTION_SHORTS_EDIT]="LATENCY_ACTION_SHORTS_EDIT";W[W.LATENCY_ACTION_SHORTS_CAMERA]="LATENCY_ACTION_SHORTS_CAMERA";
W[W.LATENCY_ACTION_PARENT_TOOLS_DASHBOARD]="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD";W[W.LATENCY_ACTION_PARENT_TOOLS_COLLECTION]="LATENCY_ACTION_PARENT_TOOLS_COLLECTION";W[W.LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_ALBUM_DETAIL";W[W.LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL";
W[W.LATENCY_ACTION_STORE]="LATENCY_ACTION_STORE";W[W.LATENCY_ACTION_CHIPS]="LATENCY_ACTION_CHIPS";W[W.LATENCY_ACTION_SEARCH_ZERO_STATE]="LATENCY_ACTION_SEARCH_ZERO_STATE";W[W.LATENCY_ACTION_LIVE_PAGINATION]="LATENCY_ACTION_LIVE_PAGINATION";W[W.LATENCY_ACTION_LIVE]="LATENCY_ACTION_LIVE";W[W.LATENCY_ACTION_PREBUFFER]="LATENCY_ACTION_PREBUFFER";W[W.LATENCY_ACTION_TENX]="LATENCY_ACTION_TENX";W[W.LATENCY_ACTION_KIDS_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PROFILE_SETTINGS";
W[W.LATENCY_ACTION_KIDS_WATCH_IT_AGAIN]="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN";W[W.LATENCY_ACTION_KIDS_SECRET_CODE]="LATENCY_ACTION_KIDS_SECRET_CODE";W[W.LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS";W[W.LATENCY_ACTION_KIDS_ONBOARDING]="LATENCY_ACTION_KIDS_ONBOARDING";W[W.LATENCY_ACTION_KIDS_VOICE_SEARCH]="LATENCY_ACTION_KIDS_VOICE_SEARCH";W[W.LATENCY_ACTION_KIDS_CURATED_COLLECTION]="LATENCY_ACTION_KIDS_CURATED_COLLECTION";
W[W.LATENCY_ACTION_KIDS_LIBRARY]="LATENCY_ACTION_KIDS_LIBRARY";W[W.LATENCY_ACTION_CREATOR_PROMOTION_LIST]="LATENCY_ACTION_CREATOR_PROMOTION_LIST";W[W.LATENCY_ACTION_CREATOR_PROMOTION_EDIT]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT";W[W.LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION";W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING";
W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDIT]="LATENCY_ACTION_CREATOR_VIDEO_EDIT";W[W.LATENCY_ACTION_CREATOR_VIDEO_COMMENTS]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS";W[W.LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS";
W[W.LATENCY_ACTION_CREATOR_SONG_ANALYTICS]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_POST_LIST]="LATENCY_ACTION_CREATOR_POST_LIST";W[W.LATENCY_ACTION_CREATOR_POST_EDIT]="LATENCY_ACTION_CREATOR_POST_EDIT";W[W.LATENCY_ACTION_CREATOR_POST_COMMENTS]="LATENCY_ACTION_CREATOR_POST_COMMENTS";W[W.LATENCY_ACTION_CREATOR_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_LIVE_STREAMING";W[W.LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT";
W[W.LATENCY_ACTION_CREATOR_DIALOG_UPLOADS]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS";W[W.LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES";W[W.LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION";W[W.LATENCY_ACTION_CREATOR_CHANNEL_EDITING]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING";W[W.LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD]="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ARTIST_PROFILE]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE";W[W.LATENCY_ACTION_CREATOR_ARTIST_CONCERTS]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS";W[W.LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE";
W[W.LATENCY_ACTION_EXPERIMENTAL_WATCH_UI]="LATENCY_ACTION_EXPERIMENTAL_WATCH_UI";W[W.LATENCY_ACTION_STORYBOARD_THUMBNAILS]="LATENCY_ACTION_STORYBOARD_THUMBNAILS";W[W.LATENCY_ACTION_SEARCH_THUMBNAILS]="LATENCY_ACTION_SEARCH_THUMBNAILS";W[W.LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD]="LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD";W[W.LATENCY_ACTION_VOICE_ASSISTANT]="LATENCY_ACTION_VOICE_ASSISTANT";W[W.LATENCY_ACTION_SEARCH_UI]="LATENCY_ACTION_SEARCH_UI";W[W.LATENCY_ACTION_SUGGEST]="LATENCY_ACTION_SUGGEST";
W[W.LATENCY_ACTION_AUTO_SEARCH]="LATENCY_ACTION_AUTO_SEARCH";W[W.LATENCY_ACTION_DOWNLOADS]="LATENCY_ACTION_DOWNLOADS";W[W.LATENCY_ACTION_EXPLORE]="LATENCY_ACTION_EXPLORE";W[W.LATENCY_ACTION_VIDEO_LIST]="LATENCY_ACTION_VIDEO_LIST";W[W.LATENCY_ACTION_HOME_RESUME]="LATENCY_ACTION_HOME_RESUME";W[W.LATENCY_ACTION_SUBSCRIPTIONS_LIST]="LATENCY_ACTION_SUBSCRIPTIONS_LIST";W[W.LATENCY_ACTION_THUMBNAIL_LOAD]="LATENCY_ACTION_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_FIRST_THUMBNAIL_LOAD]="LATENCY_ACTION_FIRST_THUMBNAIL_LOAD";
W[W.LATENCY_ACTION_SUBSCRIPTIONS_FEED]="LATENCY_ACTION_SUBSCRIPTIONS_FEED";W[W.LATENCY_ACTION_SUBSCRIPTIONS]="LATENCY_ACTION_SUBSCRIPTIONS";W[W.LATENCY_ACTION_TRENDING]="LATENCY_ACTION_TRENDING";W[W.LATENCY_ACTION_LIBRARY]="LATENCY_ACTION_LIBRARY";W[W.LATENCY_ACTION_VIDEO_THUMBNAIL]="LATENCY_ACTION_VIDEO_THUMBNAIL";W[W.LATENCY_ACTION_SHOW_MORE]="LATENCY_ACTION_SHOW_MORE";W[W.LATENCY_ACTION_VIDEO_PREVIEW]="LATENCY_ACTION_VIDEO_PREVIEW";W[W.LATENCY_ACTION_AD_TO_AD]="LATENCY_ACTION_AD_TO_AD";
W[W.LATENCY_ACTION_VIDEO_TO_AD]="LATENCY_ACTION_VIDEO_TO_AD";W[W.LATENCY_ACTION_AD_TO_VIDEO]="LATENCY_ACTION_AD_TO_VIDEO";W[W.LATENCY_ACTION_DIRECT_PLAYBACK]="LATENCY_ACTION_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_PREBUFFER_VIDEO]="LATENCY_ACTION_PREBUFFER_VIDEO";W[W.LATENCY_ACTION_PREFETCH_VIDEO]="LATENCY_ACTION_PREFETCH_VIDEO";W[W.LATENCY_ACTION_STARTUP]="LATENCY_ACTION_STARTUP";W[W.LATENCY_ACTION_ONBOARDING]="LATENCY_ACTION_ONBOARDING";W[W.LATENCY_ACTION_LOGIN]="LATENCY_ACTION_LOGIN";
W[W.LATENCY_ACTION_REEL_WATCH]="LATENCY_ACTION_REEL_WATCH";W[W.LATENCY_ACTION_WATCH]="LATENCY_ACTION_WATCH";W[W.LATENCY_ACTION_RESULTS]="LATENCY_ACTION_RESULTS";W[W.LATENCY_ACTION_CHANNELS]="LATENCY_ACTION_CHANNELS";W[W.LATENCY_ACTION_HOME]="LATENCY_ACTION_HOME";W[W.LATENCY_ACTION_BROWSE]="LATENCY_ACTION_BROWSE";W[W.LATENCY_ACTION_USER_ACTION]="LATENCY_ACTION_USER_ACTION";W[W.LATENCY_ACTION_INFRASTRUCTURE]="LATENCY_ACTION_INFRASTRUCTURE";W[W.LATENCY_ACTION_PAGE_NAVIGATION]="LATENCY_ACTION_PAGE_NAVIGATION";
W[W.LATENCY_ACTION_UNKNOWN]="LATENCY_ACTION_UNKNOWN";var Ft={LATENCY_NETWORK_MOBILE:2,LATENCY_NETWORK_WIFI:1,LATENCY_NETWORK_UNKNOWN:0};Ft[Ft.LATENCY_NETWORK_MOBILE]="LATENCY_NETWORK_MOBILE";Ft[Ft.LATENCY_NETWORK_WIFI]="LATENCY_NETWORK_WIFI";Ft[Ft.LATENCY_NETWORK_UNKNOWN]="LATENCY_NETWORK_UNKNOWN";
var X={CONN_INVALID:31,CONN_CELLULAR_5G_NSA:12,CONN_CELLULAR_5G_SA:11,CONN_WIFI_METERED:10,CONN_CELLULAR_5G:9,CONN_DISCO:8,CONN_CELLULAR_UNKNOWN:7,CONN_CELLULAR_4G:6,CONN_CELLULAR_3G:5,CONN_CELLULAR_2G:4,CONN_WIFI:3,CONN_NONE:2,CONN_UNKNOWN:1,CONN_DEFAULT:0};X[X.CONN_INVALID]="CONN_INVALID";X[X.CONN_CELLULAR_5G_NSA]="CONN_CELLULAR_5G_NSA";X[X.CONN_CELLULAR_5G_SA]="CONN_CELLULAR_5G_SA";X[X.CONN_WIFI_METERED]="CONN_WIFI_METERED";X[X.CONN_CELLULAR_5G]="CONN_CELLULAR_5G";X[X.CONN_DISCO]="CONN_DISCO";
X[X.CONN_CELLULAR_UNKNOWN]="CONN_CELLULAR_UNKNOWN";X[X.CONN_CELLULAR_4G]="CONN_CELLULAR_4G";X[X.CONN_CELLULAR_3G]="CONN_CELLULAR_3G";X[X.CONN_CELLULAR_2G]="CONN_CELLULAR_2G";X[X.CONN_WIFI]="CONN_WIFI";X[X.CONN_NONE]="CONN_NONE";X[X.CONN_UNKNOWN]="CONN_UNKNOWN";X[X.CONN_DEFAULT]="CONN_DEFAULT";
var Y={DETAILED_NETWORK_TYPE_NR_NSA:126,DETAILED_NETWORK_TYPE_NR_SA:125,DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED:124,DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT:123,DETAILED_NETWORK_TYPE_DISCONNECTED:122,DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN:121,DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN:120,DETAILED_NETWORK_TYPE_WIMAX:119,DETAILED_NETWORK_TYPE_ETHERNET:118,DETAILED_NETWORK_TYPE_BLUETOOTH:117,DETAILED_NETWORK_TYPE_WIFI:116,DETAILED_NETWORK_TYPE_LTE:115,DETAILED_NETWORK_TYPE_HSPAP:114,DETAILED_NETWORK_TYPE_EHRPD:113,
DETAILED_NETWORK_TYPE_EVDO_B:112,DETAILED_NETWORK_TYPE_UMTS:111,DETAILED_NETWORK_TYPE_IDEN:110,DETAILED_NETWORK_TYPE_HSUPA:109,DETAILED_NETWORK_TYPE_HSPA:108,DETAILED_NETWORK_TYPE_HSDPA:107,DETAILED_NETWORK_TYPE_EVDO_A:106,DETAILED_NETWORK_TYPE_EVDO_0:105,DETAILED_NETWORK_TYPE_CDMA:104,DETAILED_NETWORK_TYPE_1_X_RTT:103,DETAILED_NETWORK_TYPE_GPRS:102,DETAILED_NETWORK_TYPE_EDGE:101,DETAILED_NETWORK_TYPE_UNKNOWN:0};Y[Y.DETAILED_NETWORK_TYPE_NR_NSA]="DETAILED_NETWORK_TYPE_NR_NSA";
Y[Y.DETAILED_NETWORK_TYPE_NR_SA]="DETAILED_NETWORK_TYPE_NR_SA";Y[Y.DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED]="DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED";Y[Y.DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT]="DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT";Y[Y.DETAILED_NETWORK_TYPE_DISCONNECTED]="DETAILED_NETWORK_TYPE_DISCONNECTED";Y[Y.DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN";Y[Y.DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN";
Y[Y.DETAILED_NETWORK_TYPE_WIMAX]="DETAILED_NETWORK_TYPE_WIMAX";Y[Y.DETAILED_NETWORK_TYPE_ETHERNET]="DETAILED_NETWORK_TYPE_ETHERNET";Y[Y.DETAILED_NETWORK_TYPE_BLUETOOTH]="DETAILED_NETWORK_TYPE_BLUETOOTH";Y[Y.DETAILED_NETWORK_TYPE_WIFI]="DETAILED_NETWORK_TYPE_WIFI";Y[Y.DETAILED_NETWORK_TYPE_LTE]="DETAILED_NETWORK_TYPE_LTE";Y[Y.DETAILED_NETWORK_TYPE_HSPAP]="DETAILED_NETWORK_TYPE_HSPAP";Y[Y.DETAILED_NETWORK_TYPE_EHRPD]="DETAILED_NETWORK_TYPE_EHRPD";Y[Y.DETAILED_NETWORK_TYPE_EVDO_B]="DETAILED_NETWORK_TYPE_EVDO_B";
Y[Y.DETAILED_NETWORK_TYPE_UMTS]="DETAILED_NETWORK_TYPE_UMTS";Y[Y.DETAILED_NETWORK_TYPE_IDEN]="DETAILED_NETWORK_TYPE_IDEN";Y[Y.DETAILED_NETWORK_TYPE_HSUPA]="DETAILED_NETWORK_TYPE_HSUPA";Y[Y.DETAILED_NETWORK_TYPE_HSPA]="DETAILED_NETWORK_TYPE_HSPA";Y[Y.DETAILED_NETWORK_TYPE_HSDPA]="DETAILED_NETWORK_TYPE_HSDPA";Y[Y.DETAILED_NETWORK_TYPE_EVDO_A]="DETAILED_NETWORK_TYPE_EVDO_A";Y[Y.DETAILED_NETWORK_TYPE_EVDO_0]="DETAILED_NETWORK_TYPE_EVDO_0";Y[Y.DETAILED_NETWORK_TYPE_CDMA]="DETAILED_NETWORK_TYPE_CDMA";
Y[Y.DETAILED_NETWORK_TYPE_1_X_RTT]="DETAILED_NETWORK_TYPE_1_X_RTT";Y[Y.DETAILED_NETWORK_TYPE_GPRS]="DETAILED_NETWORK_TYPE_GPRS";Y[Y.DETAILED_NETWORK_TYPE_EDGE]="DETAILED_NETWORK_TYPE_EDGE";Y[Y.DETAILED_NETWORK_TYPE_UNKNOWN]="DETAILED_NETWORK_TYPE_UNKNOWN";var Gt={LATENCY_PLAYER_RTSP:7,LATENCY_PLAYER_HTML5_INLINE:6,LATENCY_PLAYER_HTML5_FULLSCREEN:5,LATENCY_PLAYER_HTML5:4,LATENCY_PLAYER_FRAMEWORK:3,LATENCY_PLAYER_FLASH:2,LATENCY_PLAYER_EXO:1,LATENCY_PLAYER_UNKNOWN:0};Gt[Gt.LATENCY_PLAYER_RTSP]="LATENCY_PLAYER_RTSP";
Gt[Gt.LATENCY_PLAYER_HTML5_INLINE]="LATENCY_PLAYER_HTML5_INLINE";Gt[Gt.LATENCY_PLAYER_HTML5_FULLSCREEN]="LATENCY_PLAYER_HTML5_FULLSCREEN";Gt[Gt.LATENCY_PLAYER_HTML5]="LATENCY_PLAYER_HTML5";Gt[Gt.LATENCY_PLAYER_FRAMEWORK]="LATENCY_PLAYER_FRAMEWORK";Gt[Gt.LATENCY_PLAYER_FLASH]="LATENCY_PLAYER_FLASH";Gt[Gt.LATENCY_PLAYER_EXO]="LATENCY_PLAYER_EXO";Gt[Gt.LATENCY_PLAYER_UNKNOWN]="LATENCY_PLAYER_UNKNOWN";
var Ht={LATENCY_AD_BREAK_TYPE_POSTROLL:3,LATENCY_AD_BREAK_TYPE_MIDROLL:2,LATENCY_AD_BREAK_TYPE_PREROLL:1,LATENCY_AD_BREAK_TYPE_UNKNOWN:0};Ht[Ht.LATENCY_AD_BREAK_TYPE_POSTROLL]="LATENCY_AD_BREAK_TYPE_POSTROLL";Ht[Ht.LATENCY_AD_BREAK_TYPE_MIDROLL]="LATENCY_AD_BREAK_TYPE_MIDROLL";Ht[Ht.LATENCY_AD_BREAK_TYPE_PREROLL]="LATENCY_AD_BREAK_TYPE_PREROLL";Ht[Ht.LATENCY_AD_BREAK_TYPE_UNKNOWN]="LATENCY_AD_BREAK_TYPE_UNKNOWN";var It={LATENCY_ACTION_ERROR_STARTUP_TIMEOUT:1,LATENCY_ACTION_ERROR_UNSPECIFIED:0};
It[It.LATENCY_ACTION_ERROR_STARTUP_TIMEOUT]="LATENCY_ACTION_ERROR_STARTUP_TIMEOUT";It[It.LATENCY_ACTION_ERROR_UNSPECIFIED]="LATENCY_ACTION_ERROR_UNSPECIFIED";var Jt={LIVE_STREAM_MODE_WINDOW:5,LIVE_STREAM_MODE_POST:4,LIVE_STREAM_MODE_LP:3,LIVE_STREAM_MODE_LIVE:2,LIVE_STREAM_MODE_DVR:1,LIVE_STREAM_MODE_UNKNOWN:0};Jt[Jt.LIVE_STREAM_MODE_WINDOW]="LIVE_STREAM_MODE_WINDOW";Jt[Jt.LIVE_STREAM_MODE_POST]="LIVE_STREAM_MODE_POST";Jt[Jt.LIVE_STREAM_MODE_LP]="LIVE_STREAM_MODE_LP";
Jt[Jt.LIVE_STREAM_MODE_LIVE]="LIVE_STREAM_MODE_LIVE";Jt[Jt.LIVE_STREAM_MODE_DVR]="LIVE_STREAM_MODE_DVR";Jt[Jt.LIVE_STREAM_MODE_UNKNOWN]="LIVE_STREAM_MODE_UNKNOWN";var Kt={VIDEO_STREAM_TYPE_VOD:3,VIDEO_STREAM_TYPE_DVR:2,VIDEO_STREAM_TYPE_LIVE:1,VIDEO_STREAM_TYPE_UNSPECIFIED:0};Kt[Kt.VIDEO_STREAM_TYPE_VOD]="VIDEO_STREAM_TYPE_VOD";Kt[Kt.VIDEO_STREAM_TYPE_DVR]="VIDEO_STREAM_TYPE_DVR";Kt[Kt.VIDEO_STREAM_TYPE_LIVE]="VIDEO_STREAM_TYPE_LIVE";Kt[Kt.VIDEO_STREAM_TYPE_UNSPECIFIED]="VIDEO_STREAM_TYPE_UNSPECIFIED";
var Lt={YT_IDB_TRANSACTION_TYPE_READ:2,YT_IDB_TRANSACTION_TYPE_WRITE:1,YT_IDB_TRANSACTION_TYPE_UNKNOWN:0};Lt[Lt.YT_IDB_TRANSACTION_TYPE_READ]="YT_IDB_TRANSACTION_TYPE_READ";Lt[Lt.YT_IDB_TRANSACTION_TYPE_WRITE]="YT_IDB_TRANSACTION_TYPE_WRITE";Lt[Lt.YT_IDB_TRANSACTION_TYPE_UNKNOWN]="YT_IDB_TRANSACTION_TYPE_UNKNOWN";var Mt={PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN:2,PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT:1,PLAYER_ROTATION_TYPE_UNKNOWN:0};Mt[Mt.PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN]="PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN";
Mt[Mt.PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT]="PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT";Mt[Mt.PLAYER_ROTATION_TYPE_UNKNOWN]="PLAYER_ROTATION_TYPE_UNKNOWN";var Nt="actionVisualElement spinnerInfo resourceInfo playerInfo commentInfo mdxInfo watchInfo thumbnailLoadInfo creatorInfo unpluggedInfo reelInfo subscriptionsFeedInfo requestIds mediaBrowserActionInfo musicLoadActionInfo shoppingInfo webViewInfo prefetchInfo accelerationSession commerceInfo webInfo tvInfo kabukiInfo mwebInfo musicInfo".split(" ");var Ot=y.ytLoggingLatencyUsageStats_||{};A("ytLoggingLatencyUsageStats_",Ot);function Pt(){this.i=0}
function Qt(){Pt.i||(Pt.i=new Pt);return Pt.i}
Pt.prototype.tick=function(a,b,c,d){Rt(this,"tick_"+a+"_"+b)||(c={timestamp:c,cttAuthInfo:d},M("web_csi_via_jspb")?(d=new Fj,D(d,1,a),D(d,2,b),a=new Ij,Ud(a,Fj,5,Jj,d),Yq(a,c)):lm("latencyActionTicked",{tickName:a,clientActionNonce:b},c))};
Pt.prototype.info=function(a,b,c){var d=Object.keys(a).join("");Rt(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,lm("latencyActionInfo",a,{cttAuthInfo:c}))};
Pt.prototype.jspbInfo=function(a,b,c){for(var d="",e=0;e<a.toJSON().length;e++)void 0!==a.toJSON()[e]&&(d=0===e?d.concat(""+e):d.concat("_"+e));Rt(this,"info_"+d+"_"+b)||(D(a,2,b),b={cttAuthInfo:c},c=new Ij,Ud(c,Bj,7,Jj,a),Yq(c,b))};
Pt.prototype.span=function(a,b,c){var d=Object.keys(a).join("");Rt(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,lm("latencyActionSpan",a,{cttAuthInfo:c}))};
function Rt(a,b){Ot[b]=Ot[b]||{count:0};var c=Ot[b];c.count++;c.time=P();a.i||(a.i=Wl(function(){var d=P(),e;for(e in Ot)Ot[e]&&6E4<d-Ot[e].time&&delete Ot[e];a&&(a.i=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new R("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||yr(c)),!0):!1}
;function St(){var a=["ol"];vt("").info.actionType="embed";a&&uk("TIMING_AFT_KEYS",a);uk("TIMING_ACTION","embed");if(M("web_csi_via_jspb")){a=L("TIMING_INFO",{});var b=new Bj;a=p(Object.entries(a));for(var c=a.next();!c.done;c=a.next()){var d=p(c.value);c=d.next().value;d=d.next().value;switch(c){case "GetBrowse_rid":var e=new Ej;D(e,1,c);D(e,2,String(d));Dj(b,e);break;case "GetGuide_rid":e=new Ej;D(e,1,c);D(e,2,String(d));Dj(b,e);break;case "GetHome_rid":e=new Ej;D(e,1,c);D(e,2,String(d));Dj(b,e);
break;case "GetPlayer_rid":e=new Ej;D(e,1,c);D(e,2,String(d));Dj(b,e);break;case "GetSearch_rid":e=new Ej;D(e,1,c);D(e,2,String(d));Dj(b,e);break;case "GetSettings_rid":e=new Ej;D(e,1,c);D(e,2,String(d));Dj(b,e);break;case "GetTrending_rid":e=new Ej;D(e,1,c);D(e,2,String(d));Dj(b,e);break;case "GetWatchNext_rid":e=new Ej;D(e,1,c);D(e,2,String(d));Dj(b,e);break;case "yt_red":D(b,14,!!d);break;case "yt_ad":D(b,9,!!d)}}Tt(b);b=new Bj;b=D(b,25,!0);b=D(b,1,W[Dt(L("TIMING_ACTION"))]);(a=L("PREVIOUS_ACTION"))&&
D(b,13,W[Dt(a)]);(a=L("CLIENT_PROTOCOL"))&&D(b,33,a);(a=L("CLIENT_TRANSPORT"))&&D(b,34,a);(a=Qr())&&"UNDEFINED_CSN"!==a&&D(b,4,a);a=Ut();1!==a&&-1!==a||D(b,6,!0);a=kt();if(M("skip_setting_info_in_csi_data_object"))lt();else{d=pt();c=[];for(e=0;e<d.length;e++){var f=c,g=f.push;var h=d[e];var k=Bj;if(null==h||""==h)k=new k;else{h=JSON.parse(h);if(!Array.isArray(h))throw Error(void 0);$d=h=wd(h);k=new k(h);$d=null}g.call(f,k)}for(d=0;d<c.length&&"cold"!==Yd(Md(c[d],3),"");d++);}D(b,3,"cold");Vt(a);a=
Wt();if(0<a.length)for(a=p(a),c=a.next();!c.done;c=a.next())c=c.value,d=new Aj,D(d,1,c),Wd(b,83,Aj,d);Tt(b)}else{a=L("TIMING_INFO",{});for(b in a)a.hasOwnProperty(b)&&Xt(b,a[b]);b={isNavigation:!0,actionType:Dt(L("TIMING_ACTION"))};if(a=L("PREVIOUS_ACTION"))b.previousAction=Dt(a);if(a=L("CLIENT_PROTOCOL"))b.httpProtocol=a;if(a=L("CLIENT_TRANSPORT"))b.transportProtocol=a;(a=Qr())&&"UNDEFINED_CSN"!==a&&(b.clientScreenNonce=a);a=Ut();if(1===a||-1===a)b.isVisible=!0;M("skip_setting_info_in_csi_data_object")?
lt():kt();b.loadType="cold";Vt(kt());a=Wt();if(0<a.length)for(b.resourceInfo=[],a=p(a),c=a.next();!c.done;c=a.next())b.resourceInfo.push({resourceCache:c.value});Yt(b)}b=kt();a=ot();if(!(M("skip_setting_info_in_csi_data_object")&&"cold"!==lt().loadType||"cold"!==b.yt_lt&&"cold"!==a.loadType)){c=mt();d=nt();d=d.gelTicks?d.gelTicks:d.gelTicks={};for(var m in c)if(!(m in d))if("number"===typeof c[m])Z(m,et(m));else if(M("log_repeated_ytcsi_ticks"))for(e=p(c[m]),f=e.next();!f.done;f=e.next())Z(m.slice(1),
f.value);m={};c=!1;d=p(Object.keys(b));for(e=d.next();!e.done;e=d.next())e=e.value,(e=Et(e,b[e]))&&!st(ot(),e)&&(Ts(a,e),Ts(m,e),c=!0);c&&Yt(m)}A("ytglobal.timingready_",!0);m=L("TIMING_ACTION");B("ytglobal.timingready_")&&m&&"_start"in mt()&&dt()&&rt()}
function Xt(a,b,c,d){if(null!==b){var e=kt(c);M("skip_setting_info_in_csi_data_object")?"yt_lt"===a&&(e="string"===typeof b?b:""+b,lt(c).loadType=e):e[a]=b;(a=Et(a,b,c))&&Yt(a,c,d)}}
function Yt(a,b,c){if(!M("web_csi_via_jspb")||(void 0===c?0:c))c=vt(b||""),Ts(c.info,a),M("skip_setting_info_in_csi_data_object")&&a.loadType&&(c=a.loadType,lt(b).loadType=c),Ts(ot(b),a),c=qt(b),b=jt(b).cttAuthInfo,Qt().info(a,c,b);else{c=new Bj;var d=Object.keys(a);a=Object.values(a);for(var e=0;e<d.length;e++){var f=d[e];try{switch(f){case "actionType":D(c,1,W[a[e]]);break;case "clientActionNonce":D(c,2,a[e]);break;case "clientScreenNonce":D(c,4,a[e]);break;case "loadType":D(c,3,a[e]);break;case "isPrewarmedLaunch":D(c,
92,a[e]);break;case "isFirstInstall":D(c,55,a[e]);break;case "networkType":D(c,5,Ft[a[e]]);break;case "connectionType":D(c,26,X[a[e]]);break;case "detailedConnectionType":D(c,27,Y[a[e]]);break;case "isVisible":D(c,6,a[e]);break;case "playerType":D(c,7,Gt[a[e]]);break;case "clientPlaybackNonce":D(c,8,a[e]);break;case "adClientPlaybackNonce":D(c,28,a[e]);break;case "previousCpn":D(c,77,a[e]);break;case "targetCpn":D(c,76,a[e]);break;case "isMonetized":D(c,9,a[e]);break;case "isPrerollAllowed":D(c,16,
a[e]);break;case "isPrerollShown":D(c,17,a[e]);break;case "adType":D(c,12,a[e]);break;case "adTypesAllowed":D(c,36,a[e]);break;case "adNetworks":D(c,37,a[e]);break;case "previousAction":D(c,13,W[a[e]]);break;case "isRedSubscriber":D(c,14,a[e]);break;case "serverTimeMs":D(c,15,a[e]);break;case "videoId":c.setVideoId(a[e]);break;case "adVideoId":D(c,20,a[e]);break;case "targetVideoId":D(c,78,a[e]);break;case "adBreakType":D(c,21,Ht[a[e]]);break;case "isNavigation":D(c,25,a[e]);break;case "viewportHeight":D(c,
29,a[e]);break;case "viewportWidth":D(c,30,a[e]);break;case "screenHeight":D(c,84,a[e]);break;case "screenWidth":D(c,85,a[e]);break;case "browseId":D(c,31,a[e]);break;case "isCacheHit":D(c,32,a[e]);break;case "httpProtocol":D(c,33,a[e]);break;case "transportProtocol":D(c,34,a[e]);break;case "searchQuery":D(c,41,a[e]);break;case "isContinuation":D(c,42,a[e]);break;case "availableProcessors":D(c,43,a[e]);break;case "sdk":D(c,44,a[e]);break;case "isLocalStream":D(c,45,a[e]);break;case "navigationRequestedSameUrl":D(c,
64,a[e]);break;case "shellStartupDurationMs":D(c,70,a[e]);break;case "appInstallDataAgeMs":D(c,73,a[e]);break;case "latencyActionError":D(c,71,It[a[e]]);break;case "actionStep":D(c,79,a[e]);break;case "jsHeapSizeLimit":D(c,80,a[e]);break;case "totalJsHeapSize":D(c,81,a[e]);break;case "usedJsHeapSize":D(c,82,a[e]);break;case "sourceVideoDurationMs":D(c,90,a[e]);break;case "videoOutputFrames":D(c,93,a[e]);break;case "isResume":D(c,104,a[e]);break;case "adPrebufferedTimeSecs":D(c,39,a[e]);break;case "isLivestream":D(c,
47,a[e]);break;case "liveStreamMode":D(c,91,Jt[a[e]]);break;case "adCpn2":D(c,48,a[e]);break;case "adDaiDriftMillis":D(c,49,a[e]);break;case "videoStreamType":D(c,53,Kt[a[e]]);break;case "playbackRequiresTap":D(c,56,a[e]);break;case "performanceNavigationTiming":D(c,67,a[e]);break;case "transactionType":D(c,74,Lt[a[e]]);break;case "playerRotationType":D(c,101,Mt[a[e]]);break;case "allowedPreroll":D(c,10,a[e]);break;case "shownPreroll":D(c,11,a[e]);break;case "getHomeRequestId":D(c,57,a[e]);break;
case "getSearchRequestId":D(c,60,a[e]);break;case "getPlayerRequestId":D(c,61,a[e]);break;case "getWatchNextRequestId":D(c,62,a[e]);break;case "getBrowseRequestId":D(c,63,a[e]);break;case "getLibraryRequestId":D(c,66,a[e]);break;default:Nt.includes(f)&&Dk(new R("Codegen laipb translator asked to translate message field",""+f))}}catch(g){Dk(Error("Codegen laipb translator failed to set "+f))}}Tt(c,b)}}
function Tt(a,b){if(M("skip_setting_info_in_csi_data_object")){var c=Yd(Md(a,3),"");c&&(lt(b).loadType=c)}else pt(b).push(ae(a));vt(b||"").jspbInfo.push(a);c=qt(b);b=jt(b).cttAuthInfo;Qt().jspbInfo(a,c,b)}
function Z(a,b,c){if(!b&&"_"!==a[0]){var d=a;S.mark&&(0==d.lastIndexOf("mark_",0)||(d="mark_"+d),c&&(d+=" ("+c+")"),S.mark(d))}d=vt(c||"");d.tick[a]=b||P();if(d.callback&&d.callback[a]){d=p(d.callback[a]);for(var e=d.next();!e.done;e=d.next())e=e.value,e()}d=nt(c);d.gelTicks&&(d.gelTicks[a]=!0);e=mt(c);d=b||P();M("log_repeated_ytcsi_ticks")?a in e||(e[a]=d):e[a]=d;e=qt(c);var f=jt(c).cttAuthInfo;"_start"===a?(a=Qt(),Rt(a,"baseline_"+e)||(b={timestamp:b,cttAuthInfo:f},M("web_csi_via_jspb")?(a=new zj,
D(a,1,e),e=new Ij,Ud(e,zj,6,Jj,a),Yq(e,b)):lm("latencyActionBaselined",{clientActionNonce:e},b))):Qt().tick(a,e,b,f);rt(c);return d}
function Zt(){var a=qt();requestAnimationFrame(function(){setTimeout(function(){a===qt()&&Z("ol",void 0,void 0)},0)})}
function Ut(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Gp+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Vt(a){var b=ft(),c=ht(),d=L("CSI_START_TIMESTAMP_MILLIS",0);0<d&&!M("embeds_web_enable_csi_start_override_killswitch")&&(c=d);c&&(Z("srt",b.responseStart),1!==a.prerender&&Z("_start",c,void 0));a=tt();0<a&&Z("fpt",a);a=ft();a.isPerformanceNavigationTiming&&Yt({performanceNavigationTiming:!0});Z("nreqs",a.requestStart,void 0);Z("nress",a.responseStart,void 0);Z("nrese",a.responseEnd,void 0);0<a.redirectEnd-a.redirectStart&&(Z("nrs",a.redirectStart,void 0),Z("nre",a.redirectEnd,void 0));0<
a.domainLookupEnd-a.domainLookupStart&&(Z("ndnss",a.domainLookupStart,void 0),Z("ndnse",a.domainLookupEnd,void 0));0<a.connectEnd-a.connectStart&&(Z("ntcps",a.connectStart,void 0),Z("ntcpe",a.connectEnd,void 0));a.secureConnectionStart>=ht()&&0<a.connectEnd-a.secureConnectionStart&&(Z("nstcps",a.secureConnectionStart,void 0),Z("ntcpe",a.connectEnd,void 0));S&&"getEntriesByType"in S&&$t()}
function au(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);ic()&&a.setAttribute("nonce",ic());return c?(a=S.getEntriesByName(c))&&a[0]&&(a=a[0],c=ht(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Wt(){var a=[];if(document.querySelector&&S&&S.getEntriesByName)for(var b in ct)if(ct.hasOwnProperty(b)){var c=ct[b];au(b,c)&&a.push(c)}return a}
function $t(){var a=window.location.protocol,b=S.getEntriesByType("resource");b=gb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=ib(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",gt(b.startTime)),Z("wffe",gt(b.responseEnd)))}
var bu=window;bu.ytcsi&&(bu.ytcsi.info=Xt,bu.ytcsi.tick=Z);var cu="tokens consistency mss client_location entities response_received_commands store PLAYER_PRELOAD".split(" "),du=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function eu(a,b,c,d){this.o=a;this.M=b;this.m=c;this.l=d;this.j=void 0;this.i=new Map;a.Pa||(a.Pa={});a.Pa=Object.assign({},Ss,a.Pa)}
function fu(a,b,c,d){if(void 0!==eu.i){if(d=eu.i,a=[a!==d.o,b!==d.M,c!==d.m,!1,!1,void 0!==d.j],a.some(function(e){return e}))throw new R("InnerTubeTransportService is already initialized",a);
}else eu.i=new eu(a,b,c,d)}
function gu(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?ss:c;var d=Bs(b,a.o);if(!d)return wf(new R("Error: No request builder found for command.",b));var e=d.o(b,void 0,c);return e?new rf(function(f){var g,h,k;return x(function(m){if(1==m.i){h="cors"===(null==(g=e.za)?void 0:g.mode)?"cors":void 0;if(a.m.wd){var q=e.config,r;q=null==q?void 0:null==(r=q.Ya)?void 0:r.sessionIndex;r=rs({sessionIndex:q});k=Object.assign({},hu(h),r);return m.B(2)}return v(m,iu(e.config,
h),3)}2!=m.i&&(k=m.j);f(ju(a,e,k));m.i=0})}):wf(new R("Error: Failed to build request for command.",b))}
function ku(a,b,c){var d;if(b&&!(null==b?0:null==(d=b.Ar)?0:d.Dr)&&a.l){d=p(cu);for(var e=d.next();!e.done;e=d.next())e=e.value,a.l[e]&&a.l[e].handleResponse(b,c)}}
function ju(a,b,c){var d,e,f,g,h,k,m,q,r,w,t,z,E,F,O,N,Q,da,U,mb,Wa,ma,H,la,fa,ue,ve,pd;return x(function(oa){switch(oa.i){case 1:oa.B(2);break;case 3:if((d=oa.j)&&!d.isExpired())return oa.return(Promise.resolve(d.i()));case 2:if(null==(e=b)?0:null==(f=e.ha)?0:f.context)for(g=p([]),h=g.next();!h.done;h=g.next())k=h.value,k.wr(b.ha.context);if(null==(m=a.j)||!m.Br(b.input,b.ha)){oa.B(4);break}return v(oa,a.j.qr(b.input,b.ha),5);case 5:return q=oa.j,M("kevlar_process_local_innertube_responses_killswitch")||
ku(a,q,b),oa.return(q);case 4:return(t=null==(w=b.config)?void 0:w.Fa)&&a.i.has(t)&&M("web_memoize_inflight_requests")?r=a.i.get(t):(z=JSON.stringify(b.ha),O=null!=(F=null==(E=b.za)?void 0:E.headers)?F:{},b.za=Object.assign({},b.za,{headers:Object.assign({},O,c)}),N=Object.assign({},b.za),"POST"===b.za.method&&(N=Object.assign({},N,{body:z})),(null==(Q=b.config)?0:Q.jd)&&Z(b.config.jd),da=function(){return a.M.fetch(b.input,N,b.config)},r=da(),t&&a.i.set(t,r)),v(oa,r,6);
case 6:U=oa.j;if(M("web_one_platform_error_handling")&&U&&"error"in U&&(null==(mb=U)?0:null==(Wa=mb.error)?0:Wa.details))for(ma=U.error.details,H=p(ma),la=H.next();!la.done;la=H.next())fa=la.value,(ue=fa["@type"])&&-1<du.indexOf(ue)&&(delete fa["@type"],U=fa);t&&a.i.has(t)&&a.i.delete(t);(null==(ve=b.config)?0:ve.kd)&&Z(b.config.kd);if(U||null==(pd=a.j)||!pd.hr(b.input,b.ha)){oa.B(7);break}return v(oa,a.j.pr(b.input,b.ha),8);case 8:U=oa.j;case 7:return ku(a,U,b),oa.return(U)}})}
function iu(a,b){var c,d,e,f;return x(function(g){if(1==g.i){e=null==(c=a)?void 0:null==(d=c.Ya)?void 0:d.sessionIndex;var h=rs({sessionIndex:e});if(!(h instanceof rf)){var k=new rf(cb);sf(k,2,h);h=k}return v(g,h,2)}f=g.j;return g.return(Promise.resolve(Object.assign({},hu(b),f)))})}
function hu(a){var b={"Content-Type":"application/json"};L("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=L("EOM_VISITOR_DATA"):L("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=L("VISITOR_DATA"));M("track_webfe_innertube_auth_mismatch")&&(b["X-Youtube-Bootstrap-Logged-In"]=L("LOGGED_IN",!1));"cors"!==a&&((a=L("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=L("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=L("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=
a),(a=L("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var lu=new Ds("INNERTUBE_TRANSPORT_TOKEN");var mu=["share/get_web_player_share_panel"],nu=["feedback"],ou=["notification/modify_channel_preference"],pu=["browse/edit_playlist"],qu=["subscription/subscribe"],ru=["subscription/unsubscribe"];function su(){}
u(su,Ps);su.prototype.l=function(){return qu};
su.prototype.i=function(a){return ds(a,ok)||void 0};
su.prototype.j=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
ea.Object.defineProperties(su.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function tu(){}
u(tu,Ps);tu.prototype.l=function(){return ru};
tu.prototype.i=function(a){return ds(a,nk)||void 0};
tu.prototype.j=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
ea.Object.defineProperties(tu.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function uu(){}
u(uu,Ps);uu.prototype.l=function(){return nu};
uu.prototype.i=function(a){return ds(a,Yi)||void 0};
uu.prototype.j=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
ea.Object.defineProperties(uu.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function vu(){}
u(vu,Ps);vu.prototype.l=function(){return ou};
vu.prototype.i=function(a){return ds(a,mk)||void 0};
vu.prototype.j=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function wu(){}
u(wu,Ps);wu.prototype.l=function(){return pu};
wu.prototype.i=function(a){return ds(a,lk)||void 0};
wu.prototype.j=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function xu(){}
u(xu,Ps);xu.prototype.l=function(){return mu};
xu.prototype.i=function(a){return ds(a,kk)};
xu.prototype.j=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var Fs=new Ds("NETWORK_SLI_TOKEN");function yu(a){this.i=a}
yu.prototype.fetch=function(a,b){var c=this,d,e;return x(function(f){c.i&&(d=mc(nc(5,Dc(a,"key")))||"/UNKNOWN_PATH",c.i.start(d));e=new window.Request(a,b);return M("web_fetch_promise_cleanup_killswitch")?f.return(Promise.resolve(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){yr(g)}))):f.return(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){yr(g)}))})};
yu.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.i&&this.i.success():(this.i&&this.i.failure(),b=b.then(function(c){yr(new R("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
yu[Cs]=[new Es];var zu=new Ds("NETWORK_MANAGER_TOKEN");var Au;function Bu(a){Sn.call(this,1,arguments);this.csn=a}
u(Bu,Sn);var ao=new Tn("screen-created",Bu),Cu=[],Eu=Du,Fu=0;function Gu(a,b,c,d,e,f,g){function h(){yr(new R("newScreen() parent element does not have a VE - rootVe",b))}
var k=Eu(),m=new Jr({veType:b,youtubeData:f,jspbYoutubeData:void 0});f={ba:k};e&&(f.cttAuthInfo=e);M("il_via_jspb")?(e=new oj,e.j(k),pj(e,m.getAsJspb()),c&&c.visualElement?(m=new qj,c.clientScreenNonce&&D(m,2,c.clientScreenNonce),rj(m,c.visualElement.getAsJspb()),g&&D(m,4,Kj[g]),G(e,qj,5,m)):c&&h(),d&&D(e,3,d),cr(e,f,a)):(e={csn:k,pageVe:m.getAsJson()},c&&c.visualElement?(e.implicitGesture={parentCsn:c.clientScreenNonce,gesturedVe:c.visualElement.getAsJson()},g&&(e.implicitGesture.gestureType=g)):
c&&h(),d&&(e.cloneCsn=d),a?Tq("screenCreated",e,a,f):lm("screenCreated",e,f));Yn(ao,new Bu(k));return k}
function Hu(a,b,c,d){var e=d.filter(function(k){k.csn!==b?(k.csn=b,k=!0):k=!1;return k}),f={cttAuthInfo:Sr(b)||void 0,
ba:b};d=p(d);for(var g=d.next();!g.done;g=d.next())g=g.value.getAsJson(),(rb(g)||!g.trackingParams&&!g.veType)&&yr(Error("Child VE logged with no data"));if(M("il_via_jspb")){var h=new sj;h.j(b);uj(h,c.getAsJspb());hb(e,function(k){k=k.getAsJspb();Wd(h,3,mj,k)});
"UNDEFINED_CSN"===b?Iu("visualElementAttached",f,void 0,h):dr(h,f,a)}else c={csn:b,parentVe:c.getAsJson(),childVes:hb(e,function(k){return k.getAsJson()})},"UNDEFINED_CSN"===b?Iu("visualElementAttached",f,c):a?Tq("visualElementAttached",c,a,f):lm("visualElementAttached",c,f)}
function Du(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return dd(b,3)}
function Iu(a,b,c,d){Cu.push({payloadName:a,payload:c,xa:d,options:b});Fu||(Fu=bo())}
function co(a){if(Cu){for(var b=p(Cu),c=b.next();!c.done;c=b.next())if(c=c.value,c.payload)if(M("il_via_jspb"))switch(c.xa.j(a.csn),c.payloadName){case "screenCreated":cr(c.xa,c.options);break;case "visualElementAttached":dr(c.xa,c.options);break;case "visualElementShown":Zq(c.xa,c.options);break;case "visualElementHidden":$q(c.xa,c.options);break;case "visualElementGestured":ar(c.xa,c.options);break;case "visualElementStateChanged":br(c.xa,c.options);break;default:yr(new R("flushQueue unable to map payloadName to JSPB setter"))}else c.payload.csn=
a.csn,Tq(c.payloadName,c.payload,null,c.options);Cu.length=0}Fu=0}
;var Ju={};function Ku(){this.j=new Set;this.i=new Set;this.l=new Map}
Ku.prototype.nb=function(a){M("use_ts_visibilitylogger")&&(0,Ju.nb)(a)};
function Lu(a){M("use_ts_visibilitylogger")?Lu(Ju):a.clear()}
Ku.prototype.clear=function(){M("use_ts_visibilitylogger")?(0,Ju.clear)():(this.j.clear(),this.i.clear(),this.l.clear())};
Na(Ku);function Mu(){this.o=[];this.C=[];this.i=[];this.m=[];this.s=[];this.j=new Set;this.O=new Map}
Mu.prototype.nb=function(a){this.client=a};
function Nu(a,b,c){c=void 0===c?0:c;b.then(function(d){a.j.has(c)&&a.l&&a.l();var e=Qr(c),f=Or(c);if(e&&f){var g;(null==d?0:null==(g=d.response)?0:g.trackingParams)&&Hu(a.client,e,f,[Kr(d.response.trackingParams)]);var h;(null==d?0:null==(h=d.playerResponse)?0:h.trackingParams)&&Hu(a.client,e,f,[Kr(d.playerResponse.trackingParams)])}})}
function Ou(a,b,c,d){d=void 0===d?0:d;if(a.j.has(d))a.o.push([b,c]);else{var e=Qr(d);c=c||Or(d);e&&c&&Hu(a.client,e,c,[b])}}
Mu.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=Qr(void 0===c?0:c)){a=this.client;var e=Kr(d);d={cttAuthInfo:Sr(c)||void 0,ba:c};M("il_via_jspb")?(b=new vj,b.j(c),e=e.getAsJspb(),G(b,mj,2,e),D(b,4,Kj.INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK),"UNDEFINED_CSN"===c?Iu("visualElementGestured",d,void 0,b):ar(b,d,a)):(e={csn:c,ve:e.getAsJson(),gestureType:"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK"},b&&(e.clientData=b),"UNDEFINED_CSN"===c?Iu("visualElementGestured",
d,e):a?Tq("visualElementGestured",e,a,d):lm("visualElementGestured",e,d));b=!0}else b=!1;else b=!1;return b};
function Pu(a,b,c){c=void 0===c?{}:c;a.j.add(c.layer||0);a.l=function(){Qu(a,b,c);var f=Or(c.layer);if(f){for(var g=p(a.o),h=g.next();!h.done;h=g.next())h=h.value,Ou(a,h[0],h[1]||f,c.layer);f=p(a.C);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=Qr(g);var m=k[0]||Or(g);if(h&&m){g=a.client;var q=k[1];k={cttAuthInfo:Sr(h)||void 0,ba:h};M("il_via_jspb")?(q=new yj,q.j(h),m=m.getAsJspb(),G(q,mj,2,m),"UNDEFINED_CSN"===h?Iu("visualElementStateChanged",k,void 0,q):br(q,k,g)):
(m={csn:h,ve:m.getAsJson(),clientData:q},"UNDEFINED_CSN"===h?Iu("visualElementStateChanged",k,m):g?Tq("visualElementStateChanged",m,g,k):lm("visualElementStateChanged",m,k))}}}};
Qr(c.layer)||a.l();if(c.Zb)for(var d=p(c.Zb),e=d.next();!e.done;e=d.next())Nu(a,e.value,c.layer);else xr(Error("Delayed screen needs a data promise."))}
function Qu(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.dd?c.dd:c.layer;var e=Qr(d);d=Or(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=L("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=Gu(a.client,b,f,c.Yb,c.cttAuthInfo,g,c.lr)}catch(m){Ar(m,{yr:b,rootVe:d,parentVisualElement:void 0,ir:e,vr:f,Yb:c.Yb});xr(m);return}Tr(k,b,
c.layer,c.cttAuthInfo);if(b=e&&"UNDEFINED_CSN"!==e&&d){a:{b=p(Object.values(Ir));for(f=b.next();!f.done;f=b.next())if(Qr(f.value)===e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,g=!0,h=(g=void 0===g?!1:g)?16:8,f={cttAuthInfo:Sr(e)||void 0,ba:e,ac:g},M("il_via_jspb")?(h=new wj,h.j(e),d=d.getAsJspb(),G(h,mj,2,d),D(h,4,g?16:8),"UNDEFINED_CSN"===e?Iu("visualElementHidden",f,void 0,h):$q(h,f,b)):(d={csn:e,ve:d.getAsJson(),eventType:h},"UNDEFINED_CSN"===e?Iu("visualElementHidden",f,d):b?Tq("visualElementHidden",
d,b,f):lm("visualElementHidden",d,f)));a.i[a.i.length-1]&&!a.i[a.i.length-1].csn&&(a.i[a.i.length-1].csn=k||"");Yt({clientScreenNonce:k});Lu(Ku.getInstance());d=Or(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(M("web_mark_root_visible")||M("music_web_mark_root_visible"))&&(e=k,k={cttAuthInfo:Sr(e)||void 0,ba:e},M("il_via_jspb")?(b=new xj,b.j(e),f=d.getAsJspb(),G(b,mj,2,f),D(b,4,1),"UNDEFINED_CSN"===e?Iu("visualElementShown",k,void 0,b):Zq(b,k)):(b={csn:e,ve:d.getAsJson(),eventType:1},"UNDEFINED_CSN"===e?Iu("visualElementShown",
k,b):lm("visualElementShown",b,k)));a.j.delete(c.layer||0);a.l=void 0;e=p(a.O);for(k=e.next();!k.done;k=e.next())b=p(k.value),k=b.next().value,b=b.next().value,b.has(c.layer)&&d&&Ou(a,k,d,c.layer);for(c=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(m){xr(m)}}for(c=a.m.length=0;c<a.s.length;c++){e=a.s[c];try{e()}catch(m){xr(m)}}}
;function Ru(){var a,b,c;return x(function(d){if(1==d.i)return a=Ks().resolve(lu),a?v(d,gu(a),2):(yr(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.j){if(b.errorMetadata)return yr(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.jr;return d.return(c)}yr(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;var Su=y.caches,Tu;function Uu(a){var b=a.indexOf(":");return-1===b?{nc:a}:{nc:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Vu(){return x(function(a){if(void 0!==Tu)return a.return(Tu);Tu=new Promise(function(b){var c;return x(function(d){switch(d.i){case 1:return ya(d,2),v(d,Su.open("test-only"),4);case 4:return v(d,Su.delete("test-only"),5);case 5:za(d,3);break;case 2:if(c=Aa(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.i=0}})});
return a.return(Tu)})}
function Wu(a){var b,c,d,e,f,g,h;x(function(k){if(1==k.i)return v(k,Vu(),2);if(3!=k.i){if(!k.j)return k.return(!1);b=[];return v(k,Su.keys(),3)}c=k.j;d=p(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Uu(f),h=g.datasyncId,!h||a.includes(h)||b.push(Su.delete(f));return k.return(Promise.all(b).then(function(m){return m.some(function(q){return q})}))})}
function Xu(){var a,b,c,d,e,f,g;return x(function(h){if(1==h.i)return v(h,Vu(),2);if(3!=h.i){if(!h.j)return h.return(!1);a=pm("cache contains other");return v(h,Su.keys(),3)}b=h.j;c=p(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Uu(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Yu(){try{return!!self.localStorage}catch(a){return!1}}
;function Zu(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function $u(a){if(Yu()){var b=Object.keys(window.localStorage);b=p(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Zu(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function av(){if(!Yu())return!1;var a=pm(),b=Object.keys(window.localStorage);b=p(b);for(var c=b.next();!c.done;c=b.next())if(c=Zu(c.value),void 0!==c&&c!==a)return!0;return!1}
;function bv(){Ru().then(function(a){a&&(zn(a),Wu(a),$u(a))})}
function cv(){var a=new Io;Qh.V(function(){var b,c,d,e;return x(function(f){switch(f.i){case 1:if(M("ytidb_clear_optimizations_killswitch")){f.B(2);break}b=pm("clear");if(b.startsWith("V")){var g=[b];zn(g);Wu(g);$u(g);return f.return()}c=av();return v(f,Xu(),3);case 3:return d=f.j,v(f,An(),4);case 4:if(e=f.j,!c&&!d&&!e)return f.return();case 2:a.W()?bv():a.m.add("publicytnetworkstatus-online",bv,!0,void 0,void 0),f.i=0}})})}
;function dv(a){a&&(a.dataset?a.dataset[ev("loaded")]="true":a.setAttribute("data-loaded","true"))}
function fv(a,b){return a?a.dataset?a.dataset[ev(b)]:a.getAttribute("data-"+b):null}
var gv={};function ev(a){return gv[a]||(gv[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var hv=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,iv=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function jv(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(hv,""),c=c.replace(iv,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else kv(a,b,c)}
function kv(a,b,c){c=void 0===c?null:c;var d=lv(a),e=document.getElementById(d),f=e&&fv(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=$p(d,b),b=""+Ra(b),mv[b]=f),g||(e=nv(a,d,function(){fv(e,"loaded")||(dv(e),cq(d),Xk(Ya(dq,d),0))},c)))}
function nv(a,b,c,d){d=void 0===d?null:d;var e=cf("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);zh(e,Lb(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function ov(a){a=lv(a);var b=document.getElementById(a);b&&(dq(a),b.parentNode.removeChild(b))}
function pv(a,b){a&&b&&(a=""+Ra(b),(a=mv[a])&&bq(a))}
function lv(a){var b=document.createElement("a");fc(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+kc(a)}
var mv={};var qv=[],rv=!1;function sv(){if(!M("disable_biscotti_fetch_for_ad_blocker_detection")&&!M("disable_biscotti_fetch_entirely_for_all_web_clients")&&fs()){var a=L("PLAYER_VARS",{});if("1"!=tb(a)&&!gs(a)){var b=function(){rv=!0;"google_ad_status"in window?uk("DCLKSTAT",1):uk("DCLKSTAT",2)};
try{jv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}qv.push(Qh.V(function(){if(!(rv||"google_ad_status"in window)){try{pv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}rv=!0;uk("DCLKSTAT",3)}},5E3))}}}
function tv(){var a=Number(L("DCLKSTAT",0));return isNaN(a)?0:a}
;function uv(){this.state=1;this.i=null}
l=uv.prototype;
l.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterScript)?d:null,f;d=null!=(f=a.interpreterUrl)?f:null;a.interpreterSafeScript&&(e=a.interpreterSafeScript,Db("From proto message. b/166824318"),e=e.privateDoNotAccessOrElseSafeScriptWrappedValue||"",e=(f=Ab())?f.createScript(e):e,e=(new Hb(e)).toString());a.interpreterSafeUrl&&(d=a.interpreterSafeUrl,Db("From proto message. b/166824318"),d=Lb(d.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());xv(this,e,
d,a.program,b,c)}else yr(Error("Cannot initialize botguard without program"))};
function xv(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,jv(c,function(){window[g]?yv(a,d,g,e):(a.state=3,ov(c),yr(new R("Unable to load Botguard","from "+c)))},f)):b?(f=cf("SCRIPT"),f.textContent=b,f.nonce=ic(),document.head.appendChild(f),document.head.removeChild(f),window[g]?yv(a,d,g,e):(a.state=4,yr(new R("Unable to load Botguard from JS")))):yr(new R("Unable to load VM; no url or JS provided"))}
l.isInitialized=function(){return!!this.zb()};
function yv(a,b,c,d){a.state=5;try{var e=new vh({program:b,globalName:c,gd:M("att_web_record_metrics")});e.td.then(function(){a.state=6;d&&d(b)});
a.Kb(e)}catch(f){a.state=7,f instanceof Error&&yr(f)}}
l.invoke=function(a){a=void 0===a?{}:a;var b=this.zb();if(b){var c={Xb:a};if(b.eb)throw Error("Already disposed");a=th();var d;null!=(d=b.wa)&&d.j.i.Mb("/client_streamz/bg/fsc",d.Fa);d=b.xd([c.Xb,c.vd]);null!=(b=b.wa)&&(a=th()-a,b.l.i.pb("/client_streamz/bg/fsl",a,b.Fa));b=d}else b=null;return b};
l.dispose=function(){this.Nb()};
l.Nb=function(){this.Kb(null);this.state=8};
l.zb=function(){return this.i};
l.Kb=function(a){ie(this.i);this.i=a};function zv(){uv.apply(this,arguments)}
u(zv,uv);zv.prototype.Nb=function(){this.state=8};
zv.prototype.zb=function(){return B("yt.abuse.playerAttLoader")};
zv.prototype.Kb=function(a){ie(B("yt.abuse.playerAttLoader"));A("yt.abuse.playerAttLoader",a);a&&A("yt.abuse.playerAttLoaderRun",function(b){return a.snapshot(b)})};var Av=new zv;var Bv=new uv;function Cv(){return M("use_player_abuse_bg_library")?Av.isInitialized():Bv.isInitialized()}
function Dv(a){a=void 0===a?{}:a;M("use_player_abuse_bg_library")?(a=void 0===a?{}:a,a=Av.invoke(a)):a=Bv.invoke(a);return a}
;function Ev(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?am():d;this.m=c;this.l=d;this.j=new uh;this.i=a;a={};c=p(this.i.entries());for(d=c.next();!d.done;a={Ha:a.Ha,Ra:a.Ra},d=c.next()){var e=p(d.value);d=e.next().value;e=e.next().value;a.Ra=d;a.Ha=e;d=function(f){return function(){f.Ha.Cb();b.i[f.Ra].kb=!0;b.i.every(function(g){return!0===g.kb})&&b.j.resolve()}}(a);
e=Xl(d,Fv(this,a.Ha));this.i[a.Ra]=Object.assign({},a.Ha,{Cb:d,jobId:e})}}
function Gv(a){var b=Array.from(a.i.keys()).sort(function(d,e){return Fv(a,a.i[e])-Fv(a,a.i[d])});
b=p(b);for(var c=b.next();!c.done;c=b.next())c=a.i[c.value],void 0===c.jobId||c.kb||(a.l.ga(c.jobId),Xl(c.Cb,10))}
Ev.prototype.cancel=function(){for(var a=p(this.i),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.kb||this.l.ga(b.jobId),b.kb=!0;this.j.resolve()};
function Fv(a,b){var c;return null!=(c=b.priority)?c:a.m}
;function Hv(a){this.state=a;this.plugins=[];this.s=void 0}
Hv.prototype.install=function(){this.plugins.push.apply(this.plugins,ia(Ja.apply(0,arguments)))};
Hv.prototype.uninstall=function(){var a=this;Ja.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);-1<b&&a.plugins.splice(b,1)})};
Hv.prototype.transition=function(a,b){var c=this,d=this.C.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.F===a}):f.from===c.state&&f.F===a});
if(d){this.l&&(Gv(this.l),this.l=void 0);this.state=a;d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Iv(this,e,this.s),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Iv(a,b,c){return function(){var d=Ja.apply(0,arguments),e=b.filter(function(k){var m;return 10===(null!=(m=null!=c?c:k.priority)?m:0)}),f=b.filter(function(k){var m;
return 10!==(null!=(m=null!=c?c:k.priority)?m:0)});
am();var g={};e=p(e);for(var h=e.next();!h.done;g={Sa:g.Sa},h=e.next())g.Sa=h.value,Zl(function(k){return function(){k.Sa.callback.apply(k.Sa,ia(d))}}(g));
f=f.map(function(k){var m;return{Cb:function(){k.callback.apply(k,ia(d))},
priority:null!=(m=null!=c?c:k.priority)?m:0}});
f.length&&(a.l=new Ev(f))}}
ea.Object.defineProperties(Hv.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function Jv(a){Hv.call(this,void 0===a?"document_active":a);var b=this;this.s=10;this.i=new Map;this.C=[{from:"document_active",F:"document_disposed_preventable",action:this.O},{from:"document_active",F:"document_disposed",action:this.m},{from:"document_disposed_preventable",F:"document_disposed",action:this.m},{from:"document_disposed_preventable",F:"flush_logs",action:this.o},{from:"document_disposed_preventable",F:"document_active",action:this.j},{from:"document_disposed",F:"flush_logs",action:this.o},
{from:"document_disposed",F:"document_active",action:this.j},{from:"document_disposed",F:"document_disposed",action:function(){}},
{from:"flush_logs",F:"document_active",action:this.j}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
u(Jv,Hv);Jv.prototype.O=function(a,b){if(!this.i.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.i=new Map;this.transition("document_active");return}}this.i.set("document_disposed_preventable",!0);this.i.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Jv.prototype.m=function(a,b){this.i.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.i.set("document_disposed",!0),this.transition("flush_logs"))};
Jv.prototype.o=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
Jv.prototype.j=function(){this.i=new Map};function Kv(a){Hv.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.C=[{from:"document_visibility_unknown",F:"document_visible",action:this.j},{from:"document_visibility_unknown",F:"document_hidden",action:this.i},{from:"document_visibility_unknown",F:"document_foregrounded",action:this.o},{from:"document_visibility_unknown",F:"document_backgrounded",action:this.m},{from:"document_visible",F:"document_hidden",action:this.i},{from:"document_visible",F:"document_foregrounded",action:this.o},
{from:"document_visible",F:"document_visible",action:this.j},{from:"document_foregrounded",F:"document_visible",action:this.j},{from:"document_foregrounded",F:"document_hidden",action:this.i},{from:"document_foregrounded",F:"document_foregrounded",action:this.o},{from:"document_hidden",F:"document_visible",action:this.j},{from:"document_hidden",F:"document_backgrounded",action:this.m},{from:"document_hidden",F:"document_hidden",action:this.i},{from:"document_backgrounded",F:"document_hidden",action:this.i},
{from:"document_backgrounded",F:"document_backgrounded",action:this.m},{from:"document_backgrounded",F:"document_visible",action:this.j}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
M("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
u(Kv,Hv);Kv.prototype.j=function(a,b){a(null==b?void 0:b.event);M("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Kv.prototype.i=function(a,b){a(null==b?void 0:b.event);M("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Kv.prototype.m=function(a,b){a(null==b?void 0:b.event)};
Kv.prototype.o=function(a,b){a(null==b?void 0:b.event)};function Lv(){this.i=new Jv;this.j=new Kv}
Lv.prototype.install=function(){var a=Ja.apply(0,arguments);this.i.install.apply(this.i,ia(a));this.j.install.apply(this.j,ia(a))};function Mv(){Lv.call(this);var a={};this.install((a.document_disposed={callback:this.l},a));a={};this.install((a.flush_logs={callback:this.m},a))}
var Nv;u(Mv,Lv);Mv.prototype.m=function(){if(M("web_fp_via_jspb")){var a=new lj,b=Qr();b&&D(a,1,b);b=new Ij;Ud(b,lj,380,Jj,a);Yq(b);M("web_fp_via_jspb_and_json")&&lm("finalPayload",{csn:Qr()})}else lm("finalPayload",{csn:Qr()})};
Mv.prototype.l=function(){Cr(Dr)};function Ov(){}
Ov.getInstance=function(){var a=B("ytglobal.storage_");a||(a=new Ov,A("ytglobal.storage_",a));return a};
Ov.prototype.estimate=function(){var a,b,c;return x(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(Pv()):d.return()})};
function Pv(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
A("ytglobal.storageClass_",Ov);function jm(a,b){var c=this;this.handleError=a;this.i=b;this.j=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.j=!0});
this.l=Math.random()<=xk("ytidb_transaction_ended_event_rate_limit",.02)}
jm.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":M("idb_data_corrupted_killswitch")||this.i("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.i("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":M("idb_is_supported_completed_killswitch")||this.i("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":Qv(this,b);break;case "TRANSACTION_ENDED":this.l&&this.i("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,
{hasWindowUnloaded:this.j}),this.i("idbTransactionAborted",a)}};
function Qv(a,b){Ov.getInstance().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:Rv(null==c?void 0:c.usage),deviceStorageQuotaMbytes:Rv(null==c?void 0:c.quota)});a.i("idbQuotaExceeded",c)})}
function Rv(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function Sv(a,b,c){J.call(this);var d=this;c=c||L("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.l=b||null;this.targetOrigin="*";this.m=c;this.sessionId=null;this.channel="widget";this.H=!!a;this.u=function(e){a:if(!("*"!=d.m&&e.origin!=d.m||d.l&&e.source!=d.l||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.H&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.m=d.targetOrigin=e.origin);d.l=e.source;d.sessionId=f.id;d.j&&(d.j(),d.j=null);break;case "command":d.o&&(!d.s||0<=eb(d.s,f.func))&&d.o(f.func,f.args,e.origin)}}};
this.s=this.j=this.o=null;window.addEventListener("message",this.u)}
u(Sv,J);Sv.prototype.sendMessage=function(a,b){if(b=b||this.l){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){Ek(d)}}};
Sv.prototype.D=function(){window.removeEventListener("message",this.u);J.prototype.D.call(this)};function Tv(){this.j=[];this.isReady=!1;this.l={};var a=this.i=new Sv(!!L("WIDGET_ID_ENFORCE")),b=this.fd.bind(this);a.o=b;a.s=null;this.i.channel="widget";if(a=L("WIDGET_ID"))this.i.sessionId=a}
l=Tv.prototype;l.fd=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.l[a]||"onReady"===a||(this.addEventListener(a,Uv(this,a)),this.l[a]=!0)):this.Ob(a,b,c)};
l.Ob=function(){};
function Uv(a,b){return function(c){return a.sendMessage(b,c)}}
l.addEventListener=function(){};
l.Sc=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.xb());this.sendMessage("onReady");fb(this.j,this.vc,this);this.j=[]};
l.xb=function(){return null};
function Vv(a,b){a.sendMessage("infoDelivery",b)}
l.vc=function(a){this.isReady?this.i.sendMessage(a):this.j.push(a)};
l.sendMessage=function(a,b){this.vc({event:a,info:void 0===b?null:b})};
l.dispose=function(){this.i=null};var Wv={},Xv=(Wv["api.invalidparam"]=2,Wv.auth=150,Wv["drm.auth"]=150,Wv["heartbeat.net"]=150,Wv["heartbeat.servererror"]=150,Wv["heartbeat.stop"]=150,Wv["html5.unsupportedads"]=5,Wv["fmt.noneavailable"]=5,Wv["fmt.decode"]=5,Wv["fmt.unplayable"]=5,Wv["html5.missingapi"]=5,Wv["html5.unsupportedlive"]=5,Wv["drm.unavailable"]=5,Wv["mrm.blocked"]=151,Wv);var Yv=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function Zv(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function $v(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=p(Yv);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function aw(a,b,c,d){if(Qa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function bw(a){Tv.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.qd.bind(this));this.addEventListener("onVolumeChange",this.rd.bind(this));this.addEventListener("onApiChange",this.ld.bind(this));this.addEventListener("onPlaybackQualityChange",this.nd.bind(this));this.addEventListener("onPlaybackRateChange",this.od.bind(this));this.addEventListener("onStateChange",this.pd.bind(this));this.addEventListener("onWebglSettingsChanged",
this.sd.bind(this))}
u(bw,Tv);l=bw.prototype;
l.Ob=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Zv(a)){var d=b;if(Qa(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=$v(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=$v(e);break;case "loadPlaylist":case "cuePlaylist":e=aw(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);Zv(a)&&Vv(this,this.xb())}};
l.onReady=function(){var a=this.Sc.bind(this);this.i.j=a;a=this.api.getVideoData();if(!a.isPlayable){a=a.errorCode;var b=void 0===b?5:b;this.sendMessage("onError",(a?Xv[a]||b:b).toString())}};
l.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
l.xb=function(){if(!this.api)return null;var a=this.api.getApiInterface();lb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
l.pd=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());Vv(this,a)};
l.nd=function(a){Vv(this,{playbackQuality:a})};
l.od=function(a){Vv(this,{playbackRate:a})};
l.ld=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],m=this.api.getOption(e,k);b[e][k]=m}}this.sendMessage("apiInfoDelivery",b)};
l.rd=function(){Vv(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
l.qd=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Vv(this,a)};
l.sd=function(){var a={sphericalProperties:this.api.getSphericalProperties()};Vv(this,a)};
l.dispose=function(){Tv.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function cw(a){J.call(this);this.j={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.pc,this)}
u(cw,J);l=cw.prototype;l.start=function(){this.started||this.i()||(this.started=!0,this.connection.Aa("RECEIVING"))};
l.Aa=function(a,b){this.started&&!this.i()&&this.connection.Aa(a,b)};
l.pc=function(a,b,c){if(this.started&&!this.i()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=dw(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=ew(a,c))&&this.Aa(a,c))}}};
l.addListener=function(a){if(!(a in this.j)){var b=this.md.bind(this,a);this.j[a]=b;this.addEventListener(a,b)}};
l.md=function(a,b){this.started&&!this.i()&&this.connection.Aa(a,this.wb(a,b))};
l.wb=function(a,b){if(null!=b)return{value:b}};
l.removeListener=function(a){a in this.j&&(this.removeEventListener(a,this.j[a]),delete this.j[a])};
l.D=function(){var a=this.connection;a.i()||mi(a.j,"command",this.pc,this);this.connection=null;for(var b in this.j)this.j.hasOwnProperty(b)&&this.removeListener(b);J.prototype.D.call(this)};function fw(a,b){cw.call(this,b);this.api=a;this.start()}
u(fw,cw);fw.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
fw.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function dw(a,b){switch(a){case "loadVideoById":return a=$v(b),[a];case "cueVideoById":return a=$v(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=aw(b),[a];case "cuePlaylist":return a=aw(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function ew(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
fw.prototype.wb=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return cw.prototype.wb.call(this,a,b)};
fw.prototype.D=function(){cw.prototype.D.call(this);delete this.api};function gw(a){a=void 0===a?!1:a;J.call(this);this.j=new K(a);ke(this,this.j)}
Za(gw,J);gw.prototype.subscribe=function(a,b,c){return this.i()?0:this.j.subscribe(a,b,c)};
gw.prototype.m=function(a,b){this.i()||this.j.ta.apply(this.j,arguments)};function hw(a,b,c){gw.call(this);this.l=a;this.destination=b;this.id=c}
u(hw,gw);hw.prototype.Aa=function(a,b){this.i()||this.l.Aa(this.destination,this.id,a,b)};
hw.prototype.D=function(){this.destination=this.l=null;gw.prototype.D.call(this)};function iw(a,b,c){J.call(this);this.destination=a;this.origin=c;this.j=Np(window,"message",this.l.bind(this));this.connection=new hw(this,a,b);ke(this,this.connection)}
u(iw,J);iw.prototype.Aa=function(a,b,c,d){this.i()||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(JSON.stringify(a),this.origin))};
iw.prototype.l=function(a){if(!this.i()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.i()||c.m("command",b.command,b.data,a.origin)}}}};
iw.prototype.D=function(){Op(this.j);this.destination=null;J.prototype.D.call(this)};function jw(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||vb(b);this.assets=a.assets||{};this.attrs=a.attrs||vb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
jw.prototype.clone=function(){var a=new jw,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Oa(c)?a[b]=vb(c):a[b]=c}return a};var kw=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function lw(a){a=a||"";if(window.spf){var b=a.match(kw);spf.style.load(a,b?b[1]:"",void 0)}else mw(a)}
function mw(a){var b=nw(a),c=document.getElementById(b),d=c&&fv(c,"loaded");d||c&&!d||(c=ow(a,b,function(){fv(c,"loaded")||(dv(c),cq(b),Xk(Ya(dq,b),0))}))}
function ow(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Lb(a);gc(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function nw(a){var b=cf("A");Db("This URL is never added to the DOM");fc(b,new Ob(a,Pb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+kc(a)}
;function pw(){J.call(this);this.j=[]}
u(pw,J);pw.prototype.D=function(){for(;this.j.length;){var a=this.j.pop();a.target.removeEventListener(a.name,a.callback,void 0)}J.prototype.D.call(this)};function qw(){pw.apply(this,arguments)}
u(qw,pw);function rw(a,b,c,d){J.call(this);var e=this;this.u=b;this.webPlayerContextConfig=d;this.da=!1;this.api={};this.X=this.s=null;this.L=new K;this.j={};this.R=this.Y=this.elementId=this.va=this.config=null;this.P=!1;this.m=this.H=null;this.la={};this.Wa=["onReady"];this.lastError=null;this.Ja=NaN;this.K={};this.Xa=new qw(this);this.T=0;this.l=this.o=a;ke(this,this.L);sw(this);tw(this);ke(this,this.Xa);c?this.T=Xk(function(){e.loadNewVideoConfig(c)},0):d&&(uw(this),vw(this))}
u(rw,J);l=rw.prototype;l.getId=function(){return this.u};
l.loadNewVideoConfig=function(a){if(!this.i()){this.T&&(Yk(this.T),this.T=0);var b=a||{};b instanceof jw||(b=new jw(b));this.config=b;this.setConfig(a);vw(this);this.isReady()&&ww(this)}};
function uw(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.u,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.u:a.config.attrs.id=a.u);var c;(null==(c=a.l)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
l.setConfig=function(a){this.va=a;this.config=xw(a);uw(this);if(!this.Y){var b;this.Y=yw(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.l&&(this.l.style.width=Jh(Number(b)||b)),(a=a.height)&&this.l&&(this.l.style.height=Jh(Number(a)||a))};
function ww(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function zw(a){var b=!0,c=Aw(a);c&&a.config&&(a=Bw(a),b=fv(c,"version")===a);return b&&!!B("yt.player.Application.create")}
function vw(a){if(!a.i()&&!a.P){var b=zw(a);if(b&&"html5"===(Aw(a)?"html5":null))a.R="html5",a.isReady()||Cw(a);else if(Dw(a),a.R="html5",b&&a.m&&a.o)a.o.appendChild(a.m),Cw(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.H=function(){c=!0;var d=Ew(a,"player_bootstrap_method")?B("yt.player.Application.createAlternate")||B("yt.player.Application.create"):B("yt.player.Application.create");var e=a.config?xw(a.config):void 0;d&&d(a.o,e,a.webPlayerContextConfig);Cw(a)};
a.P=!0;b?a.H():(jv(Bw(a),a.H),(b=Fw(a))&&lw(b),Gw(a)&&!c&&A("yt.player.Application.create",null))}}}
function Aw(a){var b=bf(a.elementId);!b&&a.l&&a.l.querySelector&&(b=a.l.querySelector("#"+a.elementId));return b}
function Cw(a){if(!a.i()){var b=Aw(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.P=!1;if(!Ew(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}Hw(a)}else a.Ja=Xk(function(){Cw(a)},50)}}
function Hw(a){sw(a);a.da=!0;var b=Aw(a);if(b){a.s=Iw(a,b,"addEventListener");a.X=Iw(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Iw(a,b,f))}}for(var g in a.j)a.j.hasOwnProperty(g)&&a.s&&a.s(g,a.j[g]);ww(a);a.Y&&a.Y(a.api);a.L.ta("onReady",a.api)}
function Iw(a,b,c){var d=b[c];return function(){var e=Ja.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,yr(f))}}}
function sw(a){a.da=!1;if(a.X)for(var b in a.j)a.j.hasOwnProperty(b)&&a.X(b,a.j[b]);for(var c in a.K)a.K.hasOwnProperty(c)&&Yk(Number(c));a.K={};a.s=null;a.X=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.va};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
l.isReady=function(){return this.da};
function tw(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){cq("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){cq("WATCH_LATER_VIDEO_REMOVED",b)})}
l.addEventListener=function(a,b){var c=this,d=yw(this,b);d&&(0<=eb(this.Wa,a)||this.j[a]||(b=Jw(this,a),this.s&&this.s(a,b)),this.L.subscribe(a,d),"onReady"===a&&this.isReady()&&Xk(function(){d(c.api)},0))};
l.removeEventListener=function(a,b){this.i()||(b=yw(this,b))&&mi(this.L,a,b)};
function yw(a,b){var c=b;if("string"===typeof b){if(a.la[b])return a.la[b];c=function(){var d=Ja.apply(0,arguments),e=B(b);if(e)try{e.apply(y,d)}catch(f){xr(f)}};
a.la[b]=c}return c?c:null}
function Jw(a,b){var c="ytPlayer"+b+a.u;a.j[b]=c;y[c]=function(d){var e=Xk(function(){if(!a.i()){try{a.L.ta(b,null!=d?d:void 0)}catch(h){yr(new R("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.u,data:d}))}var f=a.K,g=String(e);g in f&&delete f[g]}},0);
sb(a.K,String(e))};
return c}
l.getPlayerType=function(){return this.R||(Aw(this)?"html5":null)};
l.getLastError=function(){return this.lastError};
function Dw(a){a.cancel();sw(a);a.R=null;a.config&&(a.config.loaded=!1);var b=Aw(a);b&&(zw(a)||!Gw(a)?a.m=b:(b&&b.destroy&&b.destroy(),a.m=null));if(a.o)for(a=a.o;b=a.firstChild;)a.removeChild(b)}
l.cancel=function(){this.H&&pv(Bw(this),this.H);Yk(this.Ja);this.P=!1};
l.D=function(){Dw(this);if(this.m&&this.config&&this.m.destroy)try{this.m.destroy()}catch(b){xr(b)}this.la=null;for(var a in this.j)this.j.hasOwnProperty(a)&&(y[this.j[a]]=null);this.va=this.config=this.api=null;delete this.o;delete this.l;J.prototype.D.call(this)};
function Gw(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function Bw(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Fw(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Ew(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Kk(c||"","&")[b]}
function xw(a){for(var b={},c=p(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?vb(e):e}return b}
;var Kw={},Lw="player_uid_"+(1E9*Math.random()>>>0);function Mw(a,b){var c="player",d=!1;d=void 0===d?!0:d;c="string"===typeof c?bf(c):c;var e=Lw+"_"+Ra(c),f=Kw[e];if(f&&d)return Nw(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new rw(c,e,a,b);Kw[e]=f;cq("player-added",f.api);le(f,function(){delete Kw[f.getId()]});
return f.api}
function Nw(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Ow=null,Pw=null,Qw=null;function Rw(){Sw()}
function Tw(){Sw()}
function Sw(){var a=Ow.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function Uw(){Ow&&Ow.sendAbandonmentPing&&Ow.sendAbandonmentPing();L("PL_ATT")&&(M("use_player_abuse_bg_library")?Av.dispose():Bv.dispose());for(var a=Qh,b=0,c=qv.length;b<c;b++)a.ga(qv[b]);qv.length=0;ov("//static.doubleclick.net/instream/ad_status.js");rv=!1;uk("DCLKSTAT",0);je(Qw,Pw);Ow&&(Ow.removeEventListener("onVideoDataChange",Rw),Ow.destroy())}
;function Vw(a,b,c){a="ST-"+kc(a).toString(36);b=b?tc(b):"";c=c||5;fs()&&nl(a,b,c)}
;function Ww(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=L("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=L("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=oc(window.location.href);g&&f.push(g);g=oc(d);if(0<=eb(f,g)||!g&&0==d.lastIndexOf("/",0))if(M("autoescape_tempdata_url")&&(f=document.createElement("a"),fc(f,d),d=f.href),d&&(d=pc(d),f=d.indexOf("#"),d=0>f?d:d.slice(0,f)))if(e&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:Qr()},b)),h){var h=parseInt(h,10);isFinite(h)&&0<h&&
Vw(d,b,h)}else Vw(d,b)}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var k=void 0===k?{}:k;var m=void 0===m?"":m;var q=void 0===q?window:q;c=q.location;a=vc(a,k)+m;var r=void 0===r?Ih:r;a:{r=void 0===r?Ih:r;for(k=0;k<r.length;++k)if(m=r[k],m instanceof Gh&&m.isValid(a)){r=new Ob(a,Pb);break a}r=void 0}r=r||Sb;if(r instanceof Ob)var w=Qb(r);else{b:if(yh){try{w=new URL(r)}catch(t){w="https:";break b}w=w.protocol}else c:{w=document.createElement("a");try{w.href=r}catch(t){w=void 0;
break c}w=w.protocol;w=":"===w||""===w?"https:":w}w="javascript:"!==w?r:void 0}void 0!==w&&(c.href=w)}return!0}
;A("yt.setConfig",uk);A("yt.config.set",uk);A("yt.setMsg",Vr);A("yt.msgs.set",Vr);A("yt.logging.errors.log",xr);
A("writeEmbed",function(){var a=L("PLAYER_CONFIG");if(!a){var b=L("PLAYER_VARS");b&&(a={args:b})}ps(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=L("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);St();c=L("WEB_PLAYER_CONTEXT_CONFIGS").WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=Pk(window.location.href);
d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}Ow=Mw(a,c);Ow.addEventListener("onVideoDataChange",Rw);Ow.addEventListener("onReady",Tw);a=L("POST_MESSAGE_ID","player");L("ENABLE_JS_API")?Qw=new bw(Ow):L("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(Pw=new iw(window.parent,a,b),Qw=new fw(Ow,Pw.connection));sv();M("ytidb_create_logger_embed_killswitch")||M("embeds_web_disable_nwl")||im();a={};Nv||(Nv=new Mv);Nv.install((a.flush_logs={callback:function(){Dq()}},
a));
M("embeds_web_disable_nwl")||Dp();M("ytidb_clear_embedded_player")&&Qh.V(function(){var e;if(!Au){var f=Ks(),g={Hb:zu,zc:yu};f.providers.set(g.Hb,g);g={Wb:{feedbackEndpoint:Ls(uu),modifyChannelNotificationPreferenceEndpoint:Ls(vu),playlistEditEndpoint:Ls(wu),subscribeEndpoint:Ls(su),unsubscribeEndpoint:Ls(tu),webPlayerShareEntityServiceEndpoint:Ls(xu)}};var h=ys.getInstance(),k={};h&&(k.client_location=h);if(void 0===m){qs.i||(qs.i=new qs);var m=qs.i}void 0===e&&(e=f.resolve(zu));fu(g,e,m,k);m={Hb:lu,
Ac:eu.i};f.providers.set(m.Hb,m);Au=f.resolve(lu)}cv()})});
var Xw=Ck(function(){Zt();var a=rl.getInstance(),b=ul(119),c=1<window.devicePixelRatio;if(document.body&&$h(document.body,"exp-invert-logo"))if(c&&!$h(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!$h(d,"inverted-hdpi")){var e=Yh(d);Zh(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&$h(document.body,"inverted-hdpi")&&ai();if(b!=c){b="f"+(Math.floor(119/31)+1);d=vl(b)||0;d=c?d|67108864:d&-67108865;0==d?delete ql[b]:(c=d.toString(16),
ql[b]=c.toString());c=!0;M("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.i;d=[];for(var f in ql)d.push(f+"="+encodeURIComponent(String(ql[f])));nl(b,d.join("&"),63072E3,a.j,c)}Mu.i||(Mu.i=new Mu);a=Mu.i;f=16623;var g=void 0===g?{}:g;Object.values(Wr).includes(f)||(yr(new R("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.i.push({rootVe:f,key:g.key||""});a.o=[];a.C=[];g.Zb?Pu(a,f,g):Qu(a,f,g)}),Yw=Ck(function(a){M("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?
Uw():a.persisted||Uw()}),Zw=Ck(Uw);
window.addEventListener?(window.addEventListener("load",Xw),window.addEventListener("pagehide",Yw)):window.attachEvent&&(window.attachEvent("onload",Xw),window.attachEvent("onunload",Zw));A("yt.abuse.player.botguardInitialized",B("yt.abuse.player.botguardInitialized")||Cv);A("yt.abuse.player.invokeBotguard",B("yt.abuse.player.invokeBotguard")||Dv);A("yt.abuse.dclkstatus.checkDclkStatus",B("yt.abuse.dclkstatus.checkDclkStatus")||tv);A("yt.player.exports.navigate",B("yt.player.exports.navigate")||Ww);
A("yt.util.activity.init",B("yt.util.activity.init")||Sp);A("yt.util.activity.getTimeSinceActive",B("yt.util.activity.getTimeSinceActive")||Vp);A("yt.util.activity.setTimestamp",B("yt.util.activity.setTimestamp")||Tp);}).call(this);
