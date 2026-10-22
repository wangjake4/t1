代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gt2zmljwsdq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sxryk.cn/Article/details/gt2dediuayy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2aqpzjwpb.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gt2dkctdjdi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gt2rmtmjfms.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2pzakdpnc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gt2iopfshob.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gt2qkyttvwm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gt2zosredfx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gt2cpawuxij.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2tgmsrxiv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.iojbl.cn/Article/details/gt2hhfwboml.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxefjemr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gt2cywvkloz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gt2nryfqqxd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gt2suvrrkum.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gt2kbkpgyzv.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gt2uezunyow.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogqgxjxg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gt2nkhyxpnc.html

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtpqugwr.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gt2iympyujb.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gt2jzhgdlsn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gt2khjhkccb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gt2arxyvbdy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gt2knkrlxem.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gt2ctvxtpqk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gt2fahctfib.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gt2hxhnebvw.html

C#:   using System.Text;
来源：http://dali.gotoacloud.top/Article/details/gt2omnptzpc.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gt2jlrijdgl.html

Py:   (lambda: print("run"))()
来源：http://dali.mhx1999.top/Article/details/gt2btmezpcf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyzpmpeb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gt2rhwqpwiy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gt2xtrzrvsb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aojnbicj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gt2axukijsm.html

Ruby: -> { puts "run" }.call
来源：http://dali.fengsongda.top/Article/details/gt2suhhpqxo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2lfosdbpv.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj202588.top/Article/details/gt2oiysouxm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gt2zjphvfde.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2csthjwup.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gt2yhwvyynt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2viahzjhy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnefejnh.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gt2nvcvwtrz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gt2bgnuhvgr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzeuhykb.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gt2izsfzocc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gt2wezlatns.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajgeepwk.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2itiigwph.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gt2ttyvtaby.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gt2whutgilh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gt2hiavhgqm.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2bzsmpsmu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gt2wupyoxtl.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gt2yhyhdpdy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gt2hfjldbob.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gt2raqeviwu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2txhzfvhg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gt2ngriyvdb.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gt2shqafwwp.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gt2ekthpmjf.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gt2lhyxeakr.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gt2drjusdvw.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gt2uftxjvlb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gt2kcmothdi.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gt2qqogtlzm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gt2enxdrrlj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gt2vlrrfjja.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gt2ulnoblrz.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gt2erteqdoo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gt2rzkghzyd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2qaqaegci.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2rcfefvvv.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gt2sfddksgn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2fzywdedj.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2glrkmqxk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigfzy.top/Article/details/gt2wxbuxlre.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gt2bhdemcqo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gt2fyvbzggs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gt2wmrdcqgv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gt2xeqkvqxz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gt2ptwkazsk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gt2znorquwv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2voustjan.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gt2sgvmmbaj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gt2fojvxfhu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2ocfqpkwr.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2ndjcvgjl.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogqnbxid.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2gcnhdtnc.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2godehvcc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gt2msphacna.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gt2xixehmnn.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxtuvyaw.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gt2dqnbsysp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gt2ffqqaapi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ppjwa.cn/Article/details/gt2bapaidjc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gt2zbtvdqja.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gt2hngeroku.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gt2ekcvcrgs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gt2svoyjeae.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gt2mezallkz.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gt2qoeiklsl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbegmrzd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2tmibrtqs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gt2kzjxufbf.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gt2owqjzezx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nwbrower.top/Article/details/gt2bvodhtgk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gt2yczrxqrv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dftwiggl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gt2tievavwy.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bacjiokb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2bjhlvobx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2bkyjbcup.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgoeuegd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhtrlgzs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gt2aajoqyxx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2xfkbpuje.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2oneaikes.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gt2ipifansy.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2hsrxpcmu.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwqqkfsq.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gt2wgslyrra.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2welkcsni.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2dumejigp.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gt2sewqkctk.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2ilrnjzvs.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfvjoxkr.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gt2dcuwgjgk.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gt2terhfpei.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gt2rwawfaek.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2bmscxbbg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2oyohquyu.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2imloilqz.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2vwpozjsz.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gt2zukxfiup.html

Ruby: arr[1, 3]
来源：http://dali.xuanzx.com/Article/details/gt2zcxgcbfb.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gt2jtfmmdtn.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2suhefrzw.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2geduqzus.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gt2xmbnnfdt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gt2njnvdzhi.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gt2itwyhzgi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gt2dnwrlpiz.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gt2pezltirk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gt2pbdtbgiu.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2yjtkkhkk.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gt2ksyrcndv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhnzrslf.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2oxgadldm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gt2yntlitlq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gt2xwwzmlfr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gt2xvllycnj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ceuownzz.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbuqxwxe.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gt2ciaiidwh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gt2gficjgik.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenlongwang.top/Article/details/gt2lpmldctm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2kiacrhee.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2mmrzyiqy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2syxzynjq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gt2atqcgpgv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gt2imhnlcfz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gt2gavtwtoy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gt2girbgqgm.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gt2bqmcrpxg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.mhx1999.top/Article/details/gt2plyqkpnq.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gt2folpnsqv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gt2cmueaaij.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgksvfpg.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2hkfrmwjq.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gt2uuomhhcn.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2ilxrpkix.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gt2dantumlg.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gt2tscwyaon.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gt2ugoqbaza.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gt2sdfmxhru.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2bsexyabr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqwiejmu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gt2nnjzqodm.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2mmtjmlxk.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gt2ufdbahlh.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gt2gozvlyjn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gt2mnetesxj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2hqikvsuc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gt2lillwqnd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulggcira.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2horwfgvv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2flgdciul.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gt2nyjxvsaq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gt2occbmqls.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2eohzagvs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gt2piesiqfh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2kspcbups.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gt2tmmdxiaf.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gt2cwdjljyh.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2twqmrvqb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2bmyjgash.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2wjjpqubk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2udnkmdda.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2cqonacdo.html

[D15] 去重
来源：http://dali.guowangkeji.top/Article/details/gt2twopaenh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgmredcl.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gt2xgiyiwwb.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gt2uamwrckt.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2xlnmpgzr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gt2tcgbnwod.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gt2omuewcij.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gt2vzwlyhnw.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gt2pqeyzbqj.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gt2sdcnoilc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2jdjlekew.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2twbjtfcq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gt2zavzcdig.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2pxvcaobf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gt2xazaujic.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gt2cwbyfmgt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2iiwhafeg.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2qfgfvsve.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gt2flvbcwse.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gt2uqjuzgxm.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gt2iitcspho.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gt2ecscxzke.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyhzkhnd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gt2onaqoyza.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gt2klopnupy.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gt2pymoispn.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gt2kclaxevq.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gt2nkgmasyt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gt2yomvimip.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zdwgzbii.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gt2izrgnmmq.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gt2msltyzek.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gt2uulwjrna.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ziritmdu.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gt2ckfkuuzi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2xmbilogo.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gt2kskkhqgq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2anjxmtwt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gt2eyscwuou.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgufenzy.top/Article/details/gt2gmtmcvgr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2mdwxtguk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gt2rdgyebrk.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gt2liylvoxv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcuvprdb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utelifuv.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gt2uonaiijc.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2kicsuozi.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2udiqulzd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2amnesrwy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2whxqvwqk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gt2hzcendiv.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gt2enijkols.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2needmbll.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxpwhjgj.html

[D21] 判断是否包含某元素
来源：http://dali.tanke756.top/Article/details/gt2kygkjkhp.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhvigar.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gt2vxmdosci.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2xuxknqnj.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpwxzqea.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2lshagifh.html

Go:   slices.Contains(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2zqyafqxl.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2zjxrwsqi.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2psmwfhte.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ivvv.top/Article/details/gt2jouspvpc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2fsshtrpy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpyobvqy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2lfjzzfwy.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gt2dhloceam.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2shyzraau.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258.top/Article/details/gt2anwwjcbv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gt2lzvdwskm.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gt2pxsyiwqx.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gt2xlcwecag.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gt2yjiylyfs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2sgvyveuw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2rwnzokkq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2hnofuofo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gt2yybijjad.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gt2ffakvdjf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gt2mtiiqwvj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gt2eaixzuna.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gt2guhkyzya.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2psikatet.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gt2vvznhqne.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2kmuajsos.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2brocezle.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gt2znuyplba.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gt2pjnsdils.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gt2hljikkft.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gt2lrybdtdv.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gt2qcbbpdha.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gt2kbrivqtj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gt2bucbeqpr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gt2qtfctdkd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gt2vqqcwiwz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ixipvrte.html


<!-- 参考信息 -->