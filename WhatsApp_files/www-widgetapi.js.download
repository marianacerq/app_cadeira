(function(){'use strict';var q;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ea(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var fa=ea(this);function t(a,b){if(b)a:{var c=fa;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
t("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.g=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.g};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
t("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=fa[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ha(aa(this))}})}return a});
function ha(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function u(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if("number"==typeof a.length)return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function v(a){if(!(a instanceof Array)){a=u(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ia(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ja="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ia(d,e)&&(a[e]=d[e])}return a};
t("Object.assign",function(a){return a||ja});
var ka="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},la;
if("function"==typeof Object.setPrototypeOf)la=Object.setPrototypeOf;else{var oa;a:{var pa={a:!0},qa={};try{qa.__proto__=pa;oa=qa.a;break a}catch(a){}oa=!1}la=oa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ra=la;
function w(a,b){a.prototype=ka(b.prototype);a.prototype.constructor=a;if(ra)ra(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.na=b.prototype}
function sa(){this.H=!1;this.j=null;this.h=void 0;this.g=1;this.u=this.o=0;this.S=this.i=null}
function ta(a){if(a.H)throw new TypeError("Generator is already running");a.H=!0}
sa.prototype.M=function(a){this.h=a};
function ua(a,b){a.i={pc:b,Ac:!0};a.g=a.o||a.u}
sa.prototype.return=function(a){this.i={return:a};this.g=this.u};
function z(a,b,c){a.g=c;return{value:b}}
sa.prototype.B=function(a){this.g=a};
function va(a,b,c){a.o=b;void 0!=c&&(a.u=c)}
function wa(a){a.o=0;var b=a.i.pc;a.i=null;return b}
function xa(a){var b=a.S.splice(0)[0];(b=a.i=a.i||b)?b.Ac?a.g=a.o||a.u:void 0!=b.B&&a.u<b.B?(a.g=b.B,a.i=null):a.g=a.u:a.g=0}
function ya(a){this.g=new sa;this.h=a}
function za(a,b){ta(a.g);var c=a.g.j;if(c)return Aa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.g.return);
a.g.return(b);return Ba(a)}
function Aa(a,b,c,d){try{var e=b.call(a.g.j,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.g.H=!1,e;var f=e.value}catch(g){return a.g.j=null,ua(a.g,g),Ba(a)}a.g.j=null;d.call(a.g,f);return Ba(a)}
function Ba(a){for(;a.g.g;)try{var b=a.h(a.g);if(b)return a.g.H=!1,{value:b.value,done:!1}}catch(c){a.g.h=void 0,ua(a.g,c)}a.g.H=!1;if(a.g.i){b=a.g.i;a.g.i=null;if(b.Ac)throw b.pc;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ca(a){this.next=function(b){ta(a.g);a.g.j?b=Aa(a,a.g.j.next,b,a.g.M):(a.g.M(b),b=Ba(a));return b};
this.throw=function(b){ta(a.g);a.g.j?b=Aa(a,a.g.j["throw"],b,a.g.M):(ua(a.g,b),b=Ba(a));return b};
this.return=function(b){return za(a,b)};
this[Symbol.iterator]=function(){return this}}
function Da(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function A(a){return Da(new Ca(new ya(a)))}
function Ea(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
t("Reflect.setPrototypeOf",function(a){return a?a:ra?function(b,c){try{return ra(b,c),!0}catch(d){return!1}}:null});
t("Promise",function(a){function b(g){this.g=0;this.i=void 0;this.h=[];this.H=!1;var h=this.j();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.g=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.h=function(g){if(null==this.g){this.g=[];var h=this;this.i(function(){h.o()})}this.g.push(g)};
var e=fa.setTimeout;c.prototype.i=function(g){e(g,0)};
c.prototype.o=function(){for(;this.g&&this.g.length;){var g=this.g;this.g=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.j(l)}}}this.g=null};
c.prototype.j=function(g){this.i(function(){throw g;})};
b.prototype.j=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.hb),reject:g(this.o)}};
b.prototype.hb=function(g){if(g===this)this.o(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.jb(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.za(g):this.u(g)}};
b.prototype.za=function(g){var h=void 0;try{h=g.then}catch(k){this.o(k);return}"function"==typeof h?this.xb(h,g):this.u(g)};
b.prototype.o=function(g){this.M(2,g)};
b.prototype.u=function(g){this.M(1,g)};
b.prototype.M=function(g,h){if(0!=this.g)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.g);this.g=g;this.i=h;2===this.g&&this.ib();this.S()};
b.prototype.ib=function(){var g=this;e(function(){if(g.oa()){var h=fa.console;"undefined"!==typeof h&&h.error(g.i)}},1)};
b.prototype.oa=function(){if(this.H)return!1;var g=fa.CustomEvent,h=fa.Event,k=fa.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=fa.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.i;return k(g)};
b.prototype.S=function(){if(null!=this.h){for(var g=0;g<this.h.length;++g)f.h(this.h[g]);this.h=null}};
var f=new c;b.prototype.jb=function(g){var h=this.j();g.Ab(h.resolve,h.reject)};
b.prototype.xb=function(g,h){var k=this.j();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(r,p){return"function"==typeof r?function(x){try{l(r(x))}catch(y){m(y)}}:p}
var l,m,n=new b(function(r,p){l=r;m=p});
this.Ab(k(g,l),k(h,m));return n};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Ab=function(g,h){function k(){switch(l.g){case 1:g(l.i);break;case 2:h(l.i);break;default:throw Error("Unexpected state: "+l.g);}}
var l=this;null==this.h?f.h(k):this.h.push(k);this.H=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=u(g),m=l.next();!m.done;m=l.next())d(m.value).Ab(h,k)})};
b.all=function(g){var h=u(g),k=h.next();return k.done?d([]):new b(function(l,m){function n(x){return function(y){r[x]=y;p--;0==p&&l(r)}}
var r=[],p=0;do r.push(void 0),p++,d(k.value).Ab(n(r.length-1),m),k=h.next();while(!k.done)})};
return b});
t("WeakMap",function(a){function b(k){this.g=(h+=Math.random()+1).toString();if(k){k=u(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!ia(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(2!=m.get(k)||3!=m.get(l))return!1;m.delete(k);m.set(l,4);return!m.has(k)&&4==m.get(l)}catch(n){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ia(k,g))throw Error("WeakMap key fail: "+k);k[g][this.g]=l;return this};
b.prototype.get=function(k){return d(k)&&ia(k,g)?k[g][this.g]:void 0};
b.prototype.has=function(k){return d(k)&&ia(k,g)&&ia(k[g],this.g)};
b.prototype.delete=function(k){return d(k)&&ia(k,g)&&ia(k[g],this.g)?delete k[g][this.g]:!1};
return b});
t("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ha(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h[0][l];if(m&&ia(h[0],l))for(h=0;h<m.length;h++){var n=m[h];if(k!==k&&n.key!==n.key||k===n.key)return{id:l,list:m,index:h,entry:n}}return{id:l,list:m,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=u(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(u([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||"s"!=m.value[1])return!1;m=l.next();return m.done||4!=m.value[0].x||"t"!=m.value[1]||!l.next().done?!1:!0}catch(n){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ha(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
t("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ha(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
t("Object.setPrototypeOf",function(a){return a||ra});
t("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
t("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ha(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
t("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
t("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ia(b,d)&&c.push(b[d]);return c}});
t("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
t("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
t("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ha(this,b,"includes").indexOf(b,c||0)}});
t("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
t("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
t("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
function Ia(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
t("Array.prototype.entries",function(a){return a?a:function(){return Ia(this,function(b,c){return[b,c]})}});
t("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
t("Array.prototype.keys",function(a){return a?a:function(){return Ia(this,function(b){return b})}});
t("Array.prototype.values",function(a){return a?a:function(){return Ia(this,function(b,c){return c})}});
t("Set",function(a){function b(c){this.g=new Map;if(c){c=u(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.g.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(u([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.g.set(c,c);this.size=this.g.size;return this};
b.prototype.delete=function(c){c=this.g.delete(c);this.size=this.g.size;return c};
b.prototype.clear=function(){this.g.clear();this.size=0};
b.prototype.has=function(c){return this.g.has(c)};
b.prototype.entries=function(){return this.g.entries()};
b.prototype.values=function(){return this.g.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.g.forEach(function(f){return c.call(d,f,f,e)})};
return b});
t("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ia(b,d)&&c.push([d,b[d]]);return c}});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var B=this||self;function C(a,b){a=a.split(".");b=b||B;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Ka(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function La(a){var b=Ka(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Ma(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Na(a){return Object.prototype.hasOwnProperty.call(a,Oa)&&a[Oa]||(a[Oa]=++Pa)}
var Oa="closure_uid_"+(1E9*Math.random()>>>0),Pa=0;function Qa(a,b,c){return a.call.apply(a.bind,arguments)}
function Sa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ta(a,b,c){Ta=Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Qa:Sa;return Ta.apply(null,arguments)}
function Ua(){return Date.now()}
function D(a,b){a=a.split(".");var c=B;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function Va(a,b){function c(){}
c.prototype=b.prototype;a.na=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.me=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Wa(a){return a}
;function Xa(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Xa);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
Va(Xa,Error);Xa.prototype.name="CustomError";function Ya(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.i=!b&&/[?&]ae=1(&|$)/.test(a);this.j=!b&&/[?&]ae=2(&|$)/.test(a);if((this.g=/[?&]adurl=([^&]*)/.exec(a))&&this.g[1]){try{var c=decodeURIComponent(this.g[1])}catch(d){c=null}this.h=c}}
;function Za(){}
function $a(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var ab=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},bb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)};
function cb(a,b){b=ab(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function fb(a){return Array.prototype.concat.apply([],arguments)}
function gb(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function hb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(La(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function ib(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function jb(a){var b=kb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function lb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function mb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=mb(a[c]);return b}
var nb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function ob(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<nb.length;f++)c=nb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var pb;function qb(){}
function rb(a){return new qb(sb,a)}
var sb={};rb("");var tb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]},ub=/&/g,vb=/</g,wb=/>/g,xb=/"/g,yb=/'/g,zb=/\x00/g,Ab=/[\x00&<>"']/;function Bb(a){this.g=a}
Bb.prototype.toString=function(){return this.g.toString()};
var Cb={},Db=new Bb("about:invalid#zClosurez",Cb);var Eb,Fb=C("CLOSURE_FLAGS"),Gb=Fb&&Fb[610401301];Eb=null!=Gb?Gb:!1;function Hb(){var a=B.navigator;return a&&(a=a.userAgent)?a:""}
var Ib,Jb=B.navigator;Ib=Jb?Jb.userAgentData||null:null;function Kb(a){return Eb?Ib?Ib.brands.some(function(b){return(b=b.brand)&&-1!=b.indexOf(a)}):!1:!1}
function E(a){return-1!=Hb().indexOf(a)}
;function Lb(){return Eb?!!Ib&&0<Ib.brands.length:!1}
function Rb(){return Lb()?!1:E("Trident")||E("MSIE")}
function Sb(){return Lb()?Kb("Chromium"):(E("Chrome")||E("CriOS"))&&!(Lb()?0:E("Edge"))||E("Silk")}
;function Tb(a){this.g=a}
Tb.prototype.toString=function(){return this.g.toString()};function Ub(a){Ab.test(a)&&(-1!=a.indexOf("&")&&(a=a.replace(ub,"&amp;")),-1!=a.indexOf("<")&&(a=a.replace(vb,"&lt;")),-1!=a.indexOf(">")&&(a=a.replace(wb,"&gt;")),-1!=a.indexOf('"')&&(a=a.replace(xb,"&quot;")),-1!=a.indexOf("'")&&(a=a.replace(yb,"&#39;")),-1!=a.indexOf("\x00")&&(a=a.replace(zb,"&#0;")));return a}
;var Vb=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function Wb(a){return a?decodeURI(a):a}
function Xb(a){return Wb(a.match(Vb)[3]||null)}
function Yb(a){var b=a.match(Vb);a=b[1];var c=b[2],d=b[3];b=b[4];var e="";a&&(e+=a+":");d&&(e+="//",c&&(e+=c+"@"),e+=d,b&&(e+=":"+b));return e}
function Zb(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)Zb(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function $b(a){var b=[],c;for(c in a)Zb(c,a[c],b);return b.join("&")}
var ac=/#|$/;function bc(a,b){var c=a.search(ac);a:{var d=0;for(var e=b.length;0<=(d=a.indexOf(b,d))&&d<c;){var f=a.charCodeAt(d-1);if(38==f||63==f)if(f=a.charCodeAt(d+e),!f||61==f||38==f||35==f)break a;d+=e+1}d=-1}if(0>d)return null;e=a.indexOf("&",d);if(0>e||e>c)e=c;d+=b.length+1;return decodeURIComponent(a.slice(d,-1!==e?e:0).replace(/\+/g," "))}
;function cc(a){B.setTimeout(function(){throw a;},0)}
;function dc(){return E("iPhone")&&!E("iPod")&&!E("iPad")}
;function ec(a){ec[" "](a);return a}
ec[" "]=function(){};var fc=Lb()?!1:E("Opera"),gc=Rb(),hc=E("Edge"),ic=E("Gecko")&&!(-1!=Hb().toLowerCase().indexOf("webkit")&&!E("Edge"))&&!(E("Trident")||E("MSIE"))&&!E("Edge"),jc=-1!=Hb().toLowerCase().indexOf("webkit")&&!E("Edge");function kc(){var a=B.document;return a?a.documentMode:void 0}
var lc;a:{var mc="",nc=function(){var a=Hb();if(ic)return/rv:([^\);]+)(\)|;)/.exec(a);if(hc)return/Edge\/([\d\.]+)/.exec(a);if(gc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(jc)return/WebKit\/(\S+)/.exec(a);if(fc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
nc&&(mc=nc?nc[1]:"");if(gc){var oc=kc();if(null!=oc&&oc>parseFloat(mc)){lc=String(oc);break a}}lc=mc}var pc=lc,qc;if(B.document&&gc){var rc=kc();qc=rc?rc:parseInt(pc,10)||void 0}else qc=void 0;var wc=qc;var xc=dc()||E("iPod"),yc=E("iPad");!E("Android")||Sb();Sb();var zc=E("Safari")&&!(Sb()||(Lb()?0:E("Coast"))||(Lb()?0:E("Opera"))||(Lb()?0:E("Edge"))||(Lb()?Kb("Microsoft Edge"):E("Edg/"))||(Lb()?Kb("Opera"):E("OPR"))||E("Firefox")||E("FxiOS")||E("Silk")||E("Android"))&&!(dc()||E("iPad")||E("iPod"));var Ac={},Bc=null;
function Cc(a,b){La(a);void 0===b&&(b=0);if(!Bc){Bc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));Ac[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===Bc[h]&&(Bc[h]=g)}}}b=Ac[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],l=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|l>>4];l=b[(l&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+l+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var Dc="undefined"!==typeof Uint8Array,Ec=!gc&&"function"===typeof btoa;function Fc(a){return Array.prototype.slice.call(a)}
;var Gc="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol():void 0;Math.max.apply(Math,v(Object.values({Zd:1,Xd:2,Wd:4,ce:8,be:16,ae:32,Td:64,de:128,Vd:256,Ud:512,Yd:1024})));var Hc=Gc?function(a,b){a[Gc]|=b}:function(a,b){void 0!==a.ga?a.ga|=b:Object.defineProperties(a,{ga:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function Ic(a){var b=G(a);1!==(b&1)&&(Object.isFrozen(a)&&(a=Fc(a)),Jc(a,b|1))}
var Kc=Gc?function(a,b){a[Gc]&=~b}:function(a,b){void 0!==a.ga&&(a.ga&=~b)},G=Gc?function(a){return a[Gc]|0}:function(a){return a.ga|0},Lc=Gc?function(a){return a[Gc]}:function(a){return a.ga},Jc=Gc?function(a,b){a[Gc]=b}:function(a,b){void 0!==a.ga?a.ga=b:Object.defineProperties(a,{ga:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function Mc(a,b){Object.isFrozen(a)&&(a=Fc(a));Jc(a,b);return a}
function Nc(a){Hc(a,1);return a}
function Oc(a,b){Jc(b,(a|0)&-255)}
function Pc(a,b){Jc(b,(a|34)&-221)}
function Qc(a){a=a>>11&1023;return 0===a?536870912:a}
;var Rc={};function Sc(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var Tc,Vc,Wc=[];Jc(Wc,39);Vc=Object.freeze(Wc);function Xc(a){if(a&2)throw Error();}
;function Yc(a){return a.displayName||a.name||"unknown type name"}
function Zc(a){if("boolean"!==typeof a)throw Error("Expected boolean but got "+Ka(a)+": "+a);return!!a}
var $c=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function ad(a){return"number"===typeof a&&Number.isFinite(a)||!!a&&"string"===typeof a&&isFinite(a)}
function bd(a){if(!ad(a))throw Error();var b=typeof a;("number"===b?Number.isFinite(a):"string"!==b?0:$c.test(a))||cc(Error());"string"===typeof a?ad(a):ad(a);return a}
function cd(a){if(null!=a&&"string"!==typeof a)throw Error();return a}
function dd(a){return null==a||"string"===typeof a?a:void 0}
function ed(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Yc(b)+" but got "+(a&&Yc(a.constructor)));return a}
function fd(a,b,c){var d=!1;if(null!=a&&"object"===typeof a&&!(d=Array.isArray(a))&&a.Zb===Rc)return a;if(d){var e=d=G(a);0===e&&(e|=c&32);e|=c&2;e!==d&&Jc(a,e);return new b(a)}}
;var gd;function H(a,b,c){null==a&&(a=gd);gd=void 0;if(null==a){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-2095105|(b&1023)<<11)}else{if(!Array.isArray(a))throw Error();d=G(a);if(d&64)return a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error();a:{c=a;var e=c.length;if(e){var f=e-1,g=c[f];if(Sc(g)){d|=256;b=+!!(d&512)-1;e=f-b;1024<=e&&(hd(c,b,g),e=1023);d=d&-2095105|(e&1023)<<11;break a}}b&&(g=+!!(d&512)-1,b=Math.max(b,e-g),1024<b&&(hd(c,g,{}),d|=256,b=1023),d=d&-2095105|(b&1023)<<11)}}Jc(a,d);return a}
function hd(a,b,c){for(var d=1023+b,e=a.length,f=d;f<e;f++){var g=a[f];null!=g&&g!==c&&(c[f-b]=g)}a.length=d+1;a[d]=c}
;function id(a,b){return jd(b)}
function jd(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "boolean":return a?1:0;case "object":if(a&&!Array.isArray(a)&&Dc&&null!=a&&a instanceof Uint8Array){if(Ec){for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);a=btoa(b)}else a=Cc(a);return a}}return a}
;function nd(a,b,c){a=Fc(a);var d=a.length,e=b&256?a[d-1]:void 0;d+=e?-1:0;for(b=b&512?1:0;b<d;b++)a[b]=c(a[b]);if(e){b=a[b]={};for(var f in e)b[f]=c(e[f])}return a}
function od(a,b,c,d,e,f){if(null!=a){if(Array.isArray(a))a=e&&0==a.length&&G(a)&1?void 0:f&&G(a)&2?a:pd(a,b,c,void 0!==d,e,f);else if(Sc(a)){var g={},h;for(h in a)g[h]=od(a[h],b,c,d,e,f);a=g}else a=b(a,d);return a}}
function pd(a,b,c,d,e,f){var g=d||c?G(a):0;d=d?!!(g&32):void 0;a=Fc(a);for(var h=0;h<a.length;h++)a[h]=od(a[h],b,c,d,e,f);c&&c(g,a);return a}
function qd(a){return a.Zb===Rc?a.toJSON():jd(a)}
;function rd(a,b,c){c=void 0===c?Pc:c;if(null!=a){if(Dc&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=G(a);return d&2?a:!b||d&68||!(d&32||0===d)?pd(a,rd,d&4?Pc:c,!0,!1,!0):(Jc(a,d|34),a)}a.Zb===Rc&&(b=a.s,c=Lc(b),a=c&2?a:sd(a,b,c,!0));return a}}
function sd(a,b,c,d){a=a.constructor;b=td(b,c,d);G(b);gd=b;b=new a(b);gd=void 0;return b}
function td(a,b,c){var d=c||b&2?Pc:Oc,e=!!(b&32);a=nd(a,b,function(f){return rd(f,e,d)});
Hc(a,32|(c?2:0));return a}
;function ud(a,b){a=a.s;return vd(a,Lc(a),b)}
function vd(a,b,c,d){if(-1===c)return null;if(c>=Qc(b)){if(b&256)return a[a.length-1][c]}else{var e=a.length;if(d&&b&256&&(d=a[e-1][c],null!=d))return d;b=c+(+!!(b&512)-1);if(b<e)return a[b]}}
function wd(a,b,c){var d=a.s,e=Lc(d);Xc(e);xd(d,e,b,c);return a}
function xd(a,b,c,d,e){Sc(d);var f=Qc(b);if(c>=f||e){e=b;if(b&256)f=a[a.length-1];else{if(null==d)return;f=a[f+(+!!(b&512)-1)]={};e|=256}f[c]=d;e!==b&&Jc(a,e)}else a[c+(+!!(b&512)-1)]=d,b&256&&(a=a[a.length-1],c in a&&delete a[c])}
function yd(a,b,c,d){var e=b&2,f=vd(a,b,c);Array.isArray(f)||(f=Vc);var g=G(f);g&1||Nc(f);if(e)g&2||Hc(f,34),d&1||Object.freeze(f);else{e=!(d&2);var h=g&2;d&1||!h?e&&g&32&&!h&&Kc(f,32):(f=Nc(Fc(f)),xd(a,b,c,f))}return f}
function zd(a,b,c,d){a=a.s;var e=Lc(a);Xc(e);(c=Ad(a,e,c))&&c!==b&&null!=d&&xd(a,e,c);xd(a,e,b,d)}
function Bd(a,b,c){a=a.s;return Ad(a,Lc(a),b)===c?c:-1}
function Ad(a,b,c){for(var d=0,e=0;e<c.length;e++){var f=c[e];null!=vd(a,b,f)&&(0!==d&&xd(a,b,d),d=f)}return d}
function Cd(a,b,c){var d=void 0===d?!1:d;var e=a.s;var f=Lc(e),g=vd(e,f,c,d);b=fd(g,b,f);b!==g&&null!=b&&xd(e,f,c,b,d);e=b;if(null==e)return e;a=a.s;f=Lc(a);if(!(f&2)){g=e;b=g.s;var h=Lc(b);g=h&2?sd(g,b,h,!1):g;g!==e&&(e=g,xd(a,f,c,e,d))}return e}
function I(a,b,c,d){null!=d?ed(d,b):d=void 0;return wd(a,c,d)}
function Dd(a,b,c,d,e){null!=e?ed(e,b):e=void 0;zd(a,c,d,e)}
function Ed(a,b,c,d){a=a.s;var e=Lc(a);Xc(e);var f=!!(e&2),g=yd(a,e,b,1);if(g!==Vc&&G(g)&4){if(f)f=G(g),g=Fc(g),Jc(g,f),xd(a,e,b,g);else{f=Object.isFrozen(g);var h=G(g);var k=h&-35;f&&(g=Fc(g),h=0,xd(a,e,b,g));h!==k&&Jc(g,k)}b=g}else{f=g;h=!!(e&2);k=!!(G(f)&2);g=f;!h&&k&&(f=Fc(f));h=e|(k?2:0);k=k||void 0;for(var l=0,m=0;l<f.length;l++){var n=fd(f[l],c,h);void 0!==n&&(k=k||Lc(n.s)&2,f[m++]=n)}m<l&&(f.length=m);k=!k;h=G(f);l=h|5;k=k?l|8:l&-9;h!=k&&(f=Mc(f,k));g!==f&&xd(a,e,b,f);b=f}c=null!=d?ed(d,c):
new c;b.push(c);G(c.s)&2&&Kc(b,8)}
function Fd(a,b){var c=void 0===c?"":c;a=dd(ud(a,b));return null!=a?a:c}
function Gd(a,b){b=Bd(a,Hd,b);return dd(ud(a,b))}
function Id(a,b,c){if(null!=c){if("number"!==typeof c)throw Error();Number.isFinite(c)}wd(a,b,c)}
function Jd(a,b,c){wd(a,b,null==c?c:bd(c))}
function J(a,b,c){return wd(a,b,cd(c))}
function Kd(a,b,c){null!=c&&(Number.isFinite(c)||cc(Error()));return wd(a,b,c)}
;function K(a,b,c){this.s=H(a,b,c)}
K.prototype.toJSON=function(){if(Tc)var a=Ld(this,this.s,!1);else a=pd(this.s,qd,void 0,void 0,!1,!1),a=Ld(this,a,!0);return a};
function Md(a){Tc=!0;try{return JSON.stringify(a.toJSON(),id)}finally{Tc=!1}}
K.prototype.clone=function(){var a=this.s;return sd(this,a,Lc(a),!1)};
K.prototype.Zb=Rc;K.prototype.toString=function(){return Ld(this,this.s,!1).toString()};
function Ld(a,b,c){var d=a.constructor.ma,e=Lc(c?a.s:b),f=Qc(e);e=!1;if(d){if(!c){b=Fc(b);var g;if(b.length&&Sc(g=b[b.length-1]))for(e=0;e<d.length;e++)if(d[e]>=f){Object.assign(b[b.length-1]={},g);break}e=!0}g=b;c=!c;f=Lc(a.s);a=Qc(f);f=+!!(f&512)-1;for(var h,k,l=0;l<d.length;l++)if(k=d[l],k<a){k+=f;var m=g[k];null==m?g[k]=c?Vc:Nc([]):c&&m!==Vc&&Ic(m)}else h||(m=void 0,g.length&&Sc(m=g[g.length-1])?h=m:g.push(h={})),m=h[k],null==h[k]?h[k]=c?Vc:Nc([]):c&&m!==Vc&&Ic(m)}d=b.length;if(!d)return b;var n;
if(Sc(h=b[d-1])){a:{var r=h;g={};c=!1;for(var p in r)a=r[p],Array.isArray(a)&&a!=a&&(c=!0),null!=a?g[p]=a:c=!0;if(c){for(var x in g){r=g;break a}r=null}}r!=h&&(n=!0);d--}for(;0<d;d--){h=b[d-1];if(null!=h)break;var y=!0}if(!n&&!y)return b;var F;e?F=b:F=Array.prototype.slice.call(b,0,d);b=F;e&&(b.length=d);r&&b.push(r);return b}
;var Nd=window;rb("csi.gstatic.com");rb("googleads.g.doubleclick.net");rb("partner.googleadservices.com");rb("pubads.g.doubleclick.net");rb("securepubads.g.doubleclick.net");rb("tpc.googlesyndication.com");function Od(a,b){this.width=a;this.height=b}
q=Od.prototype;q.clone=function(){return new Od(this.width,this.height)};
q.aspectRatio=function(){return this.width/this.height};
q.Tb=function(){return!(this.width*this.height)};
q.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
q.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
q.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};function Pd(){var a=document;var b="IFRAME";"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function Qd(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Rd(a){var b=C("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||B.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Sd(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Td[c])c=Td[c];else{c=String(c);if(!Td[c]){var f=/function\s+([^\(]+)/m.exec(c);Td[c]=f?f[1]:"[Anonymous]"}c=Td[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function Sd(a,b){b||(b={});b[Ud(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[Ud(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Sd(a,b));return c}
function Ud(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Td={};/*

 SPDX-License-Identifier: Apache-2.0
*/
var Vd;try{new URL("s://g"),Vd=!0}catch(a){Vd=!1}var Wd=Vd;function Xd(){throw Error("unknown trace type");}
;function Yd(a,b){a.removeAttribute("srcdoc");var c="allow-same-origin allow-scripts allow-forms allow-popups allow-popups-to-escape-sandbox allow-storage-access-by-user-activation".split(" ");a.setAttribute("sandbox","");for(var d=0;d<c.length;d++)a.sandbox.supports&&!a.sandbox.supports(c[d])||a.sandbox.add(c[d]);if(b instanceof Bb)b instanceof Bb&&b.constructor===Bb?b=b.g:(Ka(b),b="type_error:SafeUrl");else{b:if(Wd){try{var e=new URL(b)}catch(f){c="https:";break b}c=e.protocol}else c:{c=document.createElement("a");
try{c.href=b}catch(f){c=void 0;break c}c=c.protocol;c=":"===c||""===c?"https:":c}b="javascript:"!==c?b:void 0}void 0!==b&&(a.src=b)}
;function Zd(a){this.rd=a}
function $d(a){return new Zd(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var ae=[$d("data"),$d("http"),$d("https"),$d("mailto"),$d("ftp"),new Zd(function(a){return/^[^:]*([/?#]|$)/.test(a)})];
function be(a,b){b=void 0===b?ae:b;for(var c=0;c<b.length;++c){var d=b[c];if(d instanceof Zd&&d.rd(a))return new Bb(a,Cb)}}
function ce(a){var b=void 0===b?ae:b;return be(a,b)||Db}
;function de(a){var b=ee;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function fe(){var a=[];de(function(b){a.push(b)});
return a}
var ee={Id:"allow-forms",Jd:"allow-modals",Kd:"allow-orientation-lock",Ld:"allow-pointer-lock",Md:"allow-popups",Nd:"allow-popups-to-escape-sandbox",Od:"allow-presentation",Pd:"allow-same-origin",Qd:"allow-scripts",Rd:"allow-top-navigation",Sd:"allow-top-navigation-by-user-activation"},ge=$a(function(){return fe()});
function he(){var a=ie(),b={};bb(ge(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function ie(){var a=void 0===a?document:a;return a.createElement("iframe")}
;var je=(new Date).getTime();function ke(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.startsWith("blob:")&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==
c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function le(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(n){for(var r=g,p=0;64>p;p+=4)r[p/4]=n[p]<<24|n[p+1]<<16|n[p+2]<<8|n[p+3];for(p=16;80>p;p++)n=r[p-3]^r[p-8]^r[p-14]^r[p-16],r[p]=(n<<1|n>>>31)&4294967295;n=e[0];var x=e[1],y=e[2],F=e[3],O=e[4];for(p=0;80>p;p++){if(40>p)if(20>p){var U=F^x&(y^F);var Q=1518500249}else U=x^y^F,Q=1859775393;else 60>p?(U=x&y|F&(x|y),Q=2400959708):(U=x^y^F,Q=3395469782);U=((n<<5|n>>>27)&4294967295)+U+O+Q+r[p]&4294967295;O=F;F=y;y=(x<<30|x>>>2)&4294967295;x=n;n=U}e[0]=e[0]+n&4294967295;e[1]=e[1]+x&4294967295;e[2]=
e[2]+y&4294967295;e[3]=e[3]+F&4294967295;e[4]=e[4]+O&4294967295}
function c(n,r){if("string"===typeof n){n=unescape(encodeURIComponent(n));for(var p=[],x=0,y=n.length;x<y;++x)p.push(n.charCodeAt(x));n=p}r||(r=n.length);p=0;if(0==l)for(;p+64<r;)b(n.slice(p,p+64)),p+=64,m+=64;for(;p<r;)if(f[l++]=n[p++],m++,64==l)for(l=0,b(f);p+64<r;)b(n.slice(p,p+64)),p+=64,m+=64}
function d(){var n=[],r=8*m;56>l?c(h,56-l):c(h,64-(l-56));for(var p=63;56<=p;p--)f[p]=r&255,r>>>=8;b(f);for(p=r=0;5>p;p++)for(var x=24;0<=x;x-=8)n[r++]=e[p]>>x&255;return n}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,ad:function(){for(var n=d(),r="",p=0;p<n.length;p++)r+="0123456789ABCDEF".charAt(Math.floor(n[p]/16))+"0123456789ABCDEF".charAt(n[p]%16);return r}}}
;function me(a,b,c){var d=String(B.location.href);return d&&a&&b?[b,ne(ke(d),a,c||null)].join(" "):null}
function ne(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],bb(d,function(h){e.push(h)}),oe(e.join(" "));
var f=[],g=[];bb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];bb(d,function(h){e.push(h)});
a=oe(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function oe(a){var b=le();b.update(a);return b.ad().toLowerCase()}
;var pe={};function qe(a){this.g=a||{cookie:""}}
q=qe.prototype;q.isEnabled=function(){if(!B.navigator.cookieEnabled)return!1;if(!this.Tb())return!0;this.set("TESTCOOKIESENABLED","1",{Wb:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
q.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.te;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Wb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.g.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
q.get=function(a,b){for(var c=a+"=",d=(this.g.cookie||"").split(";"),e=0,f;e<d.length;e++){f=tb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
q.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{Wb:0,path:b,domain:c});return d};
q.Tb=function(){return!this.g.cookie};
q.clear=function(){for(var a=(this.g.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=tb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var re=new qe("undefined"==typeof document?null:document);function se(a){return!!pe.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function te(a,b,c,d){(a=B[a])||"undefined"===typeof document||(a=(new qe(document)).get(b));return a?me(a,c,d):null}
function ue(a){var b=void 0===b?!1:b;var c=ke(String(B.location.href)),d=[];var e=b;e=void 0===e?!1:e;var f=B.__SAPISID||B.__APISID||B.__3PSAPISID||B.__OVERRIDE_SID;se(e)&&(f=f||B.__1PSAPISID);if(f)e=!0;else{if("undefined"!==typeof document){var g=new qe(document);f=g.get("SAPISID")||g.get("APISID")||g.get("__Secure-3PAPISID")||g.get("SID")||g.get("OSID");se(e)&&(f=f||g.get("__Secure-1PAPISID"))}e=!!f}e&&(e=(c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:"))?
B.__SAPISID:B.__APISID,e||"undefined"===typeof document||(e=new qe(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID")),(e=e?me(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e),c&&se(b)&&((b=te("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=te("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a)));return 0==d.length?null:d.join(" ")}
;"undefined"!==typeof TextDecoder&&new TextDecoder;var ve="undefined"!==typeof TextEncoder?new TextEncoder:null,we=ve?function(a){return ve.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
128>e?b[c++]=e:(2048>e?b[c++]=e>>6|192:(55296==(e&64512)&&d+1<a.length&&56320==(a.charCodeAt(d+1)&64512)?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function xe(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function ye(){this.Ka=this.Ka;this.oa=this.oa}
ye.prototype.Ka=!1;ye.prototype.dispose=function(){this.Ka||(this.Ka=!0,this.sa())};
ye.prototype.sa=function(){if(this.oa)for(;this.oa.length;)this.oa.shift()()};function ze(a,b){this.type=a;this.g=this.target=b;this.defaultPrevented=this.i=!1}
ze.prototype.stopPropagation=function(){this.i=!0};
ze.prototype.preventDefault=function(){this.defaultPrevented=!0};var Ae=function(){if(!B.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
B.addEventListener("test",c,b);B.removeEventListener("test",c,b)}catch(d){}return a}();function Be(a,b){ze.call(this,a?a.type:"");this.relatedTarget=this.g=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.h=null;a&&this.init(a,b)}
Va(Be,ze);var Ce={2:"touch",3:"pen",4:"mouse"};
Be.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.g=b;if(b=a.relatedTarget){if(ic){a:{try{ec(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Ce[a.pointerType]||"";this.state=a.state;
this.h=a;a.defaultPrevented&&Be.na.preventDefault.call(this)};
Be.prototype.stopPropagation=function(){Be.na.stopPropagation.call(this);this.h.stopPropagation?this.h.stopPropagation():this.h.cancelBubble=!0};
Be.prototype.preventDefault=function(){Be.na.preventDefault.call(this);var a=this.h;a.preventDefault?a.preventDefault():a.returnValue=!1};var De="closure_listenable_"+(1E6*Math.random()|0);var Ee=0;function Ie(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.Eb=e;this.key=++Ee;this.ub=this.zb=!1}
function Je(a){a.ub=!0;a.listener=null;a.proxy=null;a.src=null;a.Eb=null}
;function Ke(a){this.src=a;this.listeners={};this.g=0}
Ke.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.g++);var g=Le(a,b,d,e);-1<g?(b=a[g],c||(b.zb=!1)):(b=new Ie(b,this.src,f,!!d,e),b.zb=c,a.push(b));return b};
Ke.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Le(e,b,c,d);return-1<b?(Je(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.g--),!0):!1};
function Me(a,b){var c=b.type;c in a.listeners&&cb(a.listeners[c],b)&&(Je(b),0==a.listeners[c].length&&(delete a.listeners[c],a.g--))}
function Le(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.ub&&f.listener==b&&f.capture==!!c&&f.Eb==d)return e}return-1}
;var Ne="closure_lm_"+(1E6*Math.random()|0),Oe={},Pe=0;function Qe(a,b,c,d,e){if(d&&d.once)Re(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Qe(a,b[f],c,d,e);else c=Se(c),a&&a[De]?a.Oa(b,c,Ma(d)?!!d.capture:!!d,e):Te(a,b,c,!1,d,e)}
function Te(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Ma(e)?!!e.capture:!!e,h=Ue(a);h||(a[Ne]=h=new Ke(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Ve();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Ae||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(We(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Pe++}}
function Ve(){function a(c){return b.call(a.src,a.listener,c)}
var b=Xe;return a}
function Re(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Re(a,b[f],c,d,e);else c=Se(c),a&&a[De]?a.g.add(String(b),c,!0,Ma(d)?!!d.capture:!!d,e):Te(a,b,c,!0,d,e)}
function Ye(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ye(a,b[f],c,d,e);else(d=Ma(d)?!!d.capture:!!d,c=Se(c),a&&a[De])?a.g.remove(String(b),c,d,e):a&&(a=Ue(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Le(b,c,d,e)),(c=-1<a?b[a]:null)&&Ze(c))}
function Ze(a){if("number"!==typeof a&&a&&!a.ub){var b=a.src;if(b&&b[De])Me(b.g,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(We(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Pe--;(c=Ue(b))?(Me(c,a),0==c.g&&(c.src=null,b[Ne]=null)):Je(a)}}}
function We(a){return a in Oe?Oe[a]:Oe[a]="on"+a}
function Xe(a,b){if(a.ub)a=!0;else{b=new Be(b,this);var c=a.listener,d=a.Eb||a.src;a.zb&&Ze(a);a=c.call(d,b)}return a}
function Ue(a){a=a[Ne];return a instanceof Ke?a:null}
var $e="__closure_events_fn_"+(1E9*Math.random()>>>0);function Se(a){if("function"===typeof a)return a;a[$e]||(a[$e]=function(b){return a.handleEvent(b)});
return a[$e]}
;function af(){ye.call(this);this.g=new Ke(this);this.M=this;this.u=null}
Va(af,ye);af.prototype[De]=!0;af.prototype.addEventListener=function(a,b,c,d){Qe(this,a,b,c,d)};
af.prototype.removeEventListener=function(a,b,c,d){Ye(this,a,b,c,d)};
function bf(a,b){var c=a.u;if(c){var d=[];for(var e=1;c;c=c.u)d.push(c),++e}a=a.M;c=b.type||b;"string"===typeof b?b=new ze(b,a):b instanceof ze?b.target=b.target||a:(e=b,b=new ze(c,a),ob(b,e));e=!0;if(d)for(var f=d.length-1;!b.i&&0<=f;f--){var g=b.g=d[f];e=cf(g,c,!0,b)&&e}b.i||(g=b.g=a,e=cf(g,c,!0,b)&&e,b.i||(e=cf(g,c,!1,b)&&e));if(d)for(f=0;!b.i&&f<d.length;f++)g=b.g=d[f],e=cf(g,c,!1,b)&&e}
af.prototype.sa=function(){af.na.sa.call(this);if(this.g){var a=this.g,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Je(d[e]);delete a.listeners[c];a.g--}}this.u=null};
af.prototype.Oa=function(a,b,c,d){return this.g.add(String(a),b,!1,c,d)};
function cf(a,b,c,d){b=a.g.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.ub&&g.capture==c){var h=g.listener,k=g.Eb||g.src;g.zb&&Me(a.g,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function df(a){af.call(this);var b=this;this.H=this.i=0;this.ha=null!=a?a:{qa:function(e,f){return setTimeout(e,f)},
ba:function(e){clearTimeout(e)}};
var c,d;this.h=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.j=function(){return A(function(e){return z(e,ef(b),0)})};
window.addEventListener("offline",this.j);window.addEventListener("online",this.j);this.H||ff(this)}
w(df,af);function gf(){var a=hf;df.g||(df.g=new df(a));return df.g}
df.prototype.dispose=function(){window.removeEventListener("offline",this.j);window.removeEventListener("online",this.j);this.ha.ba(this.H);delete df.g};
df.prototype.ca=function(){return this.h};
function ff(a){a.H=a.ha.qa(function(){var b;return A(function(c){if(1==c.g)return a.h?(null==(b=window.navigator)?0:b.onLine)?c.B(3):z(c,ef(a),3):z(c,ef(a),3);ff(a);c.g=0})},3E4)}
function ef(a,b){return a.o?a.o:a.o=new Promise(function(c){var d,e,f,g;return A(function(h){switch(h.g){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,va(h,2,3),d&&(a.i=a.ha.qa(function(){d.abort()},b||2E4)),z(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.S=[h.i];h.o=0;h.u=0;a.o=void 0;a.i&&(a.ha.ba(a.i),a.i=0);g!==a.h&&(a.h=g,a.h?bf(a,"networkstatus-online"):bf(a,"networkstatus-offline"));c(g);xa(h);break;case 2:wa(h),g=!1,h.B(3)}})})}
;function jf(){this.data=[];this.g=-1}
jf.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.g=-1)};
jf.prototype.get=function(a){return!!this.data[a]};
function kf(a){-1===a.g&&(a.g=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.g}
;function lf(a){this.s=H(a)}
w(lf,K);function mf(a){this.s=H(a)}
w(mf,K);function nf(a,b){return J(a,2,b)}
function of(a,b){return J(a,3,b)}
function pf(a,b){return J(a,4,b)}
function qf(a,b){return J(a,5,b)}
function rf(a,b){return J(a,9,b)}
function sf(a,b){var c=a.s,d=Lc(c);Xc(d);if(null!=b){for(var e=!!b.length,f=0;f<b.length;f++){var g=b[f];ed(g,lf);e=e&&!(G(g.s)&2)}f=G(b);g=f|1;g=(e?g|8:g&-9)|4;g!=f&&(b=Mc(b,g))}null==b&&(b=void 0);xd(c,d,10,b);return a}
function tf(a,b){return wd(a,11,null==b?b:Zc(b))}
function uf(a,b){return J(a,1,b)}
function vf(a,b){return wd(a,7,null==b?b:Zc(b))}
mf.ma=[10,6];var wf="platform platformVersion architecture model uaFullVersion bitness fullVersionList wow64".split(" ");function xf(a){var b;return null!=(b=a.google_tag_data)?b:a.google_tag_data={}}
function yf(a){var b,c;return"function"===typeof(null==(b=a.navigator)?void 0:null==(c=b.userAgentData)?void 0:c.getHighEntropyValues)}
function zf(){var a=window;if(!yf(a))return null;var b=xf(a);if(b.uach_promise)return b.uach_promise;a=a.navigator.userAgentData.getHighEntropyValues(wf).then(function(c){null!=b.uach||(b.uach=c);return c});
return b.uach_promise=a}
function Af(a){var b;return tf(sf(qf(nf(uf(pf(vf(rf(of(new mf,a.architecture||""),a.bitness||""),a.mobile||!1),a.model||""),a.platform||""),a.platformVersion||""),a.uaFullVersion||""),(null==(b=a.fullVersionList)?void 0:b.map(function(c){var d=new lf;d=J(d,1,c.brand);return J(d,2,c.version)}))||[]),a.wow64||!1)}
function Bf(){var a,b;return null!=(b=null==(a=zf())?void 0:a.then(function(c){return Af(c)}))?b:null}
;function Cf(a,b){this.i=a;this.j=b;this.h=0;this.g=null}
Cf.prototype.get=function(){if(0<this.h){this.h--;var a=this.g;this.g=a.next;a.next=null}else a=this.i();return a};
function Df(a,b){a.j(b);100>a.h&&(a.h++,b.next=a.g,a.g=b)}
;var Ef;function Ff(){var a=B.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!E("Presto")&&(a=function(){var e=Pd();e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Ta(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Rb()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.mc;c.mc=null;e()}};
return function(e){d.next={mc:e};d=d.next;b.port2.postMessage(0)}}return function(e){B.setTimeout(e,0)}}
;function Gf(){this.h=this.g=null}
Gf.prototype.add=function(a,b){var c=Hf.get();c.set(a,b);this.h?this.h.next=c:this.g=c;this.h=c};
Gf.prototype.remove=function(){var a=null;this.g&&(a=this.g,this.g=this.g.next,this.g||(this.h=null),a.next=null);return a};
var Hf=new Cf(function(){return new If},function(a){return a.reset()});
function If(){this.next=this.scope=this.g=null}
If.prototype.set=function(a,b){this.g=a;this.scope=b;this.next=null};
If.prototype.reset=function(){this.next=this.scope=this.g=null};var Jf,Kf=!1,Lf=new Gf;function Mf(a,b){Jf||Nf();Kf||(Jf(),Kf=!0);Lf.add(a,b)}
function Nf(){if(B.Promise&&B.Promise.resolve){var a=B.Promise.resolve(void 0);Jf=function(){a.then(Of)}}else Jf=function(){var b=Of;
"function"!==typeof B.setImmediate||B.Window&&B.Window.prototype&&(Lb()||!E("Edge"))&&B.Window.prototype.setImmediate==B.setImmediate?(Ef||(Ef=Ff()),Ef(b)):B.setImmediate(b)}}
function Of(){for(var a;a=Lf.remove();){try{a.g.call(a.scope)}catch(b){cc(b)}Df(Hf,a)}Kf=!1}
;function Pf(a,b){this.g=a[B.Symbol.iterator]();this.h=b}
Pf.prototype[Symbol.iterator]=function(){return this};
Pf.prototype.next=function(){var a=this.g.next();return{value:a.done?void 0:this.h.call(void 0,a.value),done:a.done}};
function Qf(a,b){return new Pf(a,b)}
;function Rf(){this.blockSize=-1}
;function Sf(){this.blockSize=-1;this.blockSize=64;this.g=[];this.o=[];this.u=[];this.i=[];this.i[0]=128;for(var a=1;a<this.blockSize;++a)this.i[a]=0;this.j=this.h=0;this.reset()}
Va(Sf,Rf);Sf.prototype.reset=function(){this.g[0]=1732584193;this.g[1]=4023233417;this.g[2]=2562383102;this.g[3]=271733878;this.g[4]=3285377520;this.j=this.h=0};
function Tf(a,b,c){c||(c=0);var d=a.u;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.g[0];c=a.g[1];var g=a.g[2],h=a.g[3],k=a.g[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.g[0]=a.g[0]+b&4294967295;a.g[1]=a.g[1]+c&4294967295;a.g[2]=a.g[2]+g&4294967295;a.g[3]=a.g[3]+h&4294967295;a.g[4]=a.g[4]+k&4294967295}
Sf.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.o,f=this.h;d<b;){if(0==f)for(;d<=c;)Tf(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Tf(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Tf(this,e);f=0;break}}this.h=f;this.j+=b}};
Sf.prototype.digest=function(){var a=[],b=8*this.j;56>this.h?this.update(this.i,56-this.h):this.update(this.i,this.blockSize-(this.h-56));for(var c=this.blockSize-1;56<=c;c--)this.o[c]=b&255,b/=256;Tf(this,this.o);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.g[c]>>d&255,++b;return a};function Uf(){}
Uf.prototype.next=function(){return Vf};
var Vf={done:!0,value:void 0};function Wf(a){return{value:a,done:!1}}
Uf.prototype.ia=function(){return this};function Xf(a){if(a instanceof Yf||a instanceof Zf||a instanceof $f)return a;if("function"==typeof a.next)return new Yf(function(){return a});
if("function"==typeof a[Symbol.iterator])return new Yf(function(){return a[Symbol.iterator]()});
if("function"==typeof a.ia)return new Yf(function(){return a.ia()});
throw Error("Not an iterator or iterable.");}
function Yf(a){this.h=a}
Yf.prototype.ia=function(){return new Zf(this.h())};
Yf.prototype[Symbol.iterator]=function(){return new $f(this.h())};
Yf.prototype.g=function(){return new $f(this.h())};
function Zf(a){this.h=a}
w(Zf,Uf);Zf.prototype.next=function(){return this.h.next()};
Zf.prototype[Symbol.iterator]=function(){return new $f(this.h)};
Zf.prototype.g=function(){return new $f(this.h)};
function $f(a){Yf.call(this,function(){return a});
this.i=a}
w($f,Yf);$f.prototype.next=function(){return this.i.next()};function ag(a,b){this.h={};this.g=[];this.i=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof ag)for(c=bg(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function bg(a){cg(a);return a.g.concat()}
q=ag.prototype;q.has=function(a){return dg(this.h,a)};
q.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||eg;cg(this);for(var c,d=0;c=this.g[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function eg(a,b){return a===b}
q.Tb=function(){return 0==this.size};
q.clear=function(){this.h={};this.i=this.size=this.g.length=0};
q.remove=function(a){return this.delete(a)};
q.delete=function(a){return dg(this.h,a)?(delete this.h[a],--this.size,this.i++,this.g.length>2*this.size&&cg(this),!0):!1};
function cg(a){if(a.size!=a.g.length){for(var b=0,c=0;b<a.g.length;){var d=a.g[b];dg(a.h,d)&&(a.g[c++]=d);b++}a.g.length=c}if(a.size!=a.g.length){var e={};for(c=b=0;b<a.g.length;)d=a.g[b],dg(e,d)||(a.g[c++]=d,e[d]=1),b++;a.g.length=c}}
q.get=function(a,b){return dg(this.h,a)?this.h[a]:b};
q.set=function(a,b){dg(this.h,a)||(this.size+=1,this.g.push(a),this.i++);this.h[a]=b};
q.forEach=function(a,b){for(var c=bg(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
q.clone=function(){return new ag(this)};
q.keys=function(){return Xf(this.ia(!0)).g()};
q.values=function(){return Xf(this.ia(!1)).g()};
q.entries=function(){var a=this;return Qf(this.keys(),function(b){return[b,a.get(b)]})};
q.ia=function(a){cg(this);var b=0,c=this.i,d=this,e=new Uf;e.next=function(){if(c!=d.i)throw Error("The map has changed since the iterator was created");if(b>=d.g.length)return Vf;var f=d.g[b++];return Wf(a?f:d.h[f])};
return e};
function dg(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;var fg=B.JSON.stringify;function gg(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function hg(a){this.g=0;this.H=void 0;this.j=this.h=this.i=null;this.o=this.u=!1;if(a!=Za)try{var b=this;a.call(void 0,function(c){ig(b,2,c)},function(c){ig(b,3,c)})}catch(c){ig(this,3,c)}}
function jg(){this.next=this.context=this.h=this.i=this.g=null;this.j=!1}
jg.prototype.reset=function(){this.context=this.h=this.i=this.g=null;this.j=!1};
var kg=new Cf(function(){return new jg},function(a){a.reset()});
function lg(a,b,c){var d=kg.get();d.i=a;d.h=b;d.context=c;return d}
hg.prototype.then=function(a,b,c){return mg(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
hg.prototype.$goog_Thenable=!0;hg.prototype.cancel=function(a){if(0==this.g){var b=new ng(a);Mf(function(){og(this,b)},this)}};
function og(a,b){if(0==a.g)if(a.i){var c=a.i;if(c.h){for(var d=0,e=null,f=null,g=c.h;g&&(g.j||(d++,g.g==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.g&&1==d?og(c,b):(f?(d=f,d.next==c.j&&(c.j=d),d.next=d.next.next):pg(c),qg(c,e,3,b)))}a.i=null}else ig(a,3,b)}
function rg(a,b){a.h||2!=a.g&&3!=a.g||sg(a);a.j?a.j.next=b:a.h=b;a.j=b}
function mg(a,b,c,d){var e=lg(null,null,null);e.g=new hg(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof ng?g(h):f(k)}catch(l){g(l)}}:g});
e.g.i=a;rg(a,e);return e.g}
hg.prototype.S=function(a){this.g=0;ig(this,2,a)};
hg.prototype.oa=function(a){this.g=0;ig(this,3,a)};
function ig(a,b,c){if(0==a.g){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.g=1;a:{var d=c,e=a.S,f=a.oa;if(d instanceof hg){rg(d,lg(e||Za,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Ma(d))try{var k=d.then;if("function"===typeof k){tg(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.H=c,a.g=b,a.i=null,sg(a),3!=b||c instanceof ng||ug(a,c))}}
function tg(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function sg(a){a.u||(a.u=!0,Mf(a.M,a))}
function pg(a){var b=null;a.h&&(b=a.h,a.h=b.next,b.next=null);a.h||(a.j=null);return b}
hg.prototype.M=function(){for(var a;a=pg(this);)qg(this,a,this.g,this.H);this.u=!1};
function qg(a,b,c,d){if(3==c&&b.h&&!b.j)for(;a&&a.o;a=a.i)a.o=!1;if(b.g)b.g.i=null,vg(b,c,d);else try{b.j?b.i.call(b.context):vg(b,c,d)}catch(e){wg.call(null,e)}Df(kg,b)}
function vg(a,b,c){2==b?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function ug(a,b){a.o=!0;Mf(function(){a.o&&wg.call(null,b)})}
var wg=cc;function ng(a){Xa.call(this,a)}
Va(ng,Xa);ng.prototype.name="cancel";function L(a){ye.call(this);this.o=1;this.i=[];this.j=0;this.g=[];this.h={};this.u=!!a}
Va(L,ye);q=L.prototype;q.subscribe=function(a,b,c){var d=this.h[a];d||(d=this.h[a]=[]);var e=this.o;this.g[e]=a;this.g[e+1]=b;this.g[e+2]=c;this.o=e+3;d.push(e);return e};
function xg(a,b,c){var d=yg;if(a=d.h[a]){var e=d.g;(a=a.find(function(f){return e[f+1]==b&&e[f+2]==c}))&&d.wb(a)}}
q.wb=function(a){var b=this.g[a];if(b){var c=this.h[b];0!=this.j?(this.i.push(a),this.g[a+1]=function(){}):(c&&cb(c,a),delete this.g[a],delete this.g[a+1],delete this.g[a+2])}return!!b};
q.fb=function(a,b){var c=this.h[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.u)for(e=0;e<c.length;e++){var g=c[e];zg(this.g[g+1],this.g[g+2],d)}else{this.j++;try{for(e=0,f=c.length;e<f&&!this.Ka;e++)g=c[e],this.g[g+1].apply(this.g[g+2],d)}finally{if(this.j--,0<this.i.length&&0==this.j)for(;c=this.i.pop();)this.wb(c)}}return 0!=e}return!1};
function zg(a,b,c){Mf(function(){a.apply(b,c)})}
q.clear=function(a){if(a){var b=this.h[a];b&&(b.forEach(this.wb,this),delete this.h[a])}else this.g.length=0,this.h={}};
q.sa=function(){L.na.sa.call(this);this.clear();this.i.length=0};function Ag(a){this.g=a}
Ag.prototype.set=function(a,b){void 0===b?this.g.remove(a):this.g.set(a,fg(b))};
Ag.prototype.get=function(a){try{var b=this.g.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Ag.prototype.remove=function(a){this.g.remove(a)};function Bg(a){this.g=a}
Va(Bg,Ag);function Cg(a){this.data=a}
function Dg(a){return void 0===a||a instanceof Cg?a:new Cg(a)}
Bg.prototype.set=function(a,b){Bg.na.set.call(this,a,Dg(b))};
Bg.prototype.h=function(a){a=Bg.na.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Bg.prototype.get=function(a){if(a=this.h(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Eg(a){this.g=a}
Va(Eg,Bg);Eg.prototype.set=function(a,b,c){if(b=Dg(b)){if(c){if(c<Ua()){Eg.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Ua()}Eg.na.set.call(this,a,b)};
Eg.prototype.h=function(a){var b=Eg.na.h.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Ua()||c&&c>Ua())Eg.prototype.remove.call(this,a);else return b}};function Fg(){}
;function Gg(){}
Va(Gg,Fg);Gg.prototype[Symbol.iterator]=function(){return Xf(this.ia(!0)).g()};
Gg.prototype.clear=function(){var a=Array.from(this);a=u(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Hg(a){this.g=a}
Va(Hg,Gg);q=Hg.prototype;q.set=function(a,b){try{this.g.setItem(a,b)}catch(c){if(0==this.g.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
q.get=function(a){a=this.g.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
q.remove=function(a){this.g.removeItem(a)};
q.ia=function(a){var b=0,c=this.g,d=new Uf;d.next=function(){if(b>=c.length)return Vf;var e=c.key(b++);if(a)return Wf(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Wf(e)};
return d};
q.clear=function(){this.g.clear()};
q.key=function(a){return this.g.key(a)};function Ig(){var a=null;try{a=window.localStorage||null}catch(b){}this.g=a}
Va(Ig,Hg);function Jg(a,b){this.h=a;this.g=null;var c;if(c=gc)c=!(9<=Number(wc));if(c){Kg||(Kg=new ag);this.g=Kg.get(a);this.g||(b?this.g=document.getElementById(b):(this.g=document.createElement("userdata"),this.g.addBehavior("#default#userData"),document.body.appendChild(this.g)),Kg.set(a,this.g));try{this.g.load(this.h)}catch(d){this.g=null}}}
Va(Jg,Gg);var Lg={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Kg=null;function Mg(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Lg[b]})}
q=Jg.prototype;q.set=function(a,b){this.g.setAttribute(Mg(a),b);Ng(this)};
q.get=function(a){a=this.g.getAttribute(Mg(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
q.remove=function(a){this.g.removeAttribute(Mg(a));Ng(this)};
q.ia=function(a){var b=0,c=this.g.XMLDocument.documentElement.attributes,d=new Uf;d.next=function(){if(b>=c.length)return Vf;var e=c[b++];if(a)return Wf(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Wf(e)};
return d};
q.clear=function(){for(var a=this.g.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Ng(this)};
function Ng(a){try{a.g.save(a.h)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Og(a,b){this.h=a;this.g=b+"::"}
Va(Og,Gg);Og.prototype.set=function(a,b){this.h.set(this.g+a,b)};
Og.prototype.get=function(a){return this.h.get(this.g+a)};
Og.prototype.remove=function(a){this.h.remove(this.g+a)};
Og.prototype.ia=function(a){var b=this.h[Symbol.iterator](),c=this,d=new Uf;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.g.length)!=c.g;){e=b.next();if(e.done)return e;e=e.value}return Wf(a?e.slice(c.g.length):c.h.get(e))};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var N={},Pg="undefined"!==typeof Uint8Array&&"undefined"!==typeof Uint16Array&&"undefined"!==typeof Int32Array;N.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if("object"!==typeof c)throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
N.ec=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var Qg={Ua:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
qc:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},Rg={Ua:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
qc:function(a){return[].concat.apply([],a)}};
N.Bd=function(){Pg?(N.Ta=Uint8Array,N.pa=Uint16Array,N.Pc=Int32Array,N.assign(N,Qg)):(N.Ta=Array,N.pa=Array,N.Pc=Array,N.assign(N,Rg))};
N.Bd();var Sg=!0;try{new Uint8Array(1)}catch(a){Sg=!1}
function Tg(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if(55296===(f&64512)&&b+1<d){var g=a.charCodeAt(b+1);56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=128>f?1:2048>f?2:65536>f?3:4}var h=new N.Ta(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),55296===(f&64512)&&b+1<d&&(g=a.charCodeAt(b+1),56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)),128>f?h[c++]=f:(2048>f?h[c++]=192|f>>>6:(65536>f?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var Ug={};Ug=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;0!==c;){f=2E3<c?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var Vg={},Wg,Xg=[],Yg=0;256>Yg;Yg++){Wg=Yg;for(var Zg=0;8>Zg;Zg++)Wg=Wg&1?3988292384^Wg>>>1:Wg>>>1;Xg[Yg]=Wg}Vg=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^Xg[(a^b[d])&255];return a^-1};var $g={};$g={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function ah(a){for(var b=a.length;0<=--b;)a[b]=0}
var bh=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],ch=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],dh=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],eh=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],fh=Array(576);ah(fh);var gh=Array(60);ah(gh);var hh=Array(512);ah(hh);var ih=Array(256);ah(ih);var jh=Array(29);ah(jh);var kh=Array(30);ah(kh);function lh(a,b,c,d,e){this.Lc=a;this.ed=b;this.dd=c;this.bd=d;this.vd=e;this.vc=a&&a.length}
var mh,nh,oh;function ph(a,b){this.oc=a;this.bb=0;this.Ea=b}
function qh(a,b){a.K[a.pending++]=b&255;a.K[a.pending++]=b>>>8&255}
function rh(a,b,c){a.O>16-c?(a.V|=b<<a.O&65535,qh(a,a.V),a.V=b>>16-a.O,a.O+=c-16):(a.V|=b<<a.O&65535,a.O+=c)}
function sh(a,b,c){rh(a,c[2*b],c[2*b+1])}
function th(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(0<--b);return c>>>1}
function Ph(a,b,c){var d=Array(16),e=0,f;for(f=1;15>=f;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[2*c+1],0!==e&&(a[2*c]=th(d[e]++,e))}
function Qh(a){var b;for(b=0;286>b;b++)a.X[2*b]=0;for(b=0;30>b;b++)a.La[2*b]=0;for(b=0;19>b;b++)a.R[2*b]=0;a.X[512]=1;a.xa=a.gb=0;a.da=a.matches=0}
function Rh(a){8<a.O?qh(a,a.V):0<a.O&&(a.K[a.pending++]=a.V);a.V=0;a.O=0}
function Sh(a,b,c){Rh(a);qh(a,c);qh(a,~c);N.Ua(a.K,a.window,b,c,a.pending);a.pending+=c}
function Th(a,b,c,d){var e=2*b,f=2*c;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Uh(a,b,c){for(var d=a.L[c],e=c<<1;e<=a.wa;){e<a.wa&&Th(b,a.L[e+1],a.L[e],a.depth)&&e++;if(Th(b,d,a.L[e],a.depth))break;a.L[c]=a.L[e];c=e;e<<=1}a.L[c]=d}
function Vh(a,b,c){var d=0;if(0!==a.da){do{var e=a.K[a.ob+2*d]<<8|a.K[a.ob+2*d+1];var f=a.K[a.Vb+d];d++;if(0===e)sh(a,f,b);else{var g=ih[f];sh(a,g+256+1,b);var h=bh[g];0!==h&&(f-=jh[g],rh(a,f,h));e--;g=256>e?hh[e]:hh[256+(e>>>7)];sh(a,g,c);h=ch[g];0!==h&&(e-=kh[g],rh(a,e,h))}}while(d<a.da)}sh(a,256,b)}
function Wh(a,b){var c=b.oc,d=b.Ea.Lc,e=b.Ea.vc,f=b.Ea.bd,g,h=-1;a.wa=0;a.Xa=573;for(g=0;g<f;g++)0!==c[2*g]?(a.L[++a.wa]=h=g,a.depth[g]=0):c[2*g+1]=0;for(;2>a.wa;){var k=a.L[++a.wa]=2>h?++h:0;c[2*k]=1;a.depth[k]=0;a.xa--;e&&(a.gb-=d[2*k+1])}b.bb=h;for(g=a.wa>>1;1<=g;g--)Uh(a,c,g);k=f;do g=a.L[1],a.L[1]=a.L[a.wa--],Uh(a,c,1),d=a.L[1],a.L[--a.Xa]=g,a.L[--a.Xa]=d,c[2*k]=c[2*g]+c[2*d],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[2*g+1]=c[2*d+1]=k,a.L[1]=k++,Uh(a,c,1);while(2<=a.wa);a.L[--a.Xa]=
a.L[1];g=b.oc;k=b.bb;d=b.Ea.Lc;e=b.Ea.vc;f=b.Ea.ed;var l=b.Ea.dd,m=b.Ea.vd,n,r=0;for(n=0;15>=n;n++)a.ra[n]=0;g[2*a.L[a.Xa]+1]=0;for(b=a.Xa+1;573>b;b++){var p=a.L[b];n=g[2*g[2*p+1]+1]+1;n>m&&(n=m,r++);g[2*p+1]=n;if(!(p>k)){a.ra[n]++;var x=0;p>=l&&(x=f[p-l]);var y=g[2*p];a.xa+=y*(n+x);e&&(a.gb+=y*(d[2*p+1]+x))}}if(0!==r){do{for(n=m-1;0===a.ra[n];)n--;a.ra[n]--;a.ra[n+1]+=2;a.ra[m]--;r-=2}while(0<r);for(n=m;0!==n;n--)for(p=a.ra[n];0!==p;)d=a.L[--b],d>k||(g[2*d+1]!==n&&(a.xa+=(n-g[2*d+1])*g[2*d],g[2*
d+1]=n),p--)}Ph(c,h,a.ra)}
function Xh(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);b[2*(c+1)+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[2*(d+1)+1];++g<h&&l===f||(g<k?a.R[2*l]+=g:0!==l?(l!==e&&a.R[2*l]++,a.R[32]++):10>=g?a.R[34]++:a.R[36]++,g=0,e=l,0===f?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function Yh(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[2*(d+1)+1];if(!(++g<h&&l===f)){if(g<k){do sh(a,l,a.R);while(0!==--g)}else 0!==l?(l!==e&&(sh(a,l,a.R),g--),sh(a,16,a.R),rh(a,g-3,2)):10>=g?(sh(a,17,a.R),rh(a,g-3,3)):(sh(a,18,a.R),rh(a,g-11,7));g=0;e=l;0===f?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function Zh(a){var b=4093624447,c;for(c=0;31>=c;c++,b>>>=1)if(b&1&&0!==a.X[2*c])return 0;if(0!==a.X[18]||0!==a.X[20]||0!==a.X[26])return 1;for(c=32;256>c;c++)if(0!==a.X[2*c])return 1;return 0}
var $h=!1;function ai(a,b,c){a.K[a.ob+2*a.da]=b>>>8&255;a.K[a.ob+2*a.da+1]=b&255;a.K[a.Vb+a.da]=c&255;a.da++;0===b?a.X[2*c]++:(a.matches++,b--,a.X[2*(ih[c]+256+1)]++,a.La[2*(256>b?hh[b]:hh[256+(b>>>7)])]++);return a.da===a.rb-1}
;function bi(a,b){a.msg=$g[b];return b}
function ci(a){for(var b=a.length;0<=--b;)a[b]=0}
function di(a){var b=a.state,c=b.pending;c>a.F&&(c=a.F);0!==c&&(N.Ua(a.output,b.K,b.tb,c,a.cb),a.cb+=c,b.tb+=c,a.fc+=c,a.F-=c,b.pending-=c,0===b.pending&&(b.tb=0))}
function P(a,b){var c=0<=a.Z?a.Z:-1,d=a.l-a.Z,e=0;if(0<a.level){2===a.C.Qb&&(a.C.Qb=Zh(a));Wh(a,a.Gb);Wh(a,a.Cb);Xh(a,a.X,a.Gb.bb);Xh(a,a.La,a.Cb.bb);Wh(a,a.kc);for(e=18;3<=e&&0===a.R[2*eh[e]+1];e--);a.xa+=3*(e+1)+14;var f=a.xa+3+7>>>3;var g=a.gb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&-1!==c)rh(a,b?1:0,3),Sh(a,c,d);else if(4===a.strategy||g===f)rh(a,2+(b?1:0),3),Vh(a,fh,gh);else{rh(a,4+(b?1:0),3);c=a.Gb.bb+1;d=a.Cb.bb+1;e+=1;rh(a,c-257,5);rh(a,d-1,5);rh(a,e-4,4);for(f=0;f<e;f++)rh(a,a.R[2*eh[f]+
1],3);Yh(a,a.X,c-1);Yh(a,a.La,d-1);Vh(a,a.X,a.La)}Qh(a);b&&Rh(a);a.Z=a.l;di(a.C)}
function R(a,b){a.K[a.pending++]=b}
function ei(a,b){a.K[a.pending++]=b>>>8&255;a.K[a.pending++]=b&255}
function fi(a,b){var c=a.Bc,d=a.l,e=a.aa,f=a.Dc,g=a.l>a.T-262?a.l-(a.T-262):0,h=a.window,k=a.Ga,l=a.la,m=a.l+258,n=h[d+e-1],r=h[d+e];a.aa>=a.uc&&(c>>=2);f>a.m&&(f=a.m);do{var p=b;if(h[p+e]===r&&h[p+e-1]===n&&h[p]===h[d]&&h[++p]===h[d+1]){d+=2;for(p++;h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&h[++d]===h[++p]&&d<m;);p=258-(m-d);d=m-258;if(p>e){a.ab=b;e=p;if(p>=f)break;n=h[d+e-1];r=h[d+e]}}}while((b=l[b&k])>g&&0!==--c);return e<=
a.m?e:a.m}
function gi(a){var b=a.T,c;do{var d=a.Nc-a.m-a.l;if(a.l>=b+(b-262)){N.Ua(a.window,a.window,b,b,0);a.ab-=b;a.l-=b;a.Z-=b;var e=c=a.Fb;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.la[--e],a.la[e]=f>=b?f-b:0;while(--c);d+=b}if(0===a.C.U)break;e=a.C;c=a.window;f=a.l+a.m;var g=e.U;g>d&&(g=d);0===g?c=0:(e.U-=g,N.Ua(c,e.input,e.Ra,g,f),1===e.state.wrap?e.A=Ug(e.A,c,g,f):2===e.state.wrap&&(e.A=Vg(e.A,c,g,f)),e.Ra+=g,e.Sa+=g,c=g);a.m+=c;if(3<=a.m+a.Y)for(d=a.l-a.Y,a.D=a.window[d],a.D=
(a.D<<a.va^a.window[d+1])&a.ta;a.Y&&!(a.D=(a.D<<a.va^a.window[d+3-1])&a.ta,a.la[d&a.Ga]=a.head[a.D],a.head[a.D]=d,d++,a.Y--,3>a.m+a.Y););}while(262>a.m&&0!==a.C.U)}
function hi(a,b){for(var c;;){if(262>a.m){gi(a);if(262>a.m&&0===b)return 1;if(0===a.m)break}c=0;3<=a.m&&(a.D=(a.D<<a.va^a.window[a.l+3-1])&a.ta,c=a.la[a.l&a.Ga]=a.head[a.D],a.head[a.D]=a.l);0!==c&&a.l-c<=a.T-262&&(a.G=fi(a,c));if(3<=a.G)if(c=ai(a,a.l-a.ab,a.G-3),a.m-=a.G,a.G<=a.Xb&&3<=a.m){a.G--;do a.l++,a.D=(a.D<<a.va^a.window[a.l+3-1])&a.ta,a.la[a.l&a.Ga]=a.head[a.D],a.head[a.D]=a.l;while(0!==--a.G);a.l++}else a.l+=a.G,a.G=0,a.D=a.window[a.l],a.D=(a.D<<a.va^a.window[a.l+1])&a.ta;else c=ai(a,0,a.window[a.l]),
a.m--,a.l++;if(c&&(P(a,!1),0===a.C.F))return 1}a.Y=2>a.l?a.l:2;return 4===b?(P(a,!0),0===a.C.F?3:4):a.da&&(P(a,!1),0===a.C.F)?1:2}
function ii(a,b){for(var c,d;;){if(262>a.m){gi(a);if(262>a.m&&0===b)return 1;if(0===a.m)break}c=0;3<=a.m&&(a.D=(a.D<<a.va^a.window[a.l+3-1])&a.ta,c=a.la[a.l&a.Ga]=a.head[a.D],a.head[a.D]=a.l);a.aa=a.G;a.Gc=a.ab;a.G=2;0!==c&&a.aa<a.Xb&&a.l-c<=a.T-262&&(a.G=fi(a,c),5>=a.G&&(1===a.strategy||3===a.G&&4096<a.l-a.ab)&&(a.G=2));if(3<=a.aa&&a.G<=a.aa){d=a.l+a.m-3;c=ai(a,a.l-1-a.Gc,a.aa-3);a.m-=a.aa-1;a.aa-=2;do++a.l<=d&&(a.D=(a.D<<a.va^a.window[a.l+3-1])&a.ta,a.la[a.l&a.Ga]=a.head[a.D],a.head[a.D]=a.l);while(0!==
--a.aa);a.Pa=0;a.G=2;a.l++;if(c&&(P(a,!1),0===a.C.F))return 1}else if(a.Pa){if((c=ai(a,0,a.window[a.l-1]))&&P(a,!1),a.l++,a.m--,0===a.C.F)return 1}else a.Pa=1,a.l++,a.m--}a.Pa&&(ai(a,0,a.window[a.l-1]),a.Pa=0);a.Y=2>a.l?a.l:2;return 4===b?(P(a,!0),0===a.C.F?3:4):a.da&&(P(a,!1),0===a.C.F)?1:2}
function ji(a,b){for(var c,d,e,f=a.window;;){if(258>=a.m){gi(a);if(258>=a.m&&0===b)return 1;if(0===a.m)break}a.G=0;if(3<=a.m&&0<a.l&&(d=a.l-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.l+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.G=258-(e-d);a.G>a.m&&(a.G=a.m)}3<=a.G?(c=ai(a,1,a.G-3),a.m-=a.G,a.l+=a.G,a.G=0):(c=ai(a,0,a.window[a.l]),a.m--,a.l++);if(c&&(P(a,!1),0===a.C.F))return 1}a.Y=0;return 4===b?(P(a,!0),0===a.C.F?3:4):a.da&&
(P(a,!1),0===a.C.F)?1:2}
function ki(a,b){for(var c;;){if(0===a.m&&(gi(a),0===a.m)){if(0===b)return 1;break}a.G=0;c=ai(a,0,a.window[a.l]);a.m--;a.l++;if(c&&(P(a,!1),0===a.C.F))return 1}a.Y=0;return 4===b?(P(a,!0),0===a.C.F?3:4):a.da&&(P(a,!1),0===a.C.F)?1:2}
function li(a,b,c,d,e){this.hd=a;this.ud=b;this.xd=c;this.td=d;this.fd=e}
var mi;mi=[new li(0,0,0,0,function(a,b){var c=65535;for(c>a.ea-5&&(c=a.ea-5);;){if(1>=a.m){gi(a);if(0===a.m&&0===b)return 1;if(0===a.m)break}a.l+=a.m;a.m=0;var d=a.Z+c;if(0===a.l||a.l>=d)if(a.m=a.l-d,a.l=d,P(a,!1),0===a.C.F)return 1;if(a.l-a.Z>=a.T-262&&(P(a,!1),0===a.C.F))return 1}a.Y=0;if(4===b)return P(a,!0),0===a.C.F?3:4;a.l>a.Z&&P(a,!1);return 1}),
new li(4,4,8,4,hi),new li(4,5,16,8,hi),new li(4,6,32,32,hi),new li(4,4,16,16,ii),new li(8,16,32,32,ii),new li(8,16,128,128,ii),new li(8,32,128,256,ii),new li(32,128,258,1024,ii),new li(32,258,258,4096,ii)];
function ni(){this.C=null;this.status=0;this.K=null;this.wrap=this.pending=this.tb=this.ea=0;this.v=null;this.fa=0;this.method=8;this.Ya=-1;this.Ga=this.hc=this.T=0;this.window=null;this.Nc=0;this.head=this.la=null;this.Dc=this.uc=this.strategy=this.level=this.Xb=this.Bc=this.aa=this.m=this.ab=this.l=this.Pa=this.Gc=this.G=this.Z=this.va=this.ta=this.Rb=this.Fb=this.D=0;this.X=new N.pa(1146);this.La=new N.pa(122);this.R=new N.pa(78);ci(this.X);ci(this.La);ci(this.R);this.kc=this.Cb=this.Gb=null;this.ra=
new N.pa(16);this.L=new N.pa(573);ci(this.L);this.Xa=this.wa=0;this.depth=new N.pa(573);ci(this.depth);this.O=this.V=this.Y=this.matches=this.gb=this.xa=this.ob=this.da=this.rb=this.Vb=0}
function oi(a,b){if(!a||!a.state||5<b||0>b)return a?bi(a,-2):-2;var c=a.state;if(!a.output||!a.input&&0!==a.U||666===c.status&&4!==b)return bi(a,0===a.F?-5:-2);c.C=a;var d=c.Ya;c.Ya=b;if(42===c.status)if(2===c.wrap)a.A=0,R(c,31),R(c,139),R(c,8),c.v?(R(c,(c.v.text?1:0)+(c.v.Ca?2:0)+(c.v.Ba?4:0)+(c.v.name?8:0)+(c.v.comment?16:0)),R(c,c.v.time&255),R(c,c.v.time>>8&255),R(c,c.v.time>>16&255),R(c,c.v.time>>24&255),R(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),R(c,c.v.se&255),c.v.Ba&&c.v.Ba.length&&(R(c,
c.v.Ba.length&255),R(c,c.v.Ba.length>>8&255)),c.v.Ca&&(a.A=Vg(a.A,c.K,c.pending,0)),c.fa=0,c.status=69):(R(c,0),R(c,0),R(c,0),R(c,0),R(c,0),R(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),R(c,3),c.status=113);else{var e=8+(c.hc-8<<4)<<8;e|=(2<=c.strategy||2>c.level?0:6>c.level?1:6===c.level?2:3)<<6;0!==c.l&&(e|=32);c.status=113;ei(c,e+(31-e%31));0!==c.l&&(ei(c,a.A>>>16),ei(c,a.A&65535));a.A=1}if(69===c.status)if(c.v.Ba){for(e=c.pending;c.fa<(c.v.Ba.length&65535)&&(c.pending!==c.ea||(c.v.Ca&&c.pending>
e&&(a.A=Vg(a.A,c.K,c.pending-e,e)),di(a),e=c.pending,c.pending!==c.ea));)R(c,c.v.Ba[c.fa]&255),c.fa++;c.v.Ca&&c.pending>e&&(a.A=Vg(a.A,c.K,c.pending-e,e));c.fa===c.v.Ba.length&&(c.fa=0,c.status=73)}else c.status=73;if(73===c.status)if(c.v.name){e=c.pending;do{if(c.pending===c.ea&&(c.v.Ca&&c.pending>e&&(a.A=Vg(a.A,c.K,c.pending-e,e)),di(a),e=c.pending,c.pending===c.ea)){var f=1;break}f=c.fa<c.v.name.length?c.v.name.charCodeAt(c.fa++)&255:0;R(c,f)}while(0!==f);c.v.Ca&&c.pending>e&&(a.A=Vg(a.A,c.K,c.pending-
e,e));0===f&&(c.fa=0,c.status=91)}else c.status=91;if(91===c.status)if(c.v.comment){e=c.pending;do{if(c.pending===c.ea&&(c.v.Ca&&c.pending>e&&(a.A=Vg(a.A,c.K,c.pending-e,e)),di(a),e=c.pending,c.pending===c.ea)){f=1;break}f=c.fa<c.v.comment.length?c.v.comment.charCodeAt(c.fa++)&255:0;R(c,f)}while(0!==f);c.v.Ca&&c.pending>e&&(a.A=Vg(a.A,c.K,c.pending-e,e));0===f&&(c.status=103)}else c.status=103;103===c.status&&(c.v.Ca?(c.pending+2>c.ea&&di(a),c.pending+2<=c.ea&&(R(c,a.A&255),R(c,a.A>>8&255),a.A=0,
c.status=113)):c.status=113);if(0!==c.pending){if(di(a),0===a.F)return c.Ya=-1,0}else if(0===a.U&&(b<<1)-(4<b?9:0)<=(d<<1)-(4<d?9:0)&&4!==b)return bi(a,-5);if(666===c.status&&0!==a.U)return bi(a,-5);if(0!==a.U||0!==c.m||0!==b&&666!==c.status){d=2===c.strategy?ki(c,b):3===c.strategy?ji(c,b):mi[c.level].fd(c,b);if(3===d||4===d)c.status=666;if(1===d||3===d)return 0===a.F&&(c.Ya=-1),0;if(2===d&&(1===b?(rh(c,2,3),sh(c,256,fh),16===c.O?(qh(c,c.V),c.V=0,c.O=0):8<=c.O&&(c.K[c.pending++]=c.V&255,c.V>>=8,c.O-=
8)):5!==b&&(rh(c,0,3),Sh(c,0,0),3===b&&(ci(c.head),0===c.m&&(c.l=0,c.Z=0,c.Y=0))),di(a),0===a.F))return c.Ya=-1,0}if(4!==b)return 0;if(0>=c.wrap)return 1;2===c.wrap?(R(c,a.A&255),R(c,a.A>>8&255),R(c,a.A>>16&255),R(c,a.A>>24&255),R(c,a.Sa&255),R(c,a.Sa>>8&255),R(c,a.Sa>>16&255),R(c,a.Sa>>24&255)):(ei(c,a.A>>>16),ei(c,a.A&65535));di(a);0<c.wrap&&(c.wrap=-c.wrap);return 0!==c.pending?0:1}
;var pi={};pi=function(){this.input=null;this.Sa=this.U=this.Ra=0;this.output=null;this.fc=this.F=this.cb=0;this.msg="";this.state=null;this.Qb=2;this.A=0};var qi=Object.prototype.toString;
function ri(a){if(!(this instanceof ri))return new ri(a);a=this.options=N.assign({level:-1,method:8,chunkSize:16384,Ha:15,wd:8,strategy:0,Fa:""},a||{});a.raw&&0<a.Ha?a.Ha=-a.Ha:a.jd&&0<a.Ha&&16>a.Ha&&(a.Ha+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.C=new pi;this.C.F=0;var b=this.C;var c=a.level,d=a.method,e=a.Ha,f=a.wd,g=a.strategy;if(b){var h=1;-1===c&&(c=6);0>e?(h=0,e=-e):15<e&&(h=2,e-=16);if(1>f||9<f||8!==d||8>e||15<e||0>c||9<c||0>g||4<g)b=bi(b,-2);else{8===e&&(e=9);var k=new ni;
b.state=k;k.C=b;k.wrap=h;k.v=null;k.hc=e;k.T=1<<k.hc;k.Ga=k.T-1;k.Rb=f+7;k.Fb=1<<k.Rb;k.ta=k.Fb-1;k.va=~~((k.Rb+3-1)/3);k.window=new N.Ta(2*k.T);k.head=new N.pa(k.Fb);k.la=new N.pa(k.T);k.rb=1<<f+6;k.ea=4*k.rb;k.K=new N.Ta(k.ea);k.ob=1*k.rb;k.Vb=3*k.rb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.Sa=b.fc=0;b.Qb=2;c=b.state;c.pending=0;c.tb=0;0>c.wrap&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.A=2===c.wrap?0:1;c.Ya=0;if(!$h){d=Array(16);for(f=g=0;28>f;f++)for(jh[f]=g,e=0;e<1<<bh[f];e++)ih[g++]=
f;ih[g-1]=f;for(f=g=0;16>f;f++)for(kh[f]=g,e=0;e<1<<ch[f];e++)hh[g++]=f;for(g>>=7;30>f;f++)for(kh[f]=g<<7,e=0;e<1<<ch[f]-7;e++)hh[256+g++]=f;for(e=0;15>=e;e++)d[e]=0;for(e=0;143>=e;)fh[2*e+1]=8,e++,d[8]++;for(;255>=e;)fh[2*e+1]=9,e++,d[9]++;for(;279>=e;)fh[2*e+1]=7,e++,d[7]++;for(;287>=e;)fh[2*e+1]=8,e++,d[8]++;Ph(fh,287,d);for(e=0;30>e;e++)gh[2*e+1]=5,gh[2*e]=th(e,5);mh=new lh(fh,bh,257,286,15);nh=new lh(gh,ch,0,30,15);oh=new lh([],dh,0,19,7);$h=!0}c.Gb=new ph(c.X,mh);c.Cb=new ph(c.La,nh);c.kc=new ph(c.R,
oh);c.V=0;c.O=0;Qh(c);c=0}else c=bi(b,-2);0===c&&(b=b.state,b.Nc=2*b.T,ci(b.head),b.Xb=mi[b.level].ud,b.uc=mi[b.level].hd,b.Dc=mi[b.level].xd,b.Bc=mi[b.level].td,b.l=0,b.Z=0,b.m=0,b.Y=0,b.G=b.aa=2,b.Pa=0,b.D=0);b=c}}else b=-2;if(0!==b)throw Error($g[b]);a.header&&(b=this.C)&&b.state&&2===b.state.wrap&&(b.state.v=a.header);if(a.pb){var l;"string"===typeof a.pb?l=Tg(a.pb):"[object ArrayBuffer]"===qi.call(a.pb)?l=new Uint8Array(a.pb):l=a.pb;a=this.C;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,
2===b||1===b&&42!==l.status||l.m)b=-2;else{1===b&&(a.A=Ug(a.A,f,g,0));l.wrap=0;g>=l.T&&(0===b&&(ci(l.head),l.l=0,l.Z=0,l.Y=0),c=new N.Ta(l.T),N.Ua(c,f,g-l.T,l.T,0),f=c,g=l.T);c=a.U;d=a.Ra;e=a.input;a.U=g;a.Ra=0;a.input=f;for(gi(l);3<=l.m;){f=l.l;g=l.m-2;do l.D=(l.D<<l.va^l.window[f+3-1])&l.ta,l.la[f&l.Ga]=l.head[l.D],l.head[l.D]=f,f++;while(--g);l.l=f;l.m=2;gi(l)}l.l+=l.m;l.Z=l.l;l.Y=l.m;l.m=0;l.G=l.aa=2;l.Pa=0;a.Ra=d;a.input=e;a.U=c;l.wrap=b;b=0}else b=-2;if(0!==b)throw Error($g[b]);this.je=!0}}
ri.prototype.push=function(a,b){var c=this.C,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:!0===b?4:0;"string"===typeof a?c.input=Tg(a):"[object ArrayBuffer]"===qi.call(a)?c.input=new Uint8Array(a):c.input=a;c.Ra=0;c.U=c.input.length;do{0===c.F&&(c.output=new N.Ta(d),c.cb=0,c.F=d);a=oi(c,e);if(1!==a&&0!==a)return si(this,a),this.ended=!0,!1;if(0===c.F||0===c.U&&(4===e||2===e))if("string"===this.options.Fa){var f=N.ec(c.output,c.cb);b=f;f=f.length;if(65537>f&&(b.subarray&&Sg||!b.subarray))b=
String.fromCharCode.apply(null,N.ec(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=N.ec(c.output,c.cb),this.chunks.push(b)}while((0<c.U||0===c.F)&&1!==a);if(4===e)return(c=this.C)&&c.state?(d=c.state.status,42!==d&&69!==d&&73!==d&&91!==d&&103!==d&&113!==d&&666!==d?a=bi(c,-2):(c.state=null,a=113===d?bi(c,-3):0)):a=-2,si(this,a),this.ended=!0,0===a;2===e&&(si(this,0),c.F=0);return!0};
function si(a,b){0===b&&(a.result="string"===a.options.Fa?a.chunks.join(""):N.qc(a.chunks));a.chunks=[];a.err=b;a.msg=a.C.msg}
;function ti(a){this.name=a}
;var ui=new ti("rawColdConfigGroup");var vi=new ti("rawHotConfigGroup");function wi(a){this.s=H(a)}
w(wi,K);wi.prototype.g=function(a){J(this,5,a)};function xi(a){this.s=H(a)}
w(xi,K);function yi(a){this.s=H(a)}
w(yi,K);yi.ma=[2];function zi(a){this.s=H(a)}
w(zi,K);zi.prototype.getPlayerType=function(){var a=0;a=void 0===a?0:a;var b=ud(this,36);return null!=b?b:a};
zi.prototype.setHomeGroupInfo=function(a){return I(this,yi,81,a)};
zi.ma=[9,66,32,86,100,101];function Ai(a){this.s=H(a)}
w(Ai,K);Ai.prototype.getKey=function(){return Fd(this,1)};
Ai.prototype.ja=function(){return Fd(this,Bd(this,Bi,2))};
var Bi=[2,3,4,5,6];function Ci(a){this.s=H(a)}
w(Ci,K);Ci.ma=[15,26,28];function Di(a){this.s=H(a)}
w(Di,K);Di.ma=[5];function Ei(a){this.s=H(a)}
w(Ei,K);function Fi(a){this.s=H(a)}
w(Fi,K);Fi.prototype.setSafetyMode=function(a){return Kd(this,5,a)};
Fi.ma=[12];function Gi(a){this.s=H(a)}
w(Gi,K);Gi.ma=[12];var Hi={ie:"WEB_DISPLAY_MODE_UNKNOWN",ee:"WEB_DISPLAY_MODE_BROWSER",ge:"WEB_DISPLAY_MODE_MINIMAL_UI",he:"WEB_DISPLAY_MODE_STANDALONE",fe:"WEB_DISPLAY_MODE_FULLSCREEN"};function Ii(a){this.s=H(a)}
w(Ii,K);Ii.prototype.getKey=function(){return Fd(this,1)};
Ii.prototype.ja=function(){return Fd(this,2)};function Ji(a){this.s=H(a)}
w(Ji,K);Ji.ma=[4,5];function Ki(a){this.s=H(a)}
w(Ki,K);function Li(a){this.s=H(a)}
w(Li,K);var Mi=[2,3,4,5];function Ni(a){this.s=H(a)}
w(Ni,K);function Oi(a){this.s=H(a)}
w(Oi,K);function Pi(a){this.s=H(a)}
w(Pi,K);function Qi(a){this.s=H(a)}
w(Qi,K);Qi.ma=[10,17];function Ri(a){this.s=H(a)}
w(Ri,K);function Si(a){this.s=H(a)}
w(Si,K);function Ti(a){this.s=H(a)}
w(Ti,K);function Ui(a){this.s=H(a,486)}
w(Ui,K);
var Vi=[2,3,5,6,7,11,13,20,21,22,23,24,28,32,37,45,59,72,73,74,76,78,79,80,85,91,97,100,102,105,111,117,119,126,127,136,146,148,151,156,157,158,159,163,164,168,176,177,178,179,184,188,189,190,191,193,194,195,196,197,198,199,200,201,202,203,204,205,206,208,209,215,219,222,225,226,227,229,232,233,234,240,241,244,247,248,249,251,254,255,256,257,258,259,260,261,266,270,272,278,288,291,293,300,304,308,309,310,311,313,314,319,320,321,323,324,327,328,330,331,332,334,337,338,340,344,348,350,351,352,353,354,
355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,383,388,389,399,402,403,410,411,412,413,414,415,416,417,418,423,424,425,426,427,429,430,431,439,441,444,448,458,469,471,473,474,480,481,482,484,485];function Wi(a){this.s=H(a)}
w(Wi,K);function Xi(a){this.s=H(a)}
w(Xi,K);Xi.prototype.getPlaylistId=function(){return Gd(this,2)};
var Hd=[1,2];function Yi(a){this.s=H(a)}
w(Yi,K);Yi.ma=[3];var Zi=B.window,$i,aj,bj=(null==Zi?void 0:null==($i=Zi.yt)?void 0:$i.config_)||(null==Zi?void 0:null==(aj=Zi.ytcfg)?void 0:aj.data_)||{};D("yt.config_",bj);function cj(){var a=arguments;1<a.length?bj[a[0]]=a[1]:1===a.length&&Object.assign(bj,a[0])}
function S(a,b){return a in bj?bj[a]:b}
function dj(){return S("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS")}
function ej(){var a=bj.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;var fj=[];function gj(a){fj.forEach(function(b){return b(a)})}
function hj(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){ij(b)}}:a}
function ij(a){var b=C("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=S("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),cj("ERRORS",b));gj(a)}
function jj(a,b,c,d,e){var f=C("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=S("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),cj("ERRORS",f))}
;function T(a){a=kj(a);return"string"===typeof a&&"false"===a?!1:!!a}
function V(a,b){a=kj(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function kj(a){var b=S("EXPERIMENTS_FORCED_FLAGS",{})||{};return void 0!==b[a]?b[a]:S("EXPERIMENT_FLAGS",{})[a]}
function lj(){for(var a=[],b=S("EXPERIMENTS_FORCED_FLAGS",{}),c=u(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=S("EXPERIMENT_FLAGS",{});var e=u(Object.keys(c));for(d=e.next();!d.done;d=e.next())d=d.value,d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var mj=0;D("ytDomDomGetNextId",C("ytDomDomGetNextId")||function(){return++mj});var nj={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function oj(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.clientY=this.clientX=0;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in nj||(this[b]=a[b]);var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==
this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey}}catch(e){}}
oj.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
oj.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
oj.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var kb=B.ytEventsEventsListeners||{};D("ytEventsEventsListeners",kb);var pj=B.ytEventsEventsCounter||{count:0};D("ytEventsEventsCounter",pj);
function qj(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return jb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Ma(e[4])&&Ma(d)&&lb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function rj(a){a&&("string"==typeof a&&(a=[a]),bb(a,function(b){if(b in kb){var c=kb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?sj()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete kb[b]}}))}
var sj=$a(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function tj(a,b,c){var d=void 0===d?{}:d;if(a&&(a.addEventListener||a.attachEvent)){var e=qj(a,b,c,d);if(!e){e=++pj.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new oj(h);if(!Qd(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new oj(h);
h.currentTarget=a;return c.call(a,h)};
g=hj(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),sj()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);kb[e]=[a,b,c,g,d]}}}
;function uj(a,b){"function"===typeof a&&(a=hj(a));return window.setTimeout(a,b)}
function vj(a){"function"===typeof a&&(a=hj(a));return window.setInterval(a,250)}
;var wj=/^[\w.]*$/,xj={q:!0,search_query:!0};function yj(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=zj(f[0]||""),h=zj(f[1]||"");g in c?Array.isArray(c[g])?hb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(n){var k=n,l=f[0],m=String(yj);k.args=[{key:l,value:f[1],query:a,method:Aj==m?"unchanged":m}];xj.hasOwnProperty(l)||jj(k)}}return c}
var Aj=String(yj);function Bj(a){var b=[];ib(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];bb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Cj(a){"?"==a.charAt(0)&&(a=a.substr(1));return yj(a,"&")}
function Dj(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Cj(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);b=a;a=$b(e);a?(c=b.indexOf("#"),0>c&&(c=b.length),f=b.indexOf("?"),0>f||f>c?(f=c,e=""):e=b.substring(f+1,c),b=[b.slice(0,f),e,b.slice(c)],c=b[1],b[1]=a?c?c+"&"+a:a:c,a=b[0]+(b[1]?"?"+b[1]:"")+b[2]):a=b;return a+d}
function Ej(a){if(!b)var b=window.location.href;var c=a.match(Vb)[1]||null,d=Xb(a);c&&d?(a=a.match(Vb),b=b.match(Vb),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?Xb(b)==d&&(Number(b.match(Vb)[4]||null)||null)==(Number(a.match(Vb)[4]||null)||null):!0;return a}
function zj(a){return a&&a.match(wj)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Fj(a){var b=Gj;a=void 0===a?C("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=je;e.flash="0";a:{try{var f=b.g.top.location.href}catch(ca){f=2;break a}f=f?f===b.h.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?Nd:g;try{var h=g.history.length}catch(ca){h=0}e.u_his=h;var k;e.u_h=null==(k=Nd.screen)?void 0:k.height;var l;e.u_w=null==(l=Nd.screen)?void 0:l.width;var m;e.u_ah=null==(m=Nd.screen)?void 0:m.availHeight;var n;e.u_aw=
null==(n=Nd.screen)?void 0:n.availWidth;var r;e.u_cd=null==(r=Nd.screen)?void 0:r.colorDepth}catch(ca){}h=b.g;try{var p=h.screenX;var x=h.screenY}catch(ca){}try{var y=h.outerWidth;var F=h.outerHeight}catch(ca){}try{var O=h.innerWidth;var U=h.innerHeight}catch(ca){}try{var Q=h.screenLeft;var Fa=h.screenTop}catch(ca){}try{O=h.innerWidth,U=h.innerHeight}catch(ca){}try{var Uc=h.screen.availWidth;var Ra=h.screen.availTop}catch(ca){}p=[Q,Fa,p,x,Uc,Ra,y,F,O,U];x=b.g.top;try{var Ga=(x||window).document,da=
"CSS1Compat"==Ga.compatMode?Ga.documentElement:Ga.body;var ma=(new Od(da.clientWidth,da.clientHeight)).round()}catch(ca){ma=new Od(-12245933,-12245933)}Ga=ma;ma={};var na=void 0===na?B:na;da=new jf;"SVGElement"in na&&"createElementNS"in na.document&&da.set(0);x=he();x["allow-top-navigation-by-user-activation"]&&da.set(1);x["allow-popups-to-escape-sandbox"]&&da.set(2);na.crypto&&na.crypto.subtle&&da.set(3);"TextDecoder"in na&&"TextEncoder"in na&&da.set(4);na=kf(da);ma.bc=na;ma.bih=Ga.height;ma.biw=
Ga.width;ma.brdim=p.join();b=b.h;b=(ma.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,ma.wgl=!!Nd.WebGLRenderingContext,ma);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Gj=new function(){var a=window.document;this.g=window;this.h=a};
D("yt.ads_.signals_.getAdSignalsString",function(a){return Bj(Fj(a))});Ua();var Hj="XMLHttpRequest"in B?function(){return new XMLHttpRequest}:null;
function Ij(){if(!Hj)return null;var a=Hj();return"open"in a?a:null}
;var Jj="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");v(Jj);var Kj={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},Lj="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(v(Jj)),Mj=!1;
function Nj(a,b){b=void 0===b?{}:b;var c=Ej(a),d=T("web_ajax_ignore_global_headers_if_set"),e;for(e in Kj){var f=S(Kj[e]),g="X-Goog-AuthUser"===e||"X-Goog-PageId"===e;"X-Goog-Visitor-Id"!==e||f||(f=S("VISITOR_DATA"));!f||!c&&Xb(a)||d&&void 0!==b[e]||"TVHTML5_UNPLUGGED"===S("INNERTUBE_CLIENT_NAME")&&g||(b[e]=f)}c&&S("SESSION_INDEX")&&"TVHTML5_UNPLUGGED"!==S("INNERTUBE_CLIENT_NAME")&&(b["X-Yt-Auth-Test"]="test");"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||
!Xb(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!Xb(a)){try{var h=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(k){}h&&(b["X-YouTube-Time-Zone"]=h)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&Xb(a)||(b["X-YouTube-Ad-Signals"]=Bj(Fj()));return b}
function Oj(a){var b=window.location.search,c=Xb(a);T("debug_handle_relative_url_for_query_forward_killswitch")||!c&&Ej(a)&&(c=document.location.hostname);var d=Wb(a.match(Vb)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Cj(b),f={};bb(Lj,function(g){e[g]&&(f[g]=e[g])});
return Dj(a,f||{},!1)}
function Pj(a,b){var c=b.format||"JSON";a=Qj(a,b);var d=Rj(a,b),e=!1,f=Sj(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);a:switch(k&&"status"in k?k.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:var l=!0;break a;default:l=!1}var m=null,n=400<=k.status&&500>k.status,r=500<=k.status&&600>k.status;if(l||n||r)m=Tj(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(m&&m.return_code,10);break a;case "RAW":l=!0;break a}l=
!!m}m=m||{};n=b.context||B;l?b.onSuccess&&b.onSuccess.call(n,k,m):b.onError&&b.onError.call(n,k,m);b.onFinish&&b.onFinish.call(n,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=uj(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||B,f))},d)}return f}
function Qj(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=S("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=Dj(a,b||{},!0);return a}
function Rj(a,b){var c=S("XSRF_FIELD_NAME"),d=S("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams;var g=S("XSRF_FIELD_NAME");var h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||Xb(a)&&!b.withCredentials&&Xb(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(T("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=Cj(e),ob(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):$b(e));if(!(a=e)&&(a=f)){a:{for(var k in f){f=!1;break a}f=!0}a=!f}!Mj&&a&&"POST"!=b.method&&(Mj=!0,ij(Error("AJAX request with postData should use POST")));return e}
function Tj(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,jj(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Uj(a):null)e={},bb(a.getElementsByTagName("*"),function(g){e[g.tagName]=Vj(g)})}d&&Wj(e);
return e}
function Wj(a){if(Ma(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b];if(void 0===pb){var e=null;var f=B.trustedTypes;if(f&&f.createPolicy){try{e=f.createPolicy("goog#html",{createHTML:Wa,createScript:Wa,createScriptURL:Wa})}catch(g){B.console&&B.console.error(g.message)}pb=e}else pb=e}d=(e=pb)?e.createHTML(d):d;a[c]=new Tb(d)}else Wj(a[b])}}
function Uj(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Vj(a){var b="";bb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Xj(a,b){b.method="POST";b.postParams||(b.postParams={});return Pj(a,b)}
function Sj(a,b,c,d,e,f,g,h){function k(){4==(l&&"readyState"in l?l.readyState:0)&&b&&hj(b)(l)}
c=void 0===c?"GET":c;d=void 0===d?"":d;h=void 0===h?!1:h;var l=Ij();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;T("debug_forward_web_query_parameters")&&(a=Oj(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=Nj(a,e))for(var m in e)l.setRequestHeader(m,e[m]),"content-type"==m.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
h&&"setAttributionReporting"in XMLHttpRequest.prototype&&l.setAttributionReporting({eventSourceEligible:!0,triggerEligible:!1});l.send(d);return l}
;var Yj=[{Yb:function(a){return"Cannot read property '"+a.key+"'"},
Kb:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Yb:function(a){return"Cannot call '"+a.key+"'"},
Kb:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Yb:function(a){return a.key+" is not defined"},
Kb:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var ak={Da:[],Aa:[{nb:Zj,weight:500}]};function Zj(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function bk(){this.Aa=[];this.Da=[]}
var ck;function dk(){if(!ck){var a=ck=new bk;a.Da.length=0;a.Aa.length=0;ak.Da&&a.Da.push.apply(a.Da,ak.Da);ak.Aa&&a.Aa.push.apply(a.Aa,ak.Aa)}return ck}
;var ek=new L;function fk(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=gk(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=gk(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=gk(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function gk(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function hk(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=ik(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=fk(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?ik(e+".ve",f,g,h):0;d+=g;d+=ik(e,a[e],b,c);if(500<d)break}}else c[b]=jk(a),d+=c[b].length;else c[b]=jk(a),d+=c[b].length;return d}
function ik(a,b,c,d){c+="."+a;a=jk(b);d[c]=a;return c.length+a.length}
function jk(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function kk(){}
;function lk(){if(!B.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return B.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":B.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":B.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":B.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function mk(a){switch(a){case "DESKTOP":return 1;case "UNKNOWN_PLATFORM":return 0;case "TV":return 2;case "GAME_CONSOLE":return 3;case "MOBILE":return 4;case "TABLET":return 5}}
;D("ytglobal.prefsUserPrefsPrefs_",C("ytglobal.prefsUserPrefsPrefs_")||{});var nk={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},ok={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_WIRED:30,CONN_INVALID:31},pk={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},qk={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function rk(){var a=B.navigator;return a?a.connection:void 0}
;function sk(a){var b=Ea.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(v(b))}
w(sk,Error);function tk(){try{return uk(),!0}catch(a){return!1}}
function uk(){if(void 0!==S("DATASYNC_ID"))return S("DATASYNC_ID");throw new sk("Datasync ID not set","unknown");}
;function vk(){}
function wk(a,b){return hf.Ia(a,0,b)}
vk.prototype.qa=function(a,b){return this.Ia(a,1,b)};
vk.prototype.kb=function(a){var b=C("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var xk=V("web_emulated_idle_callback_delay",300),yk=1E3/60-3,zk=[8,5,4,3,2,1,0];
function Ak(a){a=void 0===a?{}:a;ye.call(this);this.h=[];this.i={};this.ib=this.g=0;this.hb=this.o=!1;this.M=[];this.S=this.jb=!1;for(var b=u(zk),c=b.next();!c.done;c=b.next())this.h[c.value]=[];this.j=0;this.Uc=a.timeout||1;this.H=yk;this.u=0;this.xb=this.yd.bind(this);this.Tc=this.Dd.bind(this);this.Qc=this.Vc.bind(this);this.Rc=this.kd.bind(this);this.Sc=this.zd.bind(this);this.ic=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!T("disable_scheduler_requestIdleCallback");(this.za=!1!==
a.useRaf&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.xb)}
w(Ak,ye);q=Ak.prototype;q.kb=function(a){var b=Ua();Bk(a);a=Ua()-b;this.o||(this.H-=a)};
q.Ia=function(a,b,c){++this.ib;if(10===b)return this.kb(a),this.ib;var d=this.ib;this.i[d]=a;this.o&&!c?this.M.push({id:d,priority:b}):(this.h[b].push(d),this.hb||this.o||(0!==this.g&&Ck(this)!==this.u&&Dk(this),this.start()));return d};
q.ba=function(a){delete this.i[a]};
function Ek(a){a.M.length=0;for(var b=5;0<=b;b--)a.h[b].length=0;a.h[8].length=0;a.i={};Dk(a)}
function Ck(a){if(a.h[8].length){if(a.S)return 4;if(!document.hidden&&a.za)return 3}for(var b=5;b>=a.j;b--)if(0<a.h[b].length)return 0<b?!document.hidden&&a.za?3:2:1;return 0}
function Fk(a){var b=C("yt.logging.errors.log");b&&b(a)}
function Bk(a){try{a()}catch(b){Fk(b)}}
function Gk(a){for(var b=u(zk),c=b.next();!c.done;c=b.next())if(a.h[c.value].length)return!0;return!1}
q.kd=function(a){var b=void 0;a&&(b=a.timeRemaining());this.jb=!0;Hk(this,b);this.jb=!1};
q.Dd=function(){Hk(this)};
q.Vc=function(){Ik(this)};
q.zd=function(a){this.S=!0;var b=Ck(this);4===b&&b!==this.u&&(Dk(this),this.start());Hk(this,void 0,a);this.S=!1};
q.yd=function(){document.hidden||Ik(this);this.g&&(Dk(this),this.start())};
function Ik(a){Dk(a);a.o=!0;for(var b=Ua(),c=a.h[8];c.length;){var d=c.shift(),e=a.i[d];delete a.i[d];e&&Bk(e)}Jk(a);a.o=!1;Gk(a)&&a.start();b=Ua()-b;a.H-=b}
function Jk(a){for(var b=0,c=a.M.length;b<c;b++){var d=a.M[b];a.h[d.priority].push(d.id)}a.M.length=0}
function Hk(a,b,c){a.S&&4===a.u&&a.g||Dk(a);a.o=!0;b=Ua()+(b||a.H);for(var d=a.h[5];d.length;){var e=d.shift(),f=a.i[e];delete a.i[e];if(f)try{f(c)}catch(l){Fk(l)}}for(d=a.h[4];d.length;)c=d.shift(),e=a.i[c],delete a.i[c],e&&Bk(e);d=a.jb?0:1;d=a.j>d?a.j:d;if(!(Ua()>=b)){do{a:{c=a;e=d;for(f=3;f>=e;f--)for(var g=c.h[f];g.length;){var h=g.shift(),k=c.i[h];delete c.i[h];if(k){c=k;break a}}c=null}c&&Bk(c)}while(c&&Ua()<b)}a.o=!1;Jk(a);a.H=yk;Gk(a)&&a.start()}
q.start=function(){this.hb=!1;if(0===this.g)switch(this.u=Ck(this),this.u){case 1:var a=this.Rc;this.g=this.ic?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,xk);break;case 2:this.g=window.setTimeout(this.Tc,this.Uc);break;case 3:this.g=window.requestAnimationFrame(this.Sc);break;case 4:this.g=window.setTimeout(this.Qc,0)}};
function Dk(a){if(a.g){switch(a.u){case 1:var b=a.g;a.ic?window.cancelIdleCallback(b):window.clearTimeout(b);break;case 2:case 4:window.clearTimeout(a.g);break;case 3:window.cancelAnimationFrame(a.g)}a.g=0}}
q.sa=function(){Ek(this);Dk(this);this.za&&document.removeEventListener("visibilitychange",this.xb);ye.prototype.sa.call(this)};var Kk=C("yt.scheduler.instance.timerIdMap_")||{},Lk=V("kevlar_tuner_scheduler_soft_state_timer_ms",800),Mk=0,Nk=0;function Ok(){var a=C("ytglobal.schedulerInstanceInstance_");if(!a||a.Ka)a=new Ak(S("scheduler")||{}),D("ytglobal.schedulerInstanceInstance_",a);return a}
function Pk(){Qk();var a=C("ytglobal.schedulerInstanceInstance_");a&&(xe(a),D("ytglobal.schedulerInstanceInstance_",null))}
function Qk(){Ek(Ok());for(var a in Kk)Kk.hasOwnProperty(a)&&delete Kk[Number(a)]}
function Rk(a,b,c){if(!c)return c=void 0===c,-Ok().Ia(a,b,c);var d=window.setTimeout(function(){var e=Ok().Ia(a,b);Kk[d]=e},c);
return d}
function Sk(a){Ok().kb(a)}
function Tk(a){var b=Ok();if(0>a)b.ba(-a);else{var c=Kk[a];c?(b.ba(c),delete Kk[a]):window.clearTimeout(a)}}
function Uk(){Vk()}
function Vk(){window.clearTimeout(Mk);Ok().start()}
function Wk(){var a=Ok();Dk(a);a.hb=!0;window.clearTimeout(Mk);Mk=window.setTimeout(Uk,Lk)}
function Xk(){window.clearTimeout(Nk);Nk=window.setTimeout(function(){Yk(0)},Lk)}
function Yk(a){Xk();var b=Ok();b.j=a;b.start()}
function Zk(a){Xk();var b=Ok();b.j>a&&(b.j=a,b.start())}
function $k(){window.clearTimeout(Nk);var a=Ok();a.j=0;a.start()}
;function al(){vk.apply(this,arguments)}
w(al,vk);function bl(){al.g||(al.g=new al);return al.g}
al.prototype.Ia=function(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=C("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):uj(a,c||0)};
al.prototype.ba=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=C("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
al.prototype.start=function(){var a=C("yt.scheduler.instance.start");a&&a()};
var hf=bl();
T("web_scheduler_auto_init")&&!C("yt.scheduler.initialized")&&(D("yt.scheduler.instance.dispose",Pk),D("yt.scheduler.instance.addJob",Rk),D("yt.scheduler.instance.addImmediateJob",Sk),D("yt.scheduler.instance.cancelJob",Tk),D("yt.scheduler.instance.cancelAllJobs",Qk),D("yt.scheduler.instance.start",Vk),D("yt.scheduler.instance.pause",Wk),D("yt.scheduler.instance.setPriorityThreshold",Yk),D("yt.scheduler.instance.enablePriorityThreshold",Zk),D("yt.scheduler.instance.clearPriorityThreshold",$k),D("yt.scheduler.initialized",
!0));function cl(a){var b=new Ig;if(b.g)try{b.g.setItem("__sak","1");b.g.removeItem("__sak");var c=!0}catch(d){c=!1}else c=!1;(b=c?a?new Og(b,a):b:null)||(a=new Jg(a||"UserDataSharedStore"),b=a.g?a:null);this.g=(a=b)?new Eg(a):null;this.h=document.domain||window.location.hostname}
cl.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.g)try{this.g.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(fg(b))}catch(f){return}else e=escape(b);b=this.h;re.set(""+a,e,{Wb:c,path:"/",domain:void 0===b?"youtube.com":b,secure:!1})};
cl.prototype.get=function(a,b){var c=void 0,d=!this.g;if(!d)try{c=this.g.get(a)}catch(e){d=!0}if(d&&(c=re.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
cl.prototype.remove=function(a){this.g&&this.g.remove(a);var b=this.h;re.remove(""+a,"/",void 0===b?"youtube.com":b)};var dl=function(){var a;return function(){a||(a=new cl("ytidb"));return a}}();
function el(){var a;return null==(a=dl())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var fl=[],gl=!1;function hl(a){gl||(fl.push({type:"ERROR",payload:a}),10<fl.length&&fl.shift())}
function il(a,b){gl||(fl.push({type:"EVENT",eventType:a,payload:b}),10<fl.length&&fl.shift())}
;function jl(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function kl(a){return a.substr(0,a.indexOf(":"))||a}
;var ll=xc||yc;var ml={},nl=(ml.AUTH_INVALID="No user identifier specified.",ml.EXPLICIT_ABORT="Transaction was explicitly aborted.",ml.IDB_NOT_SUPPORTED="IndexedDB is not supported.",ml.MISSING_INDEX="Index not created.",ml.MISSING_OBJECT_STORES="Object stores not created.",ml.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",ml.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",ml.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
ml.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",ml.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",ml.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",ml.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",ml),ol={},pl=(ol.AUTH_INVALID="ERROR",ol.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",ol.EXPLICIT_ABORT="IGNORED",ol.IDB_NOT_SUPPORTED="ERROR",ol.MISSING_INDEX=
"WARNING",ol.MISSING_OBJECT_STORES="ERROR",ol.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",ol.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",ol.QUOTA_EXCEEDED="WARNING",ol.QUOTA_MAYBE_EXCEEDED="WARNING",ol.UNKNOWN_ABORT="WARNING",ol.INCOMPATIBLE_DB_VERSION="WARNING",ol),ql={},rl=(ql.AUTH_INVALID=!1,ql.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,ql.EXPLICIT_ABORT=!1,ql.IDB_NOT_SUPPORTED=!1,ql.MISSING_INDEX=!1,ql.MISSING_OBJECT_STORES=!1,ql.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,ql.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,ql.QUOTA_EXCEEDED=!1,ql.QUOTA_MAYBE_EXCEEDED=!0,ql.UNKNOWN_ABORT=!0,ql.INCOMPATIBLE_DB_VERSION=!1,ql);function X(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?nl[a]:c;d=void 0===d?pl[a]:d;e=void 0===e?rl[a]:e;sk.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.g=e;Object.setPrototypeOf(this,X.prototype)}
w(X,sk);function sl(a,b){X.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},nl.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,sl.prototype)}
w(sl,X);function tl(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,tl.prototype)}
w(tl,Error);var ul=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function vl(a,b,c,d){b=kl(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof X)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new X("QUOTA_EXCEEDED",a);if(zc&&"UnknownError"===e.name)return new X("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof tl)return new X("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&ul.some(function(f){return e.message.includes(f)}))return new X("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new X("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",re:e.name})];e.level="WARNING";return e}
function wl(a,b,c){var d=el();return new X("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function xl(a){if(!a)throw Error();throw a;}
function yl(a){return a}
function zl(a){this.g=a}
function Al(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=u(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=u(d.g);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.g=[];this.h=[];a=a.g;try{a(c,b)}catch(e){b(e)}}
Al.resolve=function(a){return new Al(new zl(function(b,c){a instanceof Al?a.then(b,c):b(a)}))};
Al.reject=function(a){return new Al(new zl(function(b,c){c(a)}))};
Al.prototype.then=function(a,b){var c=this,d=null!=a?a:yl,e=null!=b?b:xl;return new Al(new zl(function(f,g){"PENDING"===c.state.status?(c.g.push(function(){Bl(c,c,d,f,g)}),c.h.push(function(){Cl(c,c,e,f,g)})):"FULFILLED"===c.state.status?Bl(c,c,d,f,g):"REJECTED"===c.state.status&&Cl(c,c,e,f,g)}))};
function Dl(a,b){a.then(void 0,b)}
function Bl(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Al?El(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Cl(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Al?El(a,b,f,d,e):d(f)}catch(g){e(g)}}
function El(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Al?El(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Fl(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Gl(a){return new Promise(function(b,c){Fl(a,b,c)})}
function Hl(a){return new Al(new zl(function(b,c){Fl(a,b,c)}))}
;function Il(a,b){return new Al(new zl(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var Jl=window,Y=Jl.ytcsi&&Jl.ytcsi.now?Jl.ytcsi.now:Jl.performance&&Jl.performance.timing&&Jl.performance.now&&Jl.performance.timing.navigationStart?function(){return Jl.performance.timing.navigationStart+Jl.performance.now()}:function(){return(new Date).getTime()};function Kl(a,b){this.g=a;this.options=b;this.transactionCount=0;this.i=Math.round(Y());this.h=!1}
q=Kl.prototype;q.add=function(a,b,c){return Ll(this,[a],{mode:"readwrite",W:!0},function(d){return d.objectStore(a).add(b,c)})};
q.clear=function(a){return Ll(this,[a],{mode:"readwrite",W:!0},function(b){return b.objectStore(a).clear()})};
q.close=function(){this.g.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
function Ml(a,b,c){a=a.g.createObjectStore(b,c);return new Nl(a)}
q.delete=function(a,b){return Ll(this,[a],{mode:"readwrite",W:!0},function(c){return c.objectStore(a).delete(b)})};
q.get=function(a,b){return Ll(this,[a],{mode:"readonly",W:!0},function(c){return c.objectStore(a).get(b)})};
function Ol(a,b,c){return Ll(a,[b],{mode:"readwrite",W:!0},function(d){d=d.objectStore(b);return Hl(d.g.put(c,void 0))})}
q.objectStoreNames=function(){return Array.from(this.g.objectStoreNames)};
function Ll(a,b,c,d){var e,f,g,h,k,l,m,n,r,p,x,y;return A(function(F){switch(F.g){case 1:var O={mode:"readonly",W:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?O.mode=c:Object.assign(O,c);e=O;a.transactionCount++;f=e.W?3:1;g=0;case 2:if(h){F.B(4);break}g++;k=Math.round(Y());va(F,5);l=a.g.transaction(b,e.mode);O=new Pl(l);O=Ql(O,d);return z(F,O,7);case 7:return m=F.h,n=Math.round(Y()),Rl(a,k,n,g,void 0,b.join(),e),F.return(m);case 5:r=wa(F);p=Math.round(Y());x=vl(r,a.g.name,b.join(),a.g.version);
if((y=x instanceof X&&!x.g)||g>=f)Rl(a,k,p,g,x,b.join(),e),h=x;F.B(2);break;case 4:return F.return(Promise.reject(h))}})}
function Rl(a,b,c,d,e,f,g){b=c-b;e?(e instanceof X&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&il("QUOTA_EXCEEDED",{dbName:kl(a.g.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof X&&"UNKNOWN_ABORT"===e.type&&(c-=a.i,0>c&&c>=Math.pow(2,31)&&(c=0),il("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.h=!0),Sl(a,!1,d,f,b,g.tag),hl(e)):Sl(a,!0,d,f,b,g.tag)}
function Sl(a,b,c,d,e,f){il("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.h,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
q.getName=function(){return this.g.name};
function Nl(a){this.g=a}
q=Nl.prototype;q.add=function(a,b){return Hl(this.g.add(a,b))};
q.autoIncrement=function(){return this.g.autoIncrement};
q.clear=function(){return Hl(this.g.clear()).then(function(){})};
function Tl(a,b,c){a.g.createIndex(b,c,{unique:!1})}
function Ul(a,b){return Vl(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
q.delete=function(a){return a instanceof IDBKeyRange?Ul(this,a):Hl(this.g.delete(a))};
q.get=function(a){return Hl(this.g.get(a))};
q.index=function(a){try{return new Wl(this.g.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new tl(a,this.g.name);throw b;}};
q.getName=function(){return this.g.name};
q.keyPath=function(){return this.g.keyPath};
function Vl(a,b,c){a=a.g.openCursor(b.query,b.direction);return Xl(a).then(function(d){return Il(d,c)})}
function Pl(a){var b=this;this.g=a;this.i=new Map;this.h=!1;this.done=new Promise(function(c,d){b.g.addEventListener("complete",function(){c()});
b.g.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.g.error)});
b.g.addEventListener("abort",function(){var e=b.g.error;if(e)d(e);else if(!b.h){e=X;for(var f=b.g.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.g.db.name,mode:b.g.mode});d(e)}})})}
function Ql(a,b){var c=new Promise(function(d,e){try{Dl(b(a).then(function(f){d(f)}),e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return u(d).next().value})}
Pl.prototype.abort=function(){this.g.abort();this.h=!0;throw new X("EXPLICIT_ABORT");};
Pl.prototype.objectStore=function(a){a=this.g.objectStore(a);var b=this.i.get(a);b||(b=new Nl(a),this.i.set(a,b));return b};
function Wl(a){this.g=a}
q=Wl.prototype;q.delete=function(a){return Yl(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
q.get=function(a){return Hl(this.g.get(a))};
q.getKey=function(a){return Hl(this.g.getKey(a))};
q.keyPath=function(){return this.g.keyPath};
q.unique=function(){return this.g.unique};
function Yl(a,b,c){a=a.g.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Xl(a).then(function(d){return Il(d,c)})}
function Zl(a,b){this.request=a;this.cursor=b}
function Xl(a){return Hl(a).then(function(b){return b?new Zl(a,b):null})}
q=Zl.prototype;q.advance=function(a){this.cursor.advance(a);return Xl(this.request)};
q.continue=function(a){this.cursor.continue(a);return Xl(this.request)};
q.delete=function(){return Hl(this.cursor.delete()).then(function(){})};
q.getKey=function(){return this.cursor.key};
q.ja=function(){return this.cursor.value};
q.update=function(a){return Hl(this.cursor.update(a))};function $l(a,b,c){return new Promise(function(d,e){function f(){r||(r=new Kl(g.result,{closed:n}));return r}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Xc,k=c.Yc,l=c.Cd,m=c.upgrade,n=c.closed,r;g.addEventListener("upgradeneeded",function(p){try{if(null===p.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");p.dataLoss&&"none"!==p.dataLoss&&il("IDB_DATA_CORRUPTED",{reason:p.dataLossMessage||"unknown reason",dbName:kl(a)});var x=f(),y=new Pl(g.transaction);m&&
m(x,function(F){return p.oldVersion<F&&p.newVersion>=F},y);
y.done.catch(function(F){e(F)})}catch(F){e(F)}});
g.addEventListener("success",function(){var p=g.result;k&&p.addEventListener("versionchange",function(){k(f())});
p.addEventListener("close",function(){il("IDB_UNEXPECTEDLY_CLOSED",{dbName:kl(a),dbVersion:p.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function am(a,b,c){c=void 0===c?{}:c;return $l(a,b,c)}
function bm(a,b){b=void 0===b?{}:b;var c,d,e,f;return A(function(g){if(1==g.g)return va(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Xc)&&c.addEventListener("blocked",function(){e()}),z(g,Gl(c),4);
if(2!=g.g)g.g=0,g.o=0;else throw f=wa(g),vl(f,a,"",-1);})}
;function cm(a,b){this.name=a;this.options=b;this.i=!0;this.o=this.j=0}
cm.prototype.h=function(a,b,c){c=void 0===c?{}:c;return am(a,b,c)};
cm.prototype.delete=function(a){a=void 0===a?{}:a;return bm(this.name,a)};
function dm(a,b){return new X("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function em(a,b){if(!b)throw wl("openWithToken",kl(a.name));return fm(a)}
function fm(a){function b(){var f,g,h,k,l,m,n,r,p,x;return A(function(y){switch(y.g){case 1:return g=null!=(f=Error().stack)?f:"",va(y,2),z(y,a.h(a.name,a.options.version,d),4);case 4:h=y.h;for(var F=a.options,O=[],U=u(Object.keys(F.eb)),Q=U.next();!Q.done;Q=U.next()){Q=Q.value;var Fa=F.eb[Q],Uc=void 0===Fa.Ad?Number.MAX_VALUE:Fa.Ad;!(h.g.version>=Fa.lb)||h.g.version>=Uc||h.g.objectStoreNames.contains(Q)||O.push(Q)}k=O;if(0===k.length){y.B(5);break}l=Object.keys(a.options.eb);m=h.objectStoreNames();
if(a.o<V("ytidb_reopen_db_retries",0))return a.o++,h.close(),hl(new X("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:l,foundObjectStores:m})),y.return(b());if(!(a.j<V("ytidb_remake_db_retries",1))){y.B(6);break}a.j++;return z(y,a.delete(),7);case 7:return hl(new X("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:l,foundObjectStores:m})),y.return(b());case 6:throw new sl(m,l);case 5:return y.return(h);case 2:n=wa(y);if(n instanceof DOMException?
"VersionError"!==n.name:"DOMError"in self&&n instanceof DOMError?"VersionError"!==n.name:!(n instanceof Object&&"message"in n)||"An attempt was made to open a database using a lower version than the existing version."!==n.message){y.B(8);break}return z(y,a.h(a.name,void 0,Object.assign({},d,{upgrade:void 0})),9);case 9:r=y.h;p=r.g.version;if(void 0!==a.options.version&&p>a.options.version+1)throw r.close(),a.i=!1,dm(a,p);return y.return(r);case 8:throw c(),n instanceof Error&&!T("ytidb_async_stack_killswitch")&&
(n.stack=n.stack+"\n"+g.substring(g.indexOf("\n")+1)),vl(n,a.name,"",null!=(x=a.options.version)?x:-1);}})}
function c(){a.g===e&&(a.g=void 0)}
if(!a.i)throw dm(a);if(a.g)return a.g;var d={Yc:function(f){f.close()},
closed:c,Cd:c,upgrade:a.options.upgrade};var e=b();a.g=e;return a.g}
;var gm=new cm("YtIdbMeta",{eb:{databases:{lb:1}},upgrade:function(a,b){b(1)&&Ml(a,"databases",{keyPath:"actualName"})}});
function hm(a,b){var c;return A(function(d){if(1==d.g)return z(d,em(gm,b),2);c=d.h;return d.return(Ll(c,["databases"],{W:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Hl(f.g.put(a,void 0)).then(function(){})})}))})}
function im(a,b){var c;return A(function(d){if(1==d.g)return a?z(d,em(gm,b),2):d.return();c=d.h;return d.return(c.delete("databases",a))})}
function jm(a,b){var c,d;return A(function(e){return 1==e.g?(c=[],z(e,em(gm,b),2)):3!=e.g?(d=e.h,z(e,Ll(d,["databases"],{W:!0,mode:"readonly"},function(f){c.length=0;return Vl(f.objectStore("databases"),{},function(g){a(g.ja())&&c.push(g.ja());return g.continue()})}),3)):e.return(c)})}
function km(a){return jm(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
;var Vm,Wm=new function(){}(new function(){});
function Xm(){var a,b,c,d;return A(function(e){switch(e.g){case 1:a=el();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=ll)f=/WebKit\/([0-9]+)/.exec(Hb()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Hb()),f=!(f&&602<=parseInt(f[1],10)));if(f||hc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
va(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return z(e,hm(d,Wm),4);case 4:return z(e,im("yt-idb-test-do-not-use",Wm),5);case 5:return e.return(!0);case 2:return wa(e),e.return(!1)}})}
function Ym(){if(void 0!==Vm)return Vm;gl=!0;return Vm=Xm().then(function(a){gl=!1;var b;if(null!=(b=dl())&&b.g){var c;b={hasSucceededOnce:(null==(c=el())?void 0:c.hasSucceededOnce)||a};var d;null==(d=dl())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Zm(){return C("ytglobal.idbToken_")||void 0}
function $m(){var a=Zm();return a?Promise.resolve(a):Ym().then(function(b){(b=b?Wm:void 0)&&D("ytglobal.idbToken_",b);return b})}
;new gg;function an(a){if(!tk())throw a=new X("AUTH_INVALID",{dbName:a}),hl(a),a;var b=uk();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function bn(a,b,c,d){var e,f,g,h,k,l;return A(function(m){switch(m.g){case 1:return f=null!=(e=Error().stack)?e:"",z(m,$m(),2);case 2:g=m.h;if(!g)throw h=wl("openDbImpl",a,b),T("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),hl(h),h;jl(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:an(a);va(m,3);return z(m,hm(k,g),5);case 5:return z(m,am(k.actualName,b,d),6);case 6:return m.return(m.h);case 3:return l=wa(m),va(m,7),z(m,im(k.actualName,g),9);case 9:m.g=
8;m.o=0;break;case 7:wa(m);case 8:throw l;}})}
function cn(a,b,c){c=void 0===c?{}:c;return bn(a,b,!1,c)}
function dn(a,b,c){c=void 0===c?{}:c;return bn(a,b,!0,c)}
function en(a,b){b=void 0===b?{}:b;var c,d;return A(function(e){if(1==e.g)return z(e,$m(),2);if(3!=e.g){c=e.h;if(!c)return e.return();jl(a);d=an(a);return z(e,bm(d.actualName,b),3)}return z(e,im(d.actualName,c),0)})}
function fn(a,b,c){a=a.map(function(d){return A(function(e){return 1==e.g?z(e,bm(d.actualName,b),2):z(e,im(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function gn(){var a=void 0===a?{}:a;var b,c;return A(function(d){if(1==d.g)return z(d,$m(),2);if(3!=d.g){b=d.h;if(!b)return d.return();jl("LogsDatabaseV2");return z(d,km(b),3)}c=d.h;return z(d,fn(c,a,b),0)})}
function hn(a,b){b=void 0===b?{}:b;var c;return A(function(d){if(1==d.g)return z(d,$m(),2);if(3!=d.g){c=d.h;if(!c)return d.return();jl(a);return z(d,bm(a,b),3)}return z(d,im(a,c),0)})}
;function jn(a,b){cm.call(this,a,b);this.options=b;jl(a)}
w(jn,cm);function kn(a,b){var c;return function(){c||(c=new jn(a,b));return c}}
jn.prototype.h=function(a,b,c){c=void 0===c?{}:c;return(this.options.Pb?dn:cn)(a,b,Object.assign({},c))};
jn.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Pb?hn:en)(this.name,a)};
function ln(a,b){return kn(a,b)}
;var mn={},nn=ln("ytGcfConfig",{eb:(mn.coldConfigStore={lb:1},mn.hotConfigStore={lb:1},mn),Pb:!1,upgrade:function(a,b){b(1)&&(Tl(Ml(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),Tl(Ml(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function on(a){return em(nn(),a)}
function pn(a,b,c){var d,e,f;return A(function(g){switch(g.g){case 1:return d={config:a,hashData:b,timestamp:Y()},z(g,on(c),2);case 2:return e=g.h,z(g,e.clear("hotConfigStore"),3);case 3:return z(g,Ol(e,"hotConfigStore",d),4);case 4:return f=g.h,g.return(f)}})}
function qn(a,b,c,d){var e,f,g;return A(function(h){switch(h.g){case 1:return e={config:a,hashData:b,configData:c,timestamp:Y()},z(h,on(d),2);case 2:return f=h.h,z(h,f.clear("coldConfigStore"),3);case 3:return z(h,Ol(f,"coldConfigStore",e),4);case 4:return g=h.h,h.return(g)}})}
function rn(a){var b,c;return A(function(d){return 1==d.g?z(d,on(a),2):3!=d.g?(b=d.h,c=void 0,z(d,Ll(b,["coldConfigStore"],{mode:"readwrite",W:!0},function(e){return Yl(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.ja()})}),3)):d.return(c)})}
function sn(a){var b,c;return A(function(d){return 1==d.g?z(d,on(a),2):3!=d.g?(b=d.h,c=void 0,z(d,Ll(b,["hotConfigStore"],{mode:"readwrite",W:!0},function(e){return Yl(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.ja()})}),3)):d.return(c)})}
;function tn(){ye.call(this);this.h=[];this.g=[];var a=C("yt.gcf.config.hotUpdateCallbacks");a?(this.h=[].concat(v(a)),this.g=a):(this.g=[],D("yt.gcf.config.hotUpdateCallbacks",this.g))}
w(tn,ye);tn.prototype.sa=function(){for(var a=u(this.h),b=a.next();!b.done;b=a.next()){var c=this.g;b=c.indexOf(b.value);0<=b&&c.splice(b,1)}this.h.length=0;ye.prototype.sa.call(this)};function un(){this.h=0;this.i=new tn}
function vn(a,b,c){var d,e,f;return A(function(g){switch(g.g){case 1:if(!T("start_client_gcf")){g.B(0);break}c&&(a.j=c,D("yt.gcf.config.hotConfigGroup",a.j||null));a.g(b);d=Zm();if(!d){g.B(3);break}if(c){g.B(4);break}return z(g,sn(d),5);case 5:e=g.h,c=null==(f=e)?void 0:f.config;case 4:return z(g,pn(c,b,d),3);case 3:if(c)for(var h=c,k=u(a.i.g),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.g=0}})}
function wn(a,b,c){var d,e,f,g;return A(function(h){if(1==h.g){if(!T("start_client_gcf"))return h.B(0);a.coldHashData=b;D("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=Zm())?c?h.B(4):z(h,rn(d),5):h.B(0)}4!=h.g&&(e=h.h,c=null==(f=e)?void 0:f.config);if(!c)return h.B(0);g=c.configData;return z(h,qn(c,b,g,d),0)})}
un.prototype.g=function(a){this.hotHashData=a;D("yt.gcf.config.hotHashData",this.hotHashData||null)};function xn(){return"INNERTUBE_API_KEY"in bj&&"INNERTUBE_API_VERSION"in bj}
function yn(){return{ld:S("INNERTUBE_API_KEY"),md:S("INNERTUBE_API_VERSION"),Sb:S("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),wc:S("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),nd:S("INNERTUBE_CONTEXT_CLIENT_NAME",1),xc:S("INNERTUBE_CONTEXT_CLIENT_VERSION"),zc:S("INNERTUBE_CONTEXT_HL"),yc:S("INNERTUBE_CONTEXT_GL"),od:S("INNERTUBE_HOST_OVERRIDE")||"",qd:!!S("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),pd:!!S("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",!1),appInstallData:S("SERIALIZED_CLIENT_CONFIG_DATA")}}
function zn(a){var b={client:{hl:a.zc,gl:a.yc,clientName:a.wc,clientVersion:a.xc,configInfo:a.Sb}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=B.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=S("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=lj();0<c.length&&(b.request={internalExperimentFlags:c});An(a,void 0,b);Bn(void 0,b);Cn(void 0,b);Dn(a,void 0,b);En(void 0,b);T("start_client_gcf")&&Fn(void 0,b);S("DELEGATED_SESSION_ID")&&!T("pageid_as_header_web")&&
(b.user={onBehalfOfUser:S("DELEGATED_SESSION_ID")});!T("fill_delegate_context_in_gel_killswitch")&&(a=S("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=Object;c=a.assign;for(var d=b.client,e={},f=u(Object.entries(Cj(S("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=u(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=
h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function Gn(a){var b=new Gi,c=new zi;J(c,1,a.zc);J(c,2,a.yc);Kd(c,16,a.nd);J(c,17,a.xc);if(a.Sb){var d=a.Sb,e=new wi;d.coldConfigData&&J(e,1,d.coldConfigData);d.appInstallData&&J(e,6,d.appInstallData);d.coldHashData&&J(e,3,d.coldHashData);d.hotHashData&&e.g(d.hotHashData);I(c,wi,62,e)}if((d=B.devicePixelRatio)&&1!=d){if(null!=d&&"number"!==typeof d)throw Error("Value of float/double field must be a number, found "+typeof d+": "+d);wd(c,65,d)}d=S("EXPERIMENTS_TOKEN","");""!==d&&J(c,54,d);d=lj();if(0<
d.length){e=new Ci;for(var f=0;f<d.length;f++){var g=new Ai;J(g,1,d[f].key);zd(g,2,Bi,cd(d[f].value));Ed(e,15,Ai,g)}I(b,Ci,5,e)}An(a,c);Bn(b);Cn(c);Dn(a,c);En(c);T("start_client_gcf")&&Fn(c);S("DELEGATED_SESSION_ID")&&!T("pageid_as_header_web")&&(a=new Fi,J(a,3,S("DELEGATED_SESSION_ID")));!T("fill_delegate_context_in_gel_killswitch")&&(a=S("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&(d=Cd(b,Fi,3)||new Fi,a=J(d,18,a),I(b,Fi,3,a));a=u(Object.entries(Cj(S("DEVICE",""))));for(d=a.next();!d.done;d=
a.next())e=u(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?J(c,12,e):"cmodel"===d?J(c,13,e):"cbr"===d?J(c,87,e):"cbrver"===d?J(c,88,e):"cos"===d?J(c,18,e):"cosver"===d?J(c,19,e):"cplatform"===d&&Kd(c,42,mk(e));I(b,zi,1,c);return b}
function An(a,b,c){a=a.wc;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=Cd(b,xi,96)||new xi;var d=lk();d=Object.keys(Hi).indexOf(d);d=-1===d?null:d;null!==d&&Kd(c,3,d);I(b,xi,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=lk())}
function Bn(a,b){var c=C("yt.embedded_player.embed_url");c&&(a?(b=Cd(a,Di,7)||new Di,J(b,4,c),I(a,Di,7,b)):b&&(b.thirdParty={embedUrl:c}))}
function Cn(a,b){var c;if(T("web_log_memory_total_kbytes")&&(null==(c=B.navigator)?0:c.deviceMemory)){var d;c=null==(d=B.navigator)?void 0:d.deviceMemory;a?Jd(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function Dn(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=Cd(b,wi,62))?d:new wi;J(c,6,a.appInstallData);I(b,wi,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function En(a,b){a:{var c=rk();if(c){var d=nk[c.type||"unknown"]||"CONN_UNKNOWN";c=nk[c.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===d&&"CONN_UNKNOWN"!==c&&(d=c);if("CONN_UNKNOWN"!==d)break a;if("CONN_UNKNOWN"!==c){d=c;break a}}d=void 0}d&&(a?Kd(a,61,ok[d]):b&&(b.client.connectionType=d));T("web_log_effective_connection_type")&&(d=rk(),d=null!=d&&d.effectiveType?qk.hasOwnProperty(d.effectiveType)?qk[d.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,d&&(a?Kd(a,94,pk[d]):
b&&(b.client.effectiveConnectionType=d)))}
function Hn(a,b,c){c=void 0===c?{}:c;var d={};S("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":S("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||S("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.le||S("AUTHORIZATION");if(!b)if(a)b="Bearer "+C("gapi.auth.getToken")().ke;else{kk.g||(kk.g=new kk);a={};if(c=ue([]))a.Authorization=c,c=void 0,void 0===c&&(c=Number(S("SESSION_INDEX",0)),c=isNaN(c)?0:c),T("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=
c.toString()),"INNERTUBE_HOST_OVERRIDE"in bj||(a["X-Origin"]=window.location.origin),"DELEGATED_SESSION_ID"in bj&&(a["X-Goog-PageId"]=S("DELEGATED_SESSION_ID"));T("pageid_as_header_web")||delete a["X-Goog-PageId"];d=Object.assign({},d,a)}b&&(d.Authorization=b);return d}
function Fn(a,b){if(!un.g){var c=new un;un.g=c}c=un.g;var d=Y()-c.h;if(0!==c.h&&d<V("send_config_hash_timer"))c=void 0;else{d=C("yt.gcf.config.coldConfigData");var e=C("yt.gcf.config.hotHashData"),f=C("yt.gcf.config.coldHashData");d&&e&&f&&(c.h=Y());c={coldConfigData:d,hotHashData:e,coldHashData:f}}if(e=c)if(c=e.coldConfigData,d=e.coldHashData,e=e.hotHashData,c&&d&&e)if(a){var g;b=null!=(g=Cd(a,wi,62))?g:new wi;J(b,1,c);J(b,3,d);b.g(e);I(a,wi,62,b)}else b&&(b.client.configInfo=b.client.configInfo||
{},b.client.configInfo.coldConfigData=c,b.client.configInfo.coldHashData=d,b.client.configInfo.hotHashData=e)}
;var In=C("ytPubsub2Pubsub2Instance")||new L;L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.wb;L.prototype.publish=L.prototype.fb;L.prototype.clear=L.prototype.clear;D("ytPubsub2Pubsub2Instance",In);D("ytPubsub2Pubsub2SubscribedKeys",C("ytPubsub2Pubsub2SubscribedKeys")||{});D("ytPubsub2Pubsub2TopicToKeys",C("ytPubsub2Pubsub2TopicToKeys")||{});D("ytPubsub2Pubsub2IsAsync",C("ytPubsub2Pubsub2IsAsync")||{});D("ytPubsub2Pubsub2SkipSubKey",null);function Jn(a,b,c){c=void 0===c?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&(a={ye:a,xe:b},(b=C("ytPubsub2Pubsub2Instance"))&&b.publish.call(b,"meta_logging_csi_event".toString(),"meta_logging_csi_event",a))}
;var Kn=V("max_body_size_to_compress",5E5),Ln=V("min_body_size_to_compress",500),Mn=!0,Nn=0,On=0,Pn=V("compression_performance_threshold_lr",250),Qn=V("slow_compressions_before_abandon_count",4);
function Rn(a,b,c,d){var e=Y(),f={startTime:e,ticks:{},infos:{}};if(Mn)try{try{var g=(new Blob(b.split(""))).size}catch(r){jj(r),g=null}if(null==g||!(g>Kn||g<Ln)){var h=we(b);var k=k||{};k.jd=!0;var l=new ri(k);l.push(h,!0);if(l.err)throw l.msg||$g[l.err];var m=l.result;var n=Y();f.ticks.gelc=n;On++;T("disable_compression_due_to_performance_degredation")&&n-e>=Pn&&(Nn++,T("abandon_compression_after_N_slow_zips")?On===V("compression_disable_point")&&Nn>Qn&&(Mn=!1):Mn=!1);T("gel_compression_csi_killswitch")||
!T("log_gel_compression_latency")&&!T("log_gel_compression_latency_lr")||Jn("gel_compression",f,{sampleRate:.1});c.headers||(c.headers={});c.headers["Content-Encoding"]="gzip";c.postBody=m;c.postParams=void 0}d(a,c)}catch(r){jj(r),d(a,c)}else d(a,c)}
;function Sn(a){a=Object.assign({},a);delete a.Authorization;var b=ue();if(b){var c=new Sf;c.update(S("INNERTUBE_API_KEY"));c.update(b);a.hash=Cc(c.digest(),3)}return a}
;var Tn;function Un(){Tn||(Tn=new cl("yt.innertube"));return Tn}
function Vn(a,b,c,d){if(d)return null;d=Un().get("nextId",!0)||1;var e=Un().get("requests",!0)||{};e[d]={method:a,request:b,authState:Sn(c),requestTime:Math.round(Y())};Un().set("nextId",d+1,86400,!0);Un().set("requests",e,86400,!0);return d}
function Wn(a){var b=Un().get("requests",!0)||{};delete b[a];Un().set("requests",b,86400,!0)}
function Xn(a){var b=Un().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(Y())-d.requestTime)){var e=d.authState,f=Sn(Hn(!1));lb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(Y())),Yn(a,d.method,e,{}));delete b[c]}}Un().set("requests",b,86400,!0)}}
;function Zn(a){this.yb=this.g=!1;this.potentialEsfErrorCounter=this.h=0;this.handleError=function(){};
this.Wa=function(){};
this.now=Date.now;this.qb=!1;var b;this.Mc=null!=(b=a.Mc)?b:100;var c;this.Kc=null!=(c=a.Kc)?c:1;var d;this.Ic=null!=(d=a.Ic)?d:2592E6;var e;this.Hc=null!=(e=a.Hc)?e:12E4;var f;this.Jc=null!=(f=a.Jc)?f:5E3;var g;this.I=null!=(g=a.I)?g:void 0;this.Db=!!a.Db;var h;this.Bb=null!=(h=a.Bb)?h:.1;var k;this.Lb=null!=(k=a.Lb)?k:10;a.handleError&&(this.handleError=a.handleError);a.Wa&&(this.Wa=a.Wa);a.qb&&(this.qb=a.qb);a.yb&&(this.yb=a.yb);this.J=a.J;this.ha=a.ha;this.N=a.N;this.P=a.P;this.ya=a.ya;this.cc=
a.cc;this.ac=a.ac;$n(this)&&(!this.J||this.J("networkless_logging"))&&ao(this)}
function ao(a){$n(a)&&!a.qb&&(a.g=!0,a.Db&&Math.random()<=a.Bb&&a.N.Zc(a.I),bo(a),a.P.ca()&&a.vb(),a.P.Oa(a.cc,a.vb.bind(a)),a.P.Oa(a.ac,a.lc.bind(a)))}
q=Zn.prototype;q.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if($n(this)&&this.g){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.N.set(d,this.I).then(function(e){d.id=e;c.P.ca()&&co(c,d)}).catch(function(e){co(c,d);
eo(c,e)})}else this.ya(a,b)};
q.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if($n(this)&&this.g){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.J&&this.J("nwl_skip_retry")&&(e.skipRetry=c);if(this.P.ca()||this.J&&this.J("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return A(function(k){if(1==k.g)return z(k,d.N.set(e,d.I).catch(function(l){eo(d,l)}),2);
f(g,h);k.g=0})}}this.ya(a,b,e.skipRetry)}else this.N.set(e,this.I).catch(function(g){d.ya(a,b,e.skipRetry);
eo(d,g)})}else this.ya(a,b,this.J&&this.J("nwl_skip_retry")&&c)};
q.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if($n(this)&&this.g){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.N.Va(d.id,c.I):e=!0;c.P.Qa&&c.J&&c.J("vss_network_hint")&&c.P.Qa(!0);f(g,h)};
this.ya(d.url,d.options);this.N.set(d,this.I).then(function(g){d.id=g;e&&c.N.Va(d.id,c.I)}).catch(function(g){eo(c,g)})}else this.ya(a,b)};
q.vb=function(){var a=this;if(!$n(this))throw Error("IndexedDB is not supported: throttleSend");this.h||(this.h=this.ha.qa(function(){var b;return A(function(c){if(1==c.g)return z(c,a.N.sc("NEW",a.I),2);if(3!=c.g)return b=c.h,b?z(c,co(a,b),3):(a.lc(),c.return());a.h&&(a.h=0,a.vb());c.g=0})},this.Mc))};
q.lc=function(){this.ha.ba(this.h);this.h=0};
function co(a,b){var c;return A(function(d){switch(d.g){case 1:if(!$n(a))throw Error("IndexedDB is not supported: immediateSend");if(void 0===b.id){d.B(2);break}return z(d,a.N.sd(b.id,a.I),3);case 3:(c=d.h)||a.Wa(Error("The request cannot be found in the database."));case 2:if(fo(a,b,a.Ic)){d.B(4);break}a.Wa(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){d.B(5);break}return z(d,a.N.Va(b.id,a.I),5);case 5:return d.return();case 4:b.skipRetry||(b=go(a,b));if(!b){d.B(0);
break}if(!b.skipRetry||void 0===b.id){d.B(8);break}return z(d,a.N.Va(b.id,a.I),8);case 8:a.ya(b.url,b.options,!!b.skipRetry),d.g=0}})}
function go(a,b){if(!$n(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return A(function(m){switch(m.g){case 1:g=ho(f);(h=io(f))&&a.J&&a.J("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.J&&a.J("nwl_consider_error_code")&&g||a.J&&!a.J("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.Lb)){m.B(2);break}if(!a.P.Ob){m.B(3);break}return z(m,a.P.Ob(),3);case 3:if(a.P.ca()){m.B(2);break}c(e,f);if(!a.J||!a.J("nwl_consider_error_code")||void 0===(null==(k=b)?void 0:k.id)){m.B(6);
break}return z(m,a.N.dc(b.id,a.I,!1),6);case 6:return m.return();case 2:if(a.J&&a.J("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.Lb)return m.return();a.potentialEsfErrorCounter++;if(void 0===(null==(l=b)?void 0:l.id)){m.B(8);break}return b.sendCount<a.Kc?z(m,a.N.dc(b.id,a.I,!0,h?!1:void 0),12):z(m,a.N.Va(b.id,a.I),8);case 12:a.ha.qa(function(){a.P.ca()&&a.vb()},a.Jc);
case 8:c(e,f),m.g=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return A(function(h){if(1==h.g)return void 0===(null==(g=b)?void 0:g.id)?h.B(2):z(h,a.N.Va(b.id,a.I),2);a.P.Qa&&a.J&&a.J("vss_network_hint")&&a.P.Qa(!0);d(e,f);h.g=0})};
return b}
function fo(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function bo(a){if(!$n(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.N.sc("QUEUED",a.I).then(function(b){b&&!fo(a,b,a.Hc)?a.ha.qa(function(){return A(function(c){if(1==c.g)return void 0===b.id?c.B(2):z(c,a.N.dc(b.id,a.I),2);bo(a);c.g=0})}):a.P.ca()&&a.vb()})}
function eo(a,b){a.Oc&&!a.P.ca()?a.Oc(b):a.handleError(b)}
function $n(a){return!!a.I||a.yb}
function ho(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
function io(a){var b;a=null==a?void 0:null==(b=a.error)?void 0:b.code;return!(400!==a&&415!==a)}
;var jo;
function ko(){if(jo)return jo();var a={};jo=ln("LogsDatabaseV2",{eb:(a.LogsRequestsStore={lb:2},a),Pb:!1,upgrade:function(b,c,d){c(2)&&Ml(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.g.indexNames.contains("newRequest")&&d.g.deleteIndex("newRequest"),Tl(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.g.objectStoreNames.contains("sapisid")&&b.g.deleteObjectStore("sapisid");c(9)&&b.g.objectStoreNames.contains("SWHealthLog")&&b.g.deleteObjectStore("SWHealthLog")},
version:9});return jo()}
;function lo(a){return em(ko(),a)}
function mo(a,b){var c,d,e,f;return A(function(g){if(1==g.g)return c={startTime:Y(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},z(g,lo(b),2);if(3!=g.g)return d=g.h,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:S("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),z(g,Ol(d,"LogsRequestsStore",e),3);f=g.h;c.ticks.tc=Y();no(c);return g.return(f)})}
function oo(a,b){var c,d,e,f,g,h,k;return A(function(l){if(1==l.g)return c={startTime:Y(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},z(l,lo(b),2);if(3!=l.g)return d=l.h,e=S("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,Y()],h=IDBKeyRange.bound(f,g),k=void 0,z(l,Ll(d,["LogsRequestsStore"],{mode:"readwrite",W:!0},function(m){return Yl(m.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(n){n.ja()&&(k=n.ja(),"NEW"===a&&(k.status="QUEUED",
n.update(k)))})}),3);
c.ticks.tc=Y();no(c);return l.return(k)})}
function po(a,b){var c;return A(function(d){if(1==d.g)return z(d,lo(b),2);c=d.h;return d.return(Ll(c,["LogsRequestsStore"],{mode:"readwrite",W:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Hl(f.g.put(g,void 0)).then(function(){return g})})}))})}
function qo(a,b,c,d){c=void 0===c?!0:c;var e;return A(function(f){if(1==f.g)return z(f,lo(b),2);e=f.h;return f.return(Ll(e,["LogsRequestsStore"],{mode:"readwrite",W:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),void 0!==d&&(k.options.compress=d),Hl(h.g.put(k,void 0)).then(function(){return k})):Al.resolve(void 0)})}))})}
function ro(a,b){var c;return A(function(d){if(1==d.g)return z(d,lo(b),2);c=d.h;return d.return(c.delete("LogsRequestsStore",a))})}
function so(a){var b,c;return A(function(d){if(1==d.g)return z(d,lo(a),2);b=d.h;c=Y()-2592E6;return z(d,Ll(b,["LogsRequestsStore"],{mode:"readwrite",W:!0},function(e){return Vl(e.objectStore("LogsRequestsStore"),{},function(f){if(f.ja().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function to(){A(function(a){return z(a,gn(),0)})}
function no(a){T("nwl_csi_killswitch")||Jn("networkless_performance",a,{sampleRate:1})}
;var uo={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,mbsConnectionInitiated:138,mbsPlaybackInitiated:139,
mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,kidsParentalGateTracking:168,kidsSignedOutSettingsStatus:437,
kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,transactionFlowPaymentSubmitted:460,
transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,ypcPauseFlowSucceeded:190,
ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,ypcFamilyCreateFlowCancelled:259,
ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,accountRegistryChange:226,
userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,musicSideloadedPlaylistServiceCalled:246,
embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,tvhtml5ApiTest:270,yongleUsbSetup:271,touStrikeInterstitialEvent:272,
liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,
delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,
voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,
sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,
clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,
startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,
playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,genericClientExperimentEvent:423,
homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,lockModeTimeoutEvent:483,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,mangoDailyNewVideosNotificationAttempt:40,mangoDailyNewVideosNotificationError:77,dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,
dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,cruiseControlEvent:445,qoeClientLoggingContext:446,atvRecommendationJobExecuted:447,tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,
producerProjectElementAdded:453,producerProjectElementRemoved:454,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,webKillswitchReceived:473,webKillswitchExecuted:474,cameraOpenEvent:475,manualSmoothnessMeasurement:476,tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,
cobaltTelemetryEvent:481,crossDevicePlayback:482,channelCreatedWithObakeImage:484,channelEditedWithObakeImage:485};var vo={},wo=ln("ServiceWorkerLogsDatabase",{eb:(vo.SWHealthLog={lb:1},vo),Pb:!0,upgrade:function(a,b){b(1)&&Tl(Ml(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function xo(a){return em(wo(),a)}
function yo(a){var b,c;A(function(d){if(1==d.g)return z(d,xo(a),2);b=d.h;c=Y()-2592E6;return z(d,Ll(b,["SWHealthLog"],{mode:"readwrite",W:!0},function(e){return Vl(e.objectStore("SWHealthLog"),{},function(f){if(f.ja().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function zo(a){var b;return A(function(c){if(1==c.g)return z(c,xo(a),2);b=c.h;return z(c,b.clear("SWHealthLog"),0)})}
;var Ao={},Bo=0;function Co(a){var b=new Image,c=""+Bo++;Ao[c]=b;b.onload=b.onerror=function(){delete Ao[c]};
b.src=a}
;function Do(){this.g=new Map;this.h=!1}
function Eo(){if(!Do.g){var a=C("yt.networkRequestMonitor.instance")||new Do;D("yt.networkRequestMonitor.instance",a);Do.g=a}return Do.g}
Do.prototype.requestComplete=function(a,b){b&&(this.h=!0);a=this.removeParams(a);this.g.get(a)||this.g.set(a,b)};
Do.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.g.get(a))?!1:!1===a&&this.h?!0:null};
Do.prototype.removeParams=function(a){return a.split("?")[0]};
Do.prototype.removeParams=Do.prototype.removeParams;Do.prototype.isEndpointCFR=Do.prototype.isEndpointCFR;Do.prototype.requestComplete=Do.prototype.requestComplete;Do.getInstance=Eo;var Fo;function Go(){Fo||(Fo=new cl("yt.offline"));return Fo}
function Ho(a){if(T("offline_error_handling")){var b=Go().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Go().set("errors",b,2592E3,!0)}}
;function Z(){af.call(this);var a=this;this.i=!1;this.h=gf();this.h.Oa("networkstatus-online",function(){if(a.i&&T("offline_error_handling")){var b=Go().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new sk(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;ij(d)}Go().set("errors",{},2592E3,!0)}}})}
w(Z,af);function Io(){if(!Z.g){var a=C("yt.networkStatusManager.instance")||new Z;D("yt.networkStatusManager.instance",a);Z.g=a}return Z.g}
q=Z.prototype;q.ca=function(){return this.h.ca()};
q.Qa=function(a){this.h.h=a};
q.gd=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
q.cd=function(){this.i=!0};
q.Oa=function(a,b){return this.h.Oa(a,b)};
q.Ob=function(a){a=ef(this.h,a);a.then(function(b){T("use_cfr_monitor")&&Eo().requestComplete("generate_204",b)});
return a};
Z.prototype.sendNetworkCheckRequest=Z.prototype.Ob;Z.prototype.listen=Z.prototype.Oa;Z.prototype.enableErrorFlushing=Z.prototype.cd;Z.prototype.getWindowStatus=Z.prototype.gd;Z.prototype.networkStatusHint=Z.prototype.Qa;Z.prototype.isNetworkAvailable=Z.prototype.ca;Z.getInstance=Io;function Jo(a){a=void 0===a?{}:a;af.call(this);var b=this;this.h=this.o=0;this.i=Io();var c=C("yt.networkStatusManager.instance.listen").bind(this.i);c&&(a.Nb?(this.Nb=a.Nb,c("networkstatus-online",function(){Ko(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Ko(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){bf(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){bf(b,"publicytnetworkstatus-offline")})))}
w(Jo,af);Jo.prototype.ca=function(){var a=C("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.i)():!0};
Jo.prototype.Qa=function(a){var b=C("yt.networkStatusManager.instance.networkStatusHint").bind(this.i);b&&b(a)};
Jo.prototype.Ob=function(a){var b=this,c;return A(function(d){c=C("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.i);return T("skip_network_check_if_cfr")&&Eo().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.Qa((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.ca())})):c?d.return(c(a)):d.return(!0)})};
function Ko(a,b){a.Nb?a.h?(hf.ba(a.o),a.o=hf.qa(function(){a.j!==b&&(bf(a,b),a.j=b,a.h=Y())},a.Nb-(Y()-a.h))):(bf(a,b),a.j=b,a.h=Y()):bf(a,b)}
;var Lo;function Mo(){var a=Zn.call;Lo||(Lo=new Jo({pe:!0,oe:!0}));a.call(Zn,this,{N:{Zc:so,Va:ro,sc:oo,sd:po,dc:qo,set:mo},P:Lo,handleError:function(b,c,d){var e,f=null==d?void 0:null==(e=d.error)?void 0:e.code;if(400===f||415===f){var g;jj(new sk(b.message,c,null==d?void 0:null==(g=d.error)?void 0:g.code),void 0,void 0,void 0,!0)}else ij(b)},
Wa:jj,ya:No,now:Y,Oc:Ho,ha:bl(),cc:"publicytnetworkstatus-online",ac:"publicytnetworkstatus-offline",Db:!0,Bb:.1,Lb:V("potential_esf_error_limit",10),J:T,qb:!(tk()&&"www.youtube-nocookie.com"!==Xb(document.location.toString()))});this.i=new gg;T("networkless_immediately_drop_all_requests")&&to();hn("LogsDatabaseV2")}
w(Mo,Zn);function Oo(){var a=C("yt.networklessRequestController.instance");a||(a=new Mo,D("yt.networklessRequestController.instance",a),T("networkless_logging")&&$m().then(function(b){a.I=b;ao(a);a.i.resolve();a.Db&&Math.random()<=a.Bb&&a.I&&yo(a.I);T("networkless_immediately_drop_sw_health_store")&&Po(a)}));
return a}
Mo.prototype.writeThenSend=function(a,b){b||(b={});tk()||(this.g=!1);Zn.prototype.writeThenSend.call(this,a,b)};
Mo.prototype.sendThenWrite=function(a,b,c){b||(b={});tk()||(this.g=!1);Zn.prototype.sendThenWrite.call(this,a,b,c)};
Mo.prototype.sendAndWrite=function(a,b){b||(b={});tk()||(this.g=!1);Zn.prototype.sendAndWrite.call(this,a,b)};
Mo.prototype.awaitInitialization=function(){return this.i.promise};
function Po(a){var b;A(function(c){if(!a.I)throw b=wl("clearSWHealthLogsDb"),b;return c.return(zo(a.I).catch(function(d){a.handleError(d)}))})}
function No(a,b,c){b=T("web_fp_via_jspb")?Object.assign({},b):b;T("use_cfr_monitor")&&Qo(a,b);if(T("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(Y())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(Y())}if(c&&0===Object.keys(b).length){var e=void 0===e?"":e;var f=void 0===f?!1:f;var g=void 0===g?!1:g;if(a)if(e)Sj(a,void 0,"POST",e);else if(S("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))Sj(a,void 0,"GET",
"",void 0,void 0,f,g);else{b:{try{var h=new Ya({url:a});if(h.i&&h.h||h.j){var k=Wb(a.match(Vb)[5]||null);var l=!(!k||!k.endsWith("/aclk")||"1"!==bc(a,"ri"));break b}}catch(n){}l=!1}if(l){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var m=!0;break b}}catch(n){}m=!1}c=m?!0:!1}else c=!1;c||Co(a)}}else b.compress?b.postBody?("string"!==typeof b.postBody&&(b.postBody=JSON.stringify(b.postBody)),Rn(a,b.postBody,b,Pj)):Rn(a,JSON.stringify(b.postParams),b,Xj):
Pj(a,b)}
function Qo(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Eo().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Eo().requestComplete(a,!0);d(e,f)}}
;var Ro=B.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:!1};D("ytNetworklessLoggingInitializationOptions",Ro);function So(a){var b=this;this.config_=null;a?this.config_=a:xn()&&(this.config_=yn());wk(function(){Xn(b)},5E3)}
So.prototype.isReady=function(){!this.config_&&xn()&&(this.config_=yn());return!!this.config_};
function Yn(a,b,c,d){function e(x){x=void 0===x?!1:x;var y;if(d.retry&&"www.youtube-nocookie.com"!=h&&(x||T("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(y=Vn(b,c,l,k)),y)){var F=g.onSuccess,O=g.onFetchSuccess;g.onSuccess=function(Q,Fa){Wn(y);F(Q,Fa)};
c.onFetchSuccess=function(Q,Fa){Wn(y);O(Q,Fa)}}try{if(x&&d.retry&&!d.Cc.bypassNetworkless)g.method="POST",d.Cc.writeThenSend?Oo().writeThenSend(p,g):Oo().sendAndWrite(p,g);
else if(d.compress)if(g.postBody){var U=g.postBody;"string"!==typeof U&&(U=JSON.stringify(g.postBody));Rn(p,U,g,Pj)}else Rn(p,JSON.stringify(g.postParams),g,Xj);else T("web_all_payloads_via_jspb")?Pj(p,g):Xj(p,g)}catch(Q){if("InvalidAccessError"==Q.name)y&&(Wn(y),y=0),jj(Error("An extension is blocking network request."));else throw Q;}y&&wk(function(){Xn(a)},5E3)}
!S("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&jj(new sk("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new sk("innertube xhrclient not ready",b,c,d);ij(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(x,y){if(d.onSuccess)d.onSuccess(y)},
onFetchSuccess:function(x){if(d.onSuccess)d.onSuccess(x)},
onError:function(x,y){if(d.onError)d.onError(y)},
onFetchError:function(x){if(d.onError)d.onError(x)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.od)&&(h=f);var k=a.config_.qd||!1,l=Hn(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var m="/youtubei/"+a.config_.md+"/"+b,n={alt:"json"},r=a.config_.pd&&f;r=r&&f.startsWith("Bearer");r||(n.key=a.config_.ld);var p=Dj(""+h+m,n||{},!0);C("ytNetworklessLoggingInitializationOptions")&&
Ro.isNwlInitialized?Ym().then(function(x){e(x)}):e(!1)}
;function To(){var a=C("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var Uo=B.ytPubsubPubsubInstance||new L,Vo=B.ytPubsubPubsubSubscribedKeys||{},Wo=B.ytPubsubPubsubTopicToKeys||{},Xo=B.ytPubsubPubsubIsSynchronous||{};L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.wb;L.prototype.publish=L.prototype.fb;L.prototype.clear=L.prototype.clear;D("ytPubsubPubsubInstance",Uo);D("ytPubsubPubsubTopicToKeys",Wo);D("ytPubsubPubsubIsSynchronous",Xo);D("ytPubsubPubsubSubscribedKeys",Vo);var Yo=Symbol("injectionDeps");function Zo(){this.key=un}
function $o(){this.h=new Map;this.g=new Map}
$o.prototype.resolve=function(a){return a instanceof Zo?ap(this,a.key,[],!0):ap(this,a,[])};
function ap(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.g.has(b))return a.g.get(b);if(!a.h.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.h.get(b);c.push(b);if(void 0!==d.Gd)var e=d.Gd;else if(d.Fd)e=d[Yo]?bp(a,d[Yo],c):[],e=d.Fd.apply(d,v(e));else if(d.Ed){e=d.Ed;var f=e[Yo]?bp(a,e[Yo],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(v(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.we||a.g.set(b,e);return e}
function bp(a,b,c){return b?b.map(function(d){return d instanceof Zo?ap(a,d.key,c,!0):ap(a,d,c)}):[]}
;var cp;function dp(){cp||(cp=new $o);return cp}
;var ep=window;function fp(){var a,b;return"h5vcc"in ep&&(null==(a=ep.h5vcc.traceEvent)?0:a.traceBegin)&&(null==(b=ep.h5vcc.traceEvent)?0:b.traceEnd)?1:"performance"in ep&&ep.performance.mark&&ep.performance.measure?2:0}
function gp(a){switch(fp()){case 1:ep.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:ep.performance.mark(a+"-start");break;case 0:break;default:Xd()}}
function hp(a){switch(fp()){case 1:ep.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:var b=a+"-start",c=a+"-end";ep.performance.mark(c);ep.performance.measure(a,b,c);break;case 0:break;default:Xd()}}
;var ip=T("web_enable_lifecycle_monitoring")&&0!==fp(),jp=T("web_enable_lifecycle_monitoring");function kp(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?bl():d;this.j=c;this.h=d;this.i=new gg;this.g=a;for(a={Ma:0};a.Ma<this.g.length;a={sb:a.sb,Ma:a.Ma},a.Ma++)a.sb=this.g[a.Ma],c=function(e){return function(){e.sb.Ub();b.g[e.Ma].Mb=!0;b.g.every(function(f){return!0===f.Mb})&&b.i.resolve()}}(a),d=this.h.Ia(c,lp(this,a.sb)),this.g[a.Ma]=Object.assign({},a.sb,{Ub:c,
jobId:d})}
function mp(a){var b=Array.from(a.g.keys()).sort(function(d,e){return lp(a,a.g[e])-lp(a,a.g[d])});
b=u(b);for(var c=b.next();!c.done;c=b.next())c=a.g[c.value],void 0===c.jobId||c.Mb||(a.h.ba(c.jobId),a.h.Ia(c.Ub,10))}
kp.prototype.cancel=function(){for(var a=u(this.g),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.Mb||this.h.ba(b.jobId),b.Mb=!0;this.i.resolve()};
function lp(a,b){var c;return null!=(c=b.priority)?c:a.j}
;function np(a){this.state=a;this.i=[];this.o=void 0;this.H={};ip&&gp(this.state)}
np.prototype.install=function(a){this.i.push(a);return this};
function op(a){ip&&hp(a.state);var b=a.transitions.find(function(d){return Array.isArray(d.from)?d.from.find(function(e){return e===a.state&&"none"===d.Fa}):d.from===a.state&&"none"===d.Fa});
if(b){a.h&&(mp(a.h),a.h=void 0);jp&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to 'none'"),console.log("with message: ",void 0),console.groupEnd());a.state="none";ip&&gp(a.state);b=b.action.bind(a);var c=a.i.filter(function(d){return d.none}).map(function(d){return d.none});
b(pp(a,c),void 0)}else throw Error("no transition specified from "+a.state+" to none");}
function pp(a,b){var c=b.filter(function(e){return 10===qp(a,e)}),d=b.filter(function(e){return 10!==qp(a,e)});
return a.H.ue?function(){var e=Ea.apply(0,arguments);return A(function(f){if(1==f.g)return z(f,a.oa.apply(a,[c].concat(v(e))),2);a.u.apply(a,[d].concat(v(e)));f.g=0})}:function(){var e=Ea.apply(0,arguments);
a.za.apply(a,[c].concat(v(e)));a.u.apply(a,[d].concat(v(e)))}}
np.prototype.za=function(a){for(var b=Ea.apply(1,arguments),c=bl(),d=u(a),e=d.next(),f={};!e.done;f={Za:f.Za},e=d.next())f.Za=e.value,c.kb(function(g){return function(){rp(g.Za.name);g.Za.nb.apply(g.Za,v(b));sp(g.Za.name)}}(f))};
np.prototype.oa=function(a){var b=Ea.apply(1,arguments),c,d,e,f,g;return A(function(h){1==h.g&&(c=bl(),d=u(a),e=d.next(),f={});if(3!=h.g){if(e.done)return h.B(0);f.Na=e.value;f.mb=void 0;g=function(k){return function(){rp(k.Na.name);var l=k.Na.nb.apply(k.Na,v(b));"function"===typeof(null==l?void 0:l.then)?k.mb=l.then(function(){sp(k.Na.name)}):sp(k.Na.name)}}(f);
c.kb(g);return f.mb?z(h,f.mb,3):h.B(3)}f={Na:f.Na,mb:f.mb};e=d.next();return h.B(2)})};
np.prototype.u=function(a){var b=Ea.apply(1,arguments),c=this,d=a.map(function(e){return{Ub:function(){rp(e.name);e.nb.apply(e,v(b));sp(e.name)},
priority:qp(c,e)}});
d.length&&(this.h=new kp(d))};
function qp(a,b){var c,d;return null!=(d=null!=(c=a.o)?c:b.priority)?d:0}
function rp(a){ip&&a&&gp(a)}
function sp(a){ip&&a&&hp(a)}
fa.Object.defineProperties(np.prototype,{j:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function tp(a){np.call(this,void 0===a?"none":a);this.g=null;this.o=10;this.transitions=[{from:"none",Fa:"application_navigating",action:this.M},{from:"application_navigating",Fa:"none",action:this.S},{from:"application_navigating",Fa:"application_navigating",action:function(){}},
{from:"none",Fa:"none",action:function(){}}]}
var up;w(tp,np);tp.prototype.M=function(a,b){var c=this;this.g=wk(function(){"application_navigating"===c.j&&op(c)},5E3);
a(null==b?void 0:b.event)};
tp.prototype.S=function(a,b){this.g&&(hf.ba(this.g),this.g=null);a(null==b?void 0:b.event)};
function vp(){up||(up=new tp);return up}
;function wp(){this.store={};this.g={}}
wp.prototype.storePayload=function(a,b){a=xp(a);this.store[a]?this.store[a].push(b):(this.g={},this.store[a]=[b]);return a};
wp.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=yp(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,v(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,v(this.store[b[d]].splice(0,a.sizeLimit))));(null==a?0:a.sizeLimit)&&c.length<(null==a?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,v(this.smartExtractMatchingEntries(a))));return c};
wp.prototype.extractMatchingEntries=function(a){a=yp(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,v(this.store[a[c]])),delete this.store[a[c]]);return b};
wp.prototype.getSequenceCount=function(a){a=yp(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=(null==(d=this.store[a[c]])?void 0:d.length)||0}return b};
function yp(a,b){var c=xp(b);if(a.g[c])return a.g[c];var d=Object.keys(a.store)||[];if(1>=d.length&&xp(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(zp(b.auth,g[0])){var h=b.isJspb;zp(void 0===h?"undefined":h?"true":"false",g[1])&&zp(b.cttAuthInfo,g[2])&&(h=b.tier,h=void 0===h?"undefined":JSON.stringify(h),zp(h,g[3])&&e.push(d[f]))}}return a.g[c]=e}
function zp(a,b){return void 0===a||"undefined"===a?!0:a===b}
wp.prototype.getSequenceCount=wp.prototype.getSequenceCount;wp.prototype.extractMatchingEntries=wp.prototype.extractMatchingEntries;wp.prototype.smartExtractMatchingEntries=wp.prototype.smartExtractMatchingEntries;wp.prototype.storePayload=wp.prototype.storePayload;function xp(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo,void 0===a.tier?"undefined":a.tier].join("/")}
;var Ap=V("initial_gel_batch_timeout",2E3),Bp=V("gel_queue_timeout_max_ms",6E4),Cp=Math.pow(2,16)-1,Dp=V("gel_min_batch_size",5),Ep=void 0;function Fp(){this.j=this.g=this.h=0;this.i=!1}
var Gp=new Fp,Hp=new Fp,Ip=new Fp,Jp=new Fp,Kp,Lp=!0,Mp=B.ytLoggingTransportTokensToCttTargetIds_||{};D("ytLoggingTransportTokensToCttTargetIds_",Mp);var Np=B.ytLoggingTransportTokensToJspbCttTargetIds_||{};D("ytLoggingTransportTokensToJspbCttTargetIds_",Np);var Op={};function Pp(){var a=C("yt.logging.ims");a||(a=new wp,D("yt.logging.ims",a));return a}
function Qp(a,b){if("log_event"===a.endpoint){Rp(a);var c=Sp(a),d=Tp(a.payload)||"",e=Up(d),f=200;if(e){if(!1===e.enabled&&!T("web_payload_policy_disabled_killswitch"))return;f=Vp(e.tier);if(400===f){Wp(a,b);return}}Op[c]=!0;e={cttAuthInfo:c,isJspb:!1,tier:f};Pp().storePayload(e,a.payload);Xp(b,c,!1,e,Yp(d))}}
function Zp(a,b,c){if("log_event"===b.endpoint){Rp(void 0,b);var d=Sp(b,!0),e=Up(a),f=200;if(e){if(!1===e.enabled&&!T("web_payload_policy_disabled_killswitch"))return;f=Vp(e.tier);if(400===f){$p(a,b,c);return}}Op[d]=!0;e={cttAuthInfo:d,isJspb:!0,tier:f};Pp().storePayload(e,b.payload.toJSON());Xp(c,d,!0,e,Yp(a))}}
function Xp(a,b,c,d,e){function f(){aq({writeThenSend:!0},T("flush_only_full_queue")?b:void 0,c,d.tier)}
c=void 0===c?!1:c;e=void 0===e?!1:e;a&&(Ep=new a);a=V("tvhtml5_logging_max_batch_ads_fork")||V("web_logging_max_batch")||100;var g=Y(),h=bq(c,d.tier),k=h.j;e&&(h.i=!0);e=0;d&&(e=Pp().getSequenceCount(d));1E3<=e?f():e>=a?Kp||(Kp=cq(function(){f();Kp=void 0},0)):10<=g-k&&(dq(c,d.tier),h.j=g)}
function Wp(a,b){if("log_event"===a.endpoint){Rp(a);var c=Sp(a),d=new Map;d.set(c,[a.payload]);var e=Tp(a.payload)||"";b&&(Ep=new b);return new hg(function(f,g){Ep&&Ep.isReady()?eq(d,Ep,f,g,{bypassNetworkless:!0},!0,Yp(e)):f()})}}
function $p(a,b,c){if("log_event"===b.endpoint){Rp(void 0,b);var d=Sp(b,!0),e=new Map;e.set(d,[b.payload.toJSON()]);c&&(Ep=new c);return new hg(function(f){Ep&&Ep.isReady()?fq(e,Ep,f,{bypassNetworkless:!0},!0,Yp(a)):f()})}}
function Sp(a,b){var c="";if(a.dangerousLogToVisitorSession)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new Xi;c.videoId?zd(d,1,Hd,cd(c.videoId)):c.playlistId&&zd(d,2,Hd,cd(c.playlistId));Np[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),Mp[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function aq(a,b,c,d){a=void 0===a?{}:a;c=void 0===c?!1:c;new hg(function(e,f){var g=bq(c,d),h=g.i;g.i=!1;gq(g.h);gq(g.g);g.g=0;Ep&&Ep.isReady()?void 0===d&&T("enable_web_tiered_gel")?hq(e,f,a,b,c,300,h):hq(e,f,a,b,c,d,h):(dq(c,d),e())})}
function hq(a,b,c,d,e,f,g){var h=Ep;c=void 0===c?{}:c;e=void 0===e?!1:e;f=void 0===f?200:f;g=void 0===g?!1:g;var k=new Map,l=new Map,m={isJspb:e,cttAuthInfo:d,tier:f},n={isJspb:e,cttAuthInfo:d};if(void 0!==d)e?(b=T("enable_web_tiered_gel")?Pp().smartExtractMatchingEntries({keys:[m,n],sizeLimit:1E3}):Pp().extractMatchingEntries(n),k.set(d,b),fq(k,h,a,c,!1,g)):(k=T("enable_web_tiered_gel")?Pp().smartExtractMatchingEntries({keys:[m,n],sizeLimit:1E3}):Pp().extractMatchingEntries(n),l.set(d,k),eq(l,h,
a,b,c,!1,g));else if(e){b=u(Object.keys(Op));for(d=b.next();!d.done;d=b.next())l=d.value,f=T("enable_web_tiered_gel")?Pp().smartExtractMatchingEntries({keys:[m,n],sizeLimit:1E3}):Pp().extractMatchingEntries({isJspb:!0,cttAuthInfo:l}),0<f.length&&k.set(l,f),(T("web_fp_via_jspb_and_json")&&c.writeThenSend||!T("web_fp_via_jspb_and_json"))&&delete Op[l];fq(k,h,a,c,!1,g)}else{k=u(Object.keys(Op));for(d=k.next();!d.done;d=k.next())m=d.value,n=T("enable_web_tiered_gel")?Pp().smartExtractMatchingEntries({keys:[{isJspb:!1,
cttAuthInfo:m,tier:f},{isJspb:!1,cttAuthInfo:m}],sizeLimit:1E3}):Pp().extractMatchingEntries({isJspb:!1,cttAuthInfo:m}),0<n.length&&l.set(m,n),(T("web_fp_via_jspb_and_json")&&c.writeThenSend||!T("web_fp_via_jspb_and_json"))&&delete Op[m];eq(l,h,a,b,c,!1,g)}}
function dq(a,b){function c(){aq({writeThenSend:!0},void 0,a,b)}
a=void 0===a?!1:a;b=void 0===b?200:b;var d=bq(a,b),e=d===Jp||d===Ip?5E3:Bp;T("web_gel_timeout_cap")&&!d.g&&(e=cq(function(){c()},e),d.g=e);
gq(d.h);e=S("LOGGING_BATCH_TIMEOUT",V("web_gel_debounce_ms",1E4));T("shorten_initial_gel_batch_timeout")&&Lp&&(e=Ap);e=cq(function(){0<V("gel_min_batch_size")?Pp().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=Dp&&c():c()},e);
d.h=e}
function eq(a,b,c,d,e,f,g){e=void 0===e?{}:e;var h=Math.round(Y()),k=a.size,l=iq(g);a=u(a);var m=a.next();for(g={};!m.done;g={Hb:g.Hb,Ja:g.Ja,dangerousLogToVisitorSession:g.dangerousLogToVisitorSession,Jb:g.Jb,Ib:g.Ib},m=a.next()){var n=u(m.value);m=n.next().value;n=n.next().value;g.Ja=mb({context:zn(b.config_||yn())});if(!La(n)&&!T("throw_err_when_logevent_malformed_killswitch")){d();break}g.Ja.events=n;(n=Mp[m])&&jq(g.Ja,m,n);delete Mp[m];g.dangerousLogToVisitorSession="visitorOnlyApprovedKey"===
m;kq(g.Ja,h,g.dangerousLogToVisitorSession);lq(e);g.Jb=function(r){T("start_client_gcf")&&hf.qa(function(){return A(function(p){return z(p,mq(r),0)})});
k--;k||c()};
g.Hb=0;g.Ib=function(r){return function(){r.Hb++;if(e.bypassNetworkless&&1===r.Hb)try{Yn(b,l,r.Ja,nq({writeThenSend:!0},r.dangerousLogToVisitorSession,r.Jb,r.Ib,f)),Lp=!1}catch(p){ij(p),d()}k--;k||c()}}(g);
try{Yn(b,l,g.Ja,nq(e,g.dangerousLogToVisitorSession,g.Jb,g.Ib,f)),Lp=!1}catch(r){ij(r),d()}}}
function fq(a,b,c,d,e,f){d=void 0===d?{}:d;var g=Math.round(Y()),h=a.size;f=iq(f);var k=new Map([].concat(v(a)));k=u(k);for(var l=k.next();!l.done;l=k.next()){var m=u(l.value).next().value,n=a.get(m);l=new Yi;var r=Gn(b.config_||yn());I(l,Gi,1,r);n=n?oq(n):[];n=u(n);for(r=n.next();!r.done;r=n.next())Ed(l,3,Ui,r.value);(n=Np[m])&&pq(l,m,n);delete Np[m];m="visitorOnlyApprovedKey"===m;qq(l,g,m);lq(d);n={startTime:Y(),ticks:{},infos:{}};l=Md(l);n.ticks.geljspc=Y();T("log_jspb_serialize_latency")&&Jn("gel_jspb_serialize",
n,{sampleRate:.1});m=nq(d,m,function(p){T("start_client_gcf")&&hf.qa(function(){return A(function(x){return z(x,mq(p),0)})});
h--;h||c()},function(){h--;
h||c()},e);
m.headers["Content-Type"]="application/json+protobuf";m.postBodyFormat="JSPB";m.postBody=l;Yn(b,f,"",m);Lp=!1}}
function lq(a){T("always_send_and_write")&&(a.writeThenSend=!1)}
function nq(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,Cc:a,dangerousLogToVisitorSession:b,ne:!!e,headers:{},postBodyFormat:"",postBody:"",compress:T("compress_gel")||T("compress_gel_lr")};rq()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(Y())));return a}
function kq(a,b,c){rq()||(a.requestTimeMs=String(b));T("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=S("EVENT_ID"))&&(c=sq(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function qq(a,b,c){rq()||Jd(a,2,b);if(!c&&(b=S("EVENT_ID"))){c=sq();var d=new Wi;J(d,1,b);Jd(d,2,c);I(a,Wi,5,d)}}
function sq(){var a=S("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*Cp/2));a++;a>Cp&&(a=1);cj("BATCH_CLIENT_COUNTER",a);return a}
function jq(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function pq(a,b,c){if(Gd(c,1))var d=1;else if(c.getPlaylistId())d=2;else return;I(a,Xi,4,c);a=Cd(a,Gi,1)||new Gi;c=Cd(a,Fi,3)||new Fi;var e=new Ei;J(e,2,b);Kd(e,1,d);Ed(c,12,Ei,e);I(a,Fi,3,c)}
function oq(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new Ui(a[c]))}catch(d){ij(new sk("Transport failed to deserialize "+String(a[c])))}return b}
function Rp(a,b){if(C("yt.logging.transport.enableScrapingForTest")){var c=C("yt.logging.transport.scrapedPayloadsForTesting"),d=C("yt.logging.transport.payloadToScrape");b&&(b=C("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);if(d&&1<=d.length)for(b=0;b<d.length;b++)if(a&&a.payload[d[b]]){var e=void 0;c.push((null==(e=a)?void 0:e.payload)[d[b]])}D("yt.logging.transport.scrapedPayloadsForTesting",c)}}
function rq(){return T("use_request_time_ms_header")||T("lr_use_request_time_ms_header")}
function cq(a,b){return T("transport_use_scheduler")?T("logging_avoid_blocking_during_navigation")||T("lr_logging_avoid_blocking_during_navigation")?wk(function(){if("none"===vp().j)a();else{var c={};vp().install((c.none={nb:a},c))}},b):wk(a,b):uj(a,b)}
function gq(a){T("transport_use_scheduler")?hf.ba(a):window.clearTimeout(a)}
function mq(a){var b,c,d,e,f,g,h,k,l,m;return A(function(n){if(1==n.g){d=null==(b=a)?void 0:null==(c=b.responseContext)?void 0:c.globalConfigGroup;var r=d?d[vi.name]:void 0;e=r;g=null==(f=d)?void 0:f.hotHashData;r=d?d[ui.name]:void 0;h=r;l=null==(k=d)?void 0:k.coldHashData;return(m=dp().resolve(new Zo))?g?e?z(n,vn(m,g,e),2):z(n,vn(m,g),2):n.B(2):n.return()}return l?h?z(n,wn(m,l,h),0):z(n,wn(m,l),0):n.B(0)})}
function bq(a,b){b=void 0===b?200:b;return a?300===b?Jp:Hp:300===b?Ip:Gp}
function Up(a){if(T("enable_web_tiered_gel")){a=uo[a||""];var b,c;if(null==dp().resolve(new Zo))var d=void 0;else{var e=null!=(d=C("yt.gcf.config.hotConfigGroup"))?d:null;d=null==e?void 0:null==(b=e.loggingHotConfig)?void 0:null==(c=b.eventLoggingConfig)?void 0:c.payloadPolicies}if(b=d)for(c=0;c<b.length;c++)if(b[c].payloadNumber===a)return b[c]}}
function Tp(a){a=Object.keys(a);a=u(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,uo[b])return b}
function Vp(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
function Yp(a){return"gelDebuggingEvent"===a}
function iq(a){return(void 0===a?0:a)&&T("vss_through_gel_video_stats")?"video_stats":"log_event"}
;var tq=B.ytLoggingGelSequenceIdObj_||{};D("ytLoggingGelSequenceIdObj_",tq);
function uq(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||Y());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=To();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!T("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,b={index:vq(b),groupKey:b},a.sequence=b,d.endOfSequence&&delete tq[d.sequenceGroup]);(d.sendIsolatedPayload?Wp:Qp)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
function wq(a){aq(void 0,void 0,void 0===a?!1:a)}
function vq(a){tq[a]=a in tq?tq[a]+1:0;return tq[a]}
;var xq=[];function yq(a,b,c){c=void 0===c?{}:c;var d=So;S("ytLoggingEventsDefaultDisabled",!1)&&So===So&&(d=null);T("web_all_payloads_via_jspb")?(c.timestamp||(c.lact=To(),c.timestamp=Y()),xq.push({Ec:a,payload:b,options:c})):uq(a,b,d,c)}
;var zq=B.ytLoggingGelSequenceIdObj_||{};D("ytLoggingGelSequenceIdObj_",zq);function Aq(a,b){var c=void 0;c=void 0===c?{}:c;var d=!1;S("ytLoggingEventsDefaultDisabled",!1)&&(d=!0);d=d?null:So;c=void 0===c?{}:c;var e=Math.round(c.timestamp||Y());Jd(b,1,e<Number.MAX_SAFE_INTEGER?e:0);e=new Ti;if(c.lact)Jd(e,1,isFinite(c.lact)?c.lact:-1);else if(c.timestamp)Jd(e,1,-1);else{var f=To();Jd(e,1,isFinite(f)?f:-1)}if(c.sequenceGroup&&!T("web_gel_sequence_info_killswitch")){f=c.sequenceGroup;var g=vq(f),h=new Si;Jd(h,2,g);J(h,1,f);I(e,Si,3,h);c.endOfSequence&&delete zq[c.sequenceGroup]}I(b,
Ti,33,e);(c.sendIsolatedPayload?$p:Zp)(a,{endpoint:"log_event",payload:b,cttAuthInfo:c.cttAuthInfo,dangerousLogToVisitorSession:c.dangerousLogToVisitorSession},d)}
;var Bq=new Set,Cq=0,Dq=0,Eq=0,Fq=[],Gq=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Hq(a){try{Bq.add(a.message)}catch(b){}Cq++}
function Iq(){for(var a=u(Gq),b=a.next();!b.done;b=a.next()){var c=Hb();if(c&&0<=c.toLowerCase().indexOf(b.value.toLowerCase()))return!0}return!1}
function Jq(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:S("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=u(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=S("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=u(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=S("SERVER_NAME");b=S("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}Pj(S("ECATCHER_REPORT_HOST","")+"/error_204",a)}
;function Kq(){var a;return A(function(b){return(a=Bf())?b.return(a.then(function(c){c=Md(c);for(var d=[],e=0,f=0;f<c.length;f++){var g=c.charCodeAt(f);255<g&&(d[e++]=g&255,g>>=8);d[e++]=g}return Cc(d,3)})):b.return(Promise.resolve(null))})}
;var Lq={};function Mq(a){return Lq[a]||(Lq[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Nq={},Oq=[],yg=new L,Pq={};function Qq(){for(var a=u(Oq),b=a.next();!b.done;b=a.next())b=b.value,b()}
function Rq(a,b){var c;"yt:"===a.tagName.toLowerCase().substr(0,3)?c=a.getAttribute(b):c=a?a.dataset?a.dataset[Mq(b)]:a.getAttribute("data-"+b):null;return c}
function Sq(a){yg.fb.apply(yg,arguments)}
;function Tq(a){this.g=a||{};a=[this.g,window.YTConfig||{}];for(var b=0;b<a.length;b++)a[b].host&&(a[b].host=a[b].host.toString().replace("http://","https://"))}
function Uq(a,b){a=[a.g,window.YTConfig||{}];for(var c=0;c<a.length;c++){var d=a[c][b];if(void 0!==d)return d}return null}
function Vq(a,b,c){Wq||(Wq={},Xq=new Set,tj(window,"message",function(d){a:if(Xq.has(d.origin)){try{var e=JSON.parse(d.data)}catch(g){break a}var f=Wq[e.id];f&&d.origin===f.Wc&&(d=f.Hd,d.H=!0,d.H&&(bb(d.u,d.sendMessage,d),d.u.length=0),d.jc(e))}}));
a=String(Uq(a,"host"));Wq[c]={Hd:b,Wc:a};Xq.add(a)}
var Wq=null,Xq=null;var Yq=window;
function Zq(a,b,c){this.o=this.g=this.h=null;this.i=0;this.H=!1;this.u=[];this.j=null;this.S={};if(!a)throw Error("YouTube player element ID required.");this.id=Na(this);this.M=c;c=document;if(a="string"===typeof a?c.getElementById(a):a)if(c="iframe"===a.tagName.toLowerCase(),b.host||(b.host=c?Yb(a.src):"https://www.youtube.com"),this.h=new Tq(b),c||(b=$q(this,a),this.o=a,(c=a.parentNode)&&c.replaceChild(b,a),a=b),this.g=a,this.g.id||(this.g.id="widget"+Na(this.g)),Nq[this.g.id]=this,window.postMessage){this.j=
new L;ar(this);b=Uq(this.h,"events");for(var d in b)b.hasOwnProperty(d)&&this.addEventListener(d,b[d]);for(var e in Pq)Pq.hasOwnProperty(e)&&br(this,e)}}
q=Zq.prototype;q.setSize=function(a,b){this.g.width=a.toString();this.g.height=b.toString();return this};
q.getIframe=function(){return this.g};
q.jc=function(a){cr(this,a.event,a)};
q.addEventListener=function(a,b){var c=b;"string"===typeof b&&(c=function(){window[b].apply(window,arguments)});
if(!c)return this;this.j.subscribe(a,c);dr(this,a);return this};
function br(a,b){b=b.split(".");if(2===b.length){var c=b[1];a.M===b[0]&&dr(a,c)}}
q.destroy=function(){this.g&&this.g.id&&(Nq[this.g.id]=null);xe(this.j);if(this.o){var a=this.g,b=a.parentNode;b&&b.replaceChild(this.o,a)}else(a=this.g)&&a.parentNode&&a.parentNode.removeChild(a);Wq&&(Wq[this.id]=null);this.h=null;a=this.g;for(var c in kb)kb[c][0]==a&&rj(c);this.o=this.g=null};
q.nc=function(){return{}};
function er(a,b,c){c=c||[];c=Array.prototype.slice.call(c);b={event:"command",func:b,args:c};a.H?a.sendMessage(b):a.u.push(b)}
function cr(a,b,c){a.j.Ka||(c={target:a,data:c},a.j.fb(b,c),Sq(a.M+"."+b,c))}
function $q(a,b){var c=document.createElement("iframe");b=b.attributes;for(var d=0,e=b.length;d<e;d++){var f=b[d].value;null!=f&&""!==f&&"null"!==f&&c.setAttribute(b[d].name,f)}c.setAttribute("frameBorder","0");c.setAttribute("allowfullscreen","1");c.setAttribute("allow","accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share");c.setAttribute("title","YouTube "+Uq(a.h,"title"));(b=Uq(a.h,"width"))&&c.setAttribute("width",b.toString());(b=Uq(a.h,"height"))&&
c.setAttribute("height",b.toString());Yq.yt_embedsEnableIframeWithLazyLoad&&c.setAttribute("loading","lazy");var g=a.nc();g.enablejsapi=window.postMessage?1:0;window.location.host&&(g.origin=window.location.protocol+"//"+window.location.host);g.widgetid=a.id;window.location.href&&bb(["debugjs","debugcss"],function(k){var l=bc(window.location.href,k);null!==l&&(g[k]=l)});
var h=""+Uq(a.h,"host")+("/embed/"+Uq(a.h,"videoId"))+"?"+$b(g);Yq.yt_embedsEnableUaChProbe?Kq().then(function(k){var l=new URL(h),m=Number(l.searchParams.get("reloads"));isNaN(m)&&(m=0);l.searchParams.set("reloads",(m+1).toString());k&&l.searchParams.set("uach",k);l.searchParams.set("uats",Math.floor(window.performance.timeOrigin).toString());k=be(l.href).toString();Yd(c,ce(k));c.sandbox.add("allow-presentation","allow-top-navigation");return k}):Yq.yt_embedsEnableIframeSrcWithIntent?(Yd(c,ce(h)),
c.sandbox.add("allow-presentation","allow-top-navigation")):c.src=h;
return c}
q.Fc=function(){this.g&&this.g.contentWindow?this.sendMessage({event:"listening"}):window.clearInterval(this.i)};
function ar(a){Vq(a.h,a,a.id);a.i=vj(a.Fc.bind(a));tj(a.g,"load",function(){window.clearInterval(a.i);a.i=vj(a.Fc.bind(a))})}
function dr(a,b){a.S[b]||(a.S[b]=!0,er(a,"addEventListener",[b]))}
q.sendMessage=function(a){a.id=this.id;a.channel="widget";var b=JSON.stringify(a),c=[Yb(this.g.src||"").replace("http:","https:")];if(this.g.contentWindow)for(var d=0;d<c.length;d++)try{this.g.contentWindow.postMessage(b,c[d])}catch(sc){if(sc.name&&"SyntaxError"===sc.name){if(!(sc.message&&0<sc.message.indexOf("target origin ''"))){var e=void 0,f=sc;e=void 0===e?{}:e;e.name=S("INNERTUBE_CONTEXT_CLIENT_NAME",1);e.version=S("INNERTUBE_CONTEXT_CLIENT_VERSION");var g="WARNING",h=!1;g=void 0===g?"ERROR":
g;h=void 0===h?!1:h;if(f){f.hasOwnProperty("level")&&f.level&&(g=f.level);if(T("console_log_js_exceptions")){var k=f,l=[];l.push("Name: "+k.name);l.push("Message: "+k.message);k.hasOwnProperty("params")&&l.push("Error Params: "+JSON.stringify(k.params));k.hasOwnProperty("args")&&l.push("Error args: "+JSON.stringify(k.args));l.push("File name: "+k.fileName);l.push("Stacktrace: "+k.stack);window.console.log(l.join("\n"),k)}if(!(5<=Cq)){var m=void 0,n=void 0,r=f,p=e,x=Rd(r),y=x.message||"Unknown Error",
F=x.name||"UnknownError",O=x.stack||r.h||"Not available";if(O.startsWith(F+": "+y)){var U=O.split("\n");U.shift();O=U.join("\n")}var Q=x.lineNumber||"Not available",Fa=x.fileName||"Not available",Uc=O,Ra=0;if(r.hasOwnProperty("args")&&r.args&&r.args.length)for(var Ga=0;Ga<r.args.length&&!(Ra=hk(r.args[Ga],"params."+Ga,p,Ra),500<=Ra);Ga++);else if(r.hasOwnProperty("params")&&r.params){var da=r.params;if("object"===typeof r.params)for(n in da){if(da[n]){var ma="params."+n,na=jk(da[n]);p[ma]=na;Ra+=
ma.length+na.length;if(500<Ra)break}}else p.params=jk(da)}if(Fq.length)for(var ca=0;ca<Fq.length&&!(Ra=hk(Fq[ca],"params.context."+ca,p,Ra),500<=Ra);ca++);navigator.vendor&&!p.hasOwnProperty("vendor")&&(p["device.vendor"]=navigator.vendor);var W={message:y,name:F,lineNumber:Q,fileName:Fa,stack:Uc,params:p,sampleWeight:1},lm=Number(r.columnNumber);isNaN(lm)||(W.lineNumber=W.lineNumber+":"+lm);if("IGNORED"===r.level)m=0;else a:{for(var mm=dk(),nm=u(mm.Da),uh=nm.next();!uh.done;uh=nm.next()){var om=
uh.value;if(W.message&&W.message.match(om.qe)){m=om.weight;break a}}for(var pm=u(mm.Aa),vh=pm.next();!vh.done;vh=pm.next()){var qm=vh.value;if(qm.nb(W)){m=qm.weight;break a}}m=1}W.sampleWeight=m;for(var rm=u(Yj),wh=rm.next();!wh.done;wh=rm.next()){var xh=wh.value;if(xh.Kb[W.name])for(var sm=u(xh.Kb[W.name]),yh=sm.next();!yh.done;yh=sm.next()){var tm=yh.value,Fe=W.message.match(tm.regexp);if(Fe){W.params["params.error.original"]=Fe[0];for(var zh=tm.groups,um={},tc=0;tc<zh.length;tc++)um[zh[tc]]=Fe[tc+
1],W.params["params.error."+zh[tc]]=Fe[tc+1];W.message=xh.Yb(um);break}}}W.params||(W.params={});var vm=dk();W.params["params.errorServiceSignature"]="msg="+vm.Da.length+"&cb="+vm.Aa.length;W.params["params.serviceWorker"]="false";B.document&&B.document.querySelectorAll&&(W.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));rb("sample").constructor!==qb&&(W.params["params.fconst"]="true");var kd=W;window.yterr&&"function"===typeof window.yterr&&window.yterr(kd);
if(0!==kd.sampleWeight&&!Bq.has(kd.message))if(h&&T("web_enable_error_204")){var wm=kd;Jq(void 0===g?"ERROR":g,wm);Hq(wm)}else{var Ah=void 0,Bh=void 0,xm=void 0,ym=void 0,Ch=void 0,M=kd,Mb=g;Mb=void 0===Mb?"ERROR":Mb;if("ERROR"===Mb){ek.fb("handleError",M);if(T("record_app_crashed_web")&&0===Eq&&1===M.sampleWeight)if(Eq++,T("errors_via_jspb")){var kr=new Ri;Ch=Kd(kr,1,1);if(!T("report_client_error_with_app_crash_ks")){var lr=new Qi,mr=new Pi,nr=new Oi,or=new Ni;var pr=J(or,1,M.message);var qr=I(nr,
Ni,3,pr);ym=I(mr,Oi,5,qr);xm=I(lr,Pi,9,ym);I(Ch,Qi,4,xm)}var zm=T("jspb_sparse_encoded_pivot")?new Ui([{}]):new Ui;Dd(zm,Ri,20,Vi,Ch);Aq("appCrashed",zm)}else{var Am={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};T("report_client_error_with_app_crash_ks")||(Am.systemHealth={crashData:{clientError:{logMessage:{message:M.message}}}});yq("appCrashed",Am)}Dq++}else"WARNING"===Mb&&ek.fb("handleWarning",M);if(T("kevlar_gel_error_routing"))a:{var ld=Mb;if(T("errors_via_jspb")){if(Iq())Bh=void 0;else{var uc=new Ki;
J(uc,1,M.stack);M.fileName&&J(uc,4,M.fileName);var db=M.lineNumber&&M.lineNumber.split?M.lineNumber.split(":"):[];0!==db.length&&(1!==db.length||isNaN(Number(db[0]))?2!==db.length||isNaN(Number(db[0]))||isNaN(Number(db[1]))||(Id(uc,2,Number(db[0])),Id(uc,3,Number(db[1]))):Id(uc,2,Number(db[0])));var Nb=new Ni;J(Nb,1,M.message);J(Nb,3,M.name);Id(Nb,6,M.sampleWeight);"ERROR"===ld?Kd(Nb,2,2):"WARNING"===ld?Kd(Nb,2,1):Kd(Nb,2,0);var Dh=new Li;wd(Dh,1,Zc(!0));Dd(Dh,Ki,3,Mi,uc);var Ob=new Ji;J(Ob,3,window.location.href);
for(var Bm=S("FEXP_EXPERIMENTS",[]),Eh=0;Eh<Bm.length;Eh++){var rr=bd(Bm[Eh]),Cm=Ob.s,sr=rr,Dm=Lc(Cm);Xc(Dm);yd(Cm,Dm,5,2).push(sr)}var Fh=dj();if(!ej()&&Fh)for(var Em=u(Object.keys(Fh)),Pb=Em.next();!Pb.done;Pb=Em.next()){var Fm=Pb.value,Gh=new Ii;J(Gh,1,Fm);J(Gh,2,String(Fh[Fm]));Ed(Ob,4,Ii,Gh)}var Hh=M.params;if(Hh){var Gm=u(Object.keys(Hh));for(Pb=Gm.next();!Pb.done;Pb=Gm.next()){var Hm=Pb.value,Ih=new Ii;J(Ih,1,"client."+Hm);J(Ih,2,String(Hh[Hm]));Ed(Ob,4,Ii,Ih)}}var Im=S("SERVER_NAME"),Jm=S("SERVER_VERSION");
if(Im&&Jm){var Jh=new Ii;J(Jh,1,"server.name");J(Jh,2,Im);Ed(Ob,4,Ii,Jh);var Kh=new Ii;J(Kh,1,"server.version");J(Kh,2,Jm);Ed(Ob,4,Ii,Kh)}var Ge=new Oi;I(Ge,Ji,1,Ob);I(Ge,Li,2,Dh);I(Ge,Ni,3,Nb);Bh=Ge}var Km=Bh;if(!Km)break a;var Lm=T("jspb_sparse_encoded_pivot")?new Ui([{}]):new Ui;Dd(Lm,Oi,163,Vi,Km);Aq("clientError",Lm)}else{var Ja=void 0;Ja=void 0===Ja?{}:Ja;if(Iq())Ah=void 0;else{var md={stackTrace:M.stack};M.fileName&&(md.filename=M.fileName);var eb=M.lineNumber&&M.lineNumber.split?M.lineNumber.split(":"):
[];0!==eb.length&&(1!==eb.length||isNaN(Number(eb[0]))?2!==eb.length||isNaN(Number(eb[0]))||isNaN(Number(eb[1]))||(md.lineNumber=Number(eb[0]),md.columnNumber=Number(eb[1])):md.lineNumber=Number(eb[0]));var Lh={level:"ERROR_LEVEL_UNKNOWN",message:M.message,errorClassName:M.name,sampleWeight:M.sampleWeight};"ERROR"===ld?Lh.level="ERROR_LEVEL_ERROR":"WARNING"===ld&&(Lh.level="ERROR_LEVEL_WARNNING");var tr={isObfuscated:!0,browserStackInfo:md};Ja.pageUrl=window.location.href;Ja.kvPairs=[];S("FEXP_EXPERIMENTS")&&
(Ja.experimentIds=S("FEXP_EXPERIMENTS"));var Mh=dj();if(!ej()&&Mh)for(var Mm=u(Object.keys(Mh)),Qb=Mm.next();!Qb.done;Qb=Mm.next()){var Nm=Qb.value;Ja.kvPairs.push({key:Nm,value:String(Mh[Nm])})}var Nh=M.params;if(Nh){var Om=u(Object.keys(Nh));for(Qb=Om.next();!Qb.done;Qb=Om.next()){var Pm=Qb.value;Ja.kvPairs.push({key:"client."+Pm,value:String(Nh[Pm])})}}var Qm=S("SERVER_NAME"),Rm=S("SERVER_VERSION");Qm&&Rm&&(Ja.kvPairs.push({key:"server.name",value:Qm}),Ja.kvPairs.push({key:"server.version",value:Rm}));
Ah={errorMetadata:Ja,stackTrace:tr,logMessage:Lh}}var Sm=Ah;if(!Sm)break a;yq("clientError",Sm)}if("ERROR"===ld||T("errors_flush_gel_always_killswitch"))b:{if(T("web_fp_via_jspb")){var He=!0;He=void 0===He?!1:He;var Tm=xq;xq=[];if(Tm)for(var Um=u(Tm),Oh=Um.next();!Oh.done;Oh=Um.next()){var vc=Oh.value;He?uq(vc.Ec,vc.payload,So,vc.options):yq(vc.Ec,vc.payload,vc.options)}wq(!0);if(!T("web_fp_via_jspb_and_json"))break b}wq()}}T("suppress_error_204_logging")||Jq(Mb,M);Hq(M)}}}}}else throw sc;}else console&&
console.warn&&console.warn("The YouTube player is not attached to the DOM. API calls should be made after the onReady event. See more: https://developers.google.com/youtube/iframe_api_reference#Events")};function fr(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function gr(a){return 0===a.search("get")||0===a.search("is")}
;function hr(a,b){Zq.call(this,a,Object.assign({title:"video player",videoId:"",width:640,height:360},b||{}),"player");this.ka={};this.playerInfo={};this.videoTitle=""}
w(hr,Zq);q=hr.prototype;q.nc=function(){var a=Uq(this.h,"playerVars");if(a){var b={},c;for(c in a)b[c]=a[c];a=b}else a={};window!==window.top&&document.referrer&&(a.widget_referrer=document.referrer.substring(0,256));if(c=Uq(this.h,"embedConfig")){if(Ma(c))try{c=JSON.stringify(c)}catch(d){console.error("Invalid embed config JSON",d)}a.embed_config=c}return a};
q.jc=function(a){var b=a.event;a=a.info;switch(b){case "apiInfoDelivery":if(Ma(a))for(var c in a)a.hasOwnProperty(c)&&(this.ka[c]=a[c]);break;case "infoDelivery":ir(this,a);break;case "initialDelivery":Ma(a)&&(window.clearInterval(this.i),this.playerInfo={},this.ka={},jr(this,a.apiInterface),ir(this,a));break;default:cr(this,b,a)}};
function ir(a,b){if(Ma(b)){for(var c in b)b.hasOwnProperty(c)&&(a.playerInfo[c]=b[c]);a.playerInfo.hasOwnProperty("videoData")&&(b=a.playerInfo.videoData,b.hasOwnProperty("title")&&b.title?(b=b.title,b!==a.videoTitle&&(a.videoTitle=b,a.g.setAttribute("title",b))):(a.videoTitle="",a.g.setAttribute("title","YouTube "+Uq(a.h,"title"))))}}
function jr(a,b){bb(b,function(c){this[c]||("getCurrentTime"===c?this[c]=function(){var d=this.playerInfo.currentTime;if(1===this.playerInfo.playerState){var e=(Date.now()/1E3-this.playerInfo.currentTimeLastUpdated_)*this.playerInfo.playbackRate;0<e&&(d+=Math.min(e,1))}return d}:fr(c)?this[c]=function(){this.playerInfo={};
this.ka={};er(this,c,arguments);return this}:gr(c)?this[c]=function(){var d=0;
0===c.search("get")?d=3:0===c.search("is")&&(d=2);return this.playerInfo[c.charAt(d).toLowerCase()+c.substr(d+1)]}:this[c]=function(){er(this,c,arguments);
return this})},a)}
q.getVideoEmbedCode=function(){var a=Uq(this.h,"host")+("/embed/"+Uq(this.h,"videoId")),b=Number(Uq(this.h,"width")),c=Number(Uq(this.h,"height"));if(isNaN(b)||isNaN(c))throw Error("Invalid width or height property");b=Math.floor(b);c=Math.floor(c);var d=this.videoTitle;a=Ub(a);d=Ub(null!=d?d:"YouTube video player");return'<iframe width="'+b+'" height="'+c+'" src="'+a+'" title="'+(d+'" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>')};
q.getOptions=function(a){return this.ka.namespaces?a?this.ka[a]?this.ka[a].options||[]:[]:this.ka.namespaces||[]:[]};
q.getOption=function(a,b){if(this.ka.namespaces&&a&&b&&this.ka[a])return this.ka[a][b]};
function ur(a){if("iframe"!==a.tagName.toLowerCase()){var b=Rq(a,"videoid");b&&(b={videoId:b,width:Rq(a,"width"),height:Rq(a,"height")},new hr(a,b))}}
;D("YT.PlayerState.UNSTARTED",-1);D("YT.PlayerState.ENDED",0);D("YT.PlayerState.PLAYING",1);D("YT.PlayerState.PAUSED",2);D("YT.PlayerState.BUFFERING",3);D("YT.PlayerState.CUED",5);D("YT.get",function(a){return Nq[a]});
D("YT.scan",Qq);D("YT.subscribe",function(a,b,c){yg.subscribe(a,b,c);Pq[a]=!0;for(var d in Nq)Nq.hasOwnProperty(d)&&br(Nq[d],a)});
D("YT.unsubscribe",function(a,b,c){xg(a,b,c)});
D("YT.Player",hr);Zq.prototype.destroy=Zq.prototype.destroy;Zq.prototype.setSize=Zq.prototype.setSize;Zq.prototype.getIframe=Zq.prototype.getIframe;Zq.prototype.addEventListener=Zq.prototype.addEventListener;hr.prototype.getVideoEmbedCode=hr.prototype.getVideoEmbedCode;hr.prototype.getOptions=hr.prototype.getOptions;hr.prototype.getOption=hr.prototype.getOption;
Oq.push(function(a){var b=a;b||(b=document);a=gb(b.getElementsByTagName("yt:player"));var c=b||document;if(c.querySelectorAll&&c.querySelector)b=c.querySelectorAll(".yt-player");else{var d;c=document;b=b||c;if(b.querySelectorAll&&b.querySelector)b=b.querySelectorAll(".yt-player");else if(b.getElementsByClassName){var e=b.getElementsByClassName("yt-player");b=e}else{e=b.getElementsByTagName("*");var f={};for(c=d=0;b=e[c];c++){var g=b.className,h;if(h="function"==typeof g.split)h=0<=ab(g.split(/\s+/),
"yt-player");h&&(f[d++]=b)}f.length=d;b=f}}b=gb(b);bb(fb(a,b),ur)});
"undefined"!=typeof YTConfig&&YTConfig.parsetags&&"onload"!=YTConfig.parsetags||Qq();var vr=B.onYTReady;vr&&vr();var wr=B.onYouTubeIframeAPIReady;wr&&wr();var xr=B.onYouTubePlayerAPIReady;xr&&xr();}).call(this);
