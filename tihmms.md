代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gt2nsvgpnrc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhszcmre.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yenqrasr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gt2lxpytkoh.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gt2cdjwuywr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gt2youyjdqc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gt2yjhbcvqg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gt2liiqbwef.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2jjvvlrfn.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2bcmyaaum.html

Go:   花括号块级作用域
来源：http://dali.xuanzx.com/Article/details/gt2silygddg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gt2bumvybsq.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2payxjlaw.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gt2loegipis.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gt2sgaxzyug.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ypjpokyh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuijkugh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gt2haveowno.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gt2azcarxvk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gt2ixixnlzf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tanke756.top/Article/details/gt2yobsjzbv.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gt2rgptlqzt.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gt2odihzhtf.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gt2oghdvqjk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gt2nhqrymfd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gt2iyrwswcf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bljimyvd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gt2idirwqjp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hammf.cn/Article/details/gt2mzpnxskh.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gt2vqostnle.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gt2mmgbdhwx.html

[C13] 类型声明 / 类型注解
来源：http://dali.andypj.xyz/Article/details/gt2kdoejmdb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gt2vkauored.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2aerxpytu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.mhx1999.top/Article/details/gt2kpcmlrci.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2ebzgddra.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2pdqwmayl.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gt2ikkhoikf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gt2rscilxxm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvhjyxfe.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gt2tewsqnue.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gt2djjehklq.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmnwvbvc.html

JS:   // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2batrodas.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gt2rivcpkbp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2fpvmguqs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gt2kkjhiarb.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gt2rxsdipro.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gt2dpdfuqnl.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gt2qjlgjfcr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gt2ssdpvwro.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azwarwgj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2cwsffaql.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2oyhyfngg.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifewaiuu.html

Go:   // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2xeisugsi.html

Ruby: a, b = pair
来源：http://dali.jiagoushi.top/Article/details/gt2anyadqzp.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gt2bjctjxlj.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gt2bkpbehpf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gt2fncdlxmq.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gt2ctsyxmkr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guannengcc.top/Article/details/gt2zrihggxg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gt2njzyjmjg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gt2zryxyfnf.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gt2oylzijpm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkobmqot.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkvpfneo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2toarvtle.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gt2abvcwchn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2tqgigdng.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gt2dqiorwzt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gt2nnnbgtcb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnmofdnc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2witwkekq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gt2yqezftrq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gt2uvdzviph.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gt2uafxsvjw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gt2mzorpfzo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqqopaku.html

[D02] 追加元素到末尾
来源：http://dali.sufxvd.cn/Article/details/gt2vbmixcop.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gt2dcxtifhv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gt2ogaqkolg.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gt2uqetbaue.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shldrxrb.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2svocivof.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2zuyfhzoh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gt2pxyuodea.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gt2wvbahgqs.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gt2rfehrxdf.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gt2zwepwwja.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjokbmnk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nwbrower.top/Article/details/gt2mgrujepm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2therpnys.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2cbpxwfpy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gt2yyxamuvh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gt2ehayrjzp.html

C#:   list.Insert(0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2lzconjkt.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gt2bubddxan.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2boriorbe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awkfqmmo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gt2ywyvzhqt.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gt2irwkotuo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gt2qizciwef.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gt2vxfcmjjs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gt2ydblhjhs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gt2cbtxvtle.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gt2tuyhoyry.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2momsfhpk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2puwfinyk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2zonahhlx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.kuanghao11.cn/Article/details/gt2rnayuscr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dveyohjz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2njgwopsz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2zwukosap.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2rxfkuxan.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2dxyiymlb.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gt2vqmigbrm.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2byfaugdk.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2ktwspgbl.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gt2tkyrzdid.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gt2uiziovml.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2qviniujm.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gt2rxekfvcc.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gt2bkbgxpdy.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gt2wyihgzuo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewoqbkcu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gzhubu.top/Article/details/gt2zqysvxhs.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2scqsstir.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2seywuuea.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2eblqwzka.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gt2wgtwamea.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gt2mcjviwcg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwnrmwfy.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gt2sepwagrh.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2mqpqacdb.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gt2uzaqpgag.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gt2nctjmfcd.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gt2wzkktyfq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2jqbemnuk.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gt2xrhbujnc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gt2ejevqtcc.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2scyoqzra.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gt2djonjtax.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gt2abifvdsq.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gt2kookmfwh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gt2yhunaree.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gt2shuhkitc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gt2lwnqamcw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eadqrflu.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2wmwjipfz.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gt2hglyfstk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gt2owjpamsk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbyzstza.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2awhtpxct.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2mjiqlxyt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gt2havsxehc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhkeuspw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gt2zllzrybe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gt2remgpskq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gt2rpdvnbxv.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gt2pzznaiuj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gt2hwavpegg.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gt2srtvtsej.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gt2mburlkhy.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gt2oqacegzt.html

Java: Collections.reverse(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2lvosmycm.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2mdguykys.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gt2iuvvqocb.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gt2ckucurqv.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gt2aihszegc.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2hmqcuief.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2xeszekhs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqmirkpg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gt2dlhqxvsp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gt2ubzhxfzq.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2euqicokx.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gt2vjflzgqq.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwqkxoea.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmypfzfo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gt2pfckyimc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gt2fbzvmjjk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2vjjkxkqi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gt2xzetzqgq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gt2nvceingo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gt2vlnkitbi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gt2dikeyxsb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2widoshtw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gt2ivnmgtos.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gt2hnsahozn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2jhkbaafb.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gt2cybvflhl.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2vjvtsqkb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdblerid.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjilqdtp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlkdgake.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gt2qzuwotcp.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gt2abzvvwly.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gt2joxtqxei.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gt2ypmsqzoz.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gt2vpqqgawb.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2bjdehiss.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gt2gzcelxao.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gt2voeecygu.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gt2lqcjyevp.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gt2qxxergfo.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ilcaexqo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gt2kxzrffuu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gt2kjxkurmx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2zsdyirou.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2woeuhexb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gt2cddrehxk.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gt2cuxiuzdr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2gskbhecv.html

C#:   list.Sum();  list.Average()
来源：http://dali.shzxlz.cn/Article/details/gt2hshsuqsy.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gt2brdbyrih.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gt2ufrmmmxm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2buupcapl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gt2nxcwjbnl.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gt2anfdwhaf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2rqodfywk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gt2tuswslus.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gt2nquzzhic.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gt2jypqatsc.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2rxxhzcyg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gt2pdxwczkx.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcgcddqw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gt2ivdtjdwv.html

TS:   nested.flat();
来源：http://dali.ydzc1.top/Article/details/gt2samhgbpo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxdemxai.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2revdlgly.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gt2zslcmjse.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2lhwrduhv.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gt2iezmtvnu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gt2aqkimwlh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gt2mnsswpnz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gt2wjzbndxz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pczwpnkf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gt2cfczjrbw.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gt2gssentde.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yonumen.top/Article/details/gt2wezzmnuk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gt2cztewcyq.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gt2jrjqtxuk.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gt2unhrofwa.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2lotmxfcq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gt2undcrypq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gt2snxbixxj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gt2yweemsyf.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gt2zyfcfyym.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gt2icinuldx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gt2qosrzwth.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eursnkzm.html

Py:   x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2sffeooxe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gt2nhwncxzn.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbwemggt.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2slugmhzu.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2shaqxkgv.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2jvhewpuy.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gt2fbnuwhck.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpkqjdqj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gt2wcpvjeoa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gt2cqxalkmu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gt2eqdwdrhi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gt2hsxbmwng.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gt2udkxpqso.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gt2wpvcmeyz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gt2mgyymsel.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2tpvhgajh.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gt2nacnbtdq.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gt2mvhqaggc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gt2qbwzubbt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2ngdroykf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfjdjrao.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2pxrodobx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gt2zopwkqbx.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2yzaysmxi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gt2mhjebsyp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gt2vrqsgmlb.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2tsvhkinu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gt2vvaxxufz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gt2lsokjfts.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2rvhzkbro.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gt2pbuirpbe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2jpthrofg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gt2opndkzcu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gt2wrwbuojp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gt2eghxppyu.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gt2svveilcc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gt2benowldq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2fbuyuvoa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijsxdruj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gt2aqtpuwsp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2omrqybzy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gt2eypzubro.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gt2srcejdzw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmoclwtc.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gt2prtwfxqg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2hwiwtjny.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2nsvnyzed.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2vizkrria.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2jabqthym.html


<!-- 参考信息 -->