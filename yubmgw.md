代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gt2jzzxrrkj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gt2jfzjysds.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gt2jwyckvls.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gt2frjtblya.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gshbkwyk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gt2uvhyetmj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2sjhazgxa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gt2aiuwjpib.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gt2cixthmmq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gt2xuxzbioq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gt2fnkwuwzg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfueggvt.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gt2rqmmlqbo.html

Java: 方法内为块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2dvtovqed.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2iomiwbdv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gt2bubmewnd.html

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2nahpxchx.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gt2vhaazitj.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gt2ygfatoep.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gt2yfwoulnv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcvlchio.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gt2dhaazmgx.html

Java: import java.util.List;
来源：http://dali.xuanzx.com/Article/details/gt2zpkbfysy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gt2eyrbyzcz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gt2wmsbpiyj.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gt2brnnrceo.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gt2vjxbzyej.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gt2wrssdveh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gt2kfxqbplw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2wdvmlqqh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvdxecty.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqqxkqus.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gt2acpxdemj.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gt2kzvlqotu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gt2itnsxdul.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gt2btaldghc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gt2xykpdbrc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2mituhsxl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gt2pjatrqqb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2npjpwzuz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2yuwnryxe.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gt2tdjngxde.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gt2cmbbxfft.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gt2oomzrnwm.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gt2tlmpismg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenzaomai.com/Article/details/gt2bxvhkhff.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gt2daablkat.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2wstdiqru.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gt2zdcqmjud.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gt2dooodkuy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gt2jlkhsfau.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2luhtilef.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gt2bqsypdse.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gt2fkphhwbn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gt2gpjblzot.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xziqi.cn/Article/details/gt2yyhgtvik.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2wktlvhvh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gt2vhlfhgmt.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gt2eqdwpjoa.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2haxblryd.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gt2lapcssgq.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2anfiggkf.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzcfuuok.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2vzjlawya.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2mtbbqrkb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gt2vekbibso.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxinkj.top/Article/details/gt2akocolwj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gt2reavstwd.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gt2cvzqtplk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gt2fnowplga.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2uihkejcf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fuixzgrm.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2slcrfpns.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2eupsusze.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gt2tfpafqnv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pengpengdd.cyou/Article/details/gt2dawnlqer.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flhlezmt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gt2dsnsclhd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gt2dlbeqcro.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgufenzy.top/Article/details/gt2ibblmqrz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gt2isngxmfz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gt2lneosloj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gt2ccydqske.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gt2adxfpmes.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.redwolf501.top/Article/details/gt2bmbdrnvj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2ldulkegf.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gt2bqfaumvt.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gt2lgjwgyms.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gt2whtdtpgf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoxyhzc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gt2quarovbv.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2rsyztozg.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gt2otmffzac.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2mbvokwlo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aamkmuhx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yppckaqd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2ksfnjhpd.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvrstzck.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2onsbagts.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gt2jfpannzy.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2qcirxekw.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2tpannqyn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gt2ofbovqfg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2jnyslnno.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gt2joqscefk.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gt2atgwbcrc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nwbrower.top/Article/details/gt2nwausmjj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gt2jnfvwlqe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbrcnjyc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gt2enzateae.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gt2wordsput.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2ftczrcrb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2ywygjaid.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2vuzqtutn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gt2mfynssml.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gt2ywattptl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2wysuquoo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2cjyotitk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2bcqobpnm.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gt2ztafidin.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gt2ceiizval.html

PHP:  count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2epjoaitp.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2vhgtcemo.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gt2lafnmopy.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gt2omydbfwz.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2ihldwbfr.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gt2nfotmyfj.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdbentlv.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gt2nnfcvrxy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gt2szqzcogm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2etiqvgjc.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2ziwnkuju.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2luiinvup.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2hxjltekl.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gt2tdwhuppa.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gt2ammwjvhc.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wovwkwfw.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gt2lzspxcbd.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gt2lgfctucp.html

PHP:  array_merge($a, $b);
来源：http://dali.dashuyun.cn/Article/details/gt2loubgiau.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gt2ulyrrmsf.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gt2dmazzlpk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzhvqiwv.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gt2gzhaxkal.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gt2lpcisavt.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gt2bvstubfe.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gt2vtacdtgi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2afuqszwh.html

PHP:  sort($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2owqfhyrt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gt2wxqyxncj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gt2iarlfelv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2plutbepe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2aotgnwuv.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2ktixdzkc.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gt2uzekdvob.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.snrcjt.cn/Article/details/gt2tcclgjdr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2bcjzwmeg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2ukranory.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gt2wqmwyuuz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gt2zkspyvhi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gt2pyvjpiew.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gt2efzgmdtz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gt2ioydlyli.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gt2bhoqokbh.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gt2lfqofigt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gt2vncklpod.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gt2gjbrvlii.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gt2rlmpnfyq.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxrshsop.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gt2zvjpzjis.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gt2hjqwteuf.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afrmepvc.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gt2zrfsuzox.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gt2wvcmldhd.html

Py:   arr.index(x);  x in arr
来源：http://dali.daria6918.cn/Article/details/gt2syxyqvmz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srunvvai.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2xvjnecwt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2jlnntgnr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gt2tddnlgqc.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2pfpmgtmw.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2pulpckjz.html

C#:   list.IndexOf(x);
来源：http://dali.sweek.top/Article/details/gt2ptbpusrg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gt2hiyugnay.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqgtqymj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gt2rjbowwao.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnjwffwx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2hyjzipjc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2ohelhfhm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gt2lhnilxux.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.birdmap.top/Article/details/gt2wnixaakq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2qnkhfgpt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsfbnseh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gt2dxfhkktm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gt2ylfrzlkp.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwktsokh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2lezosptw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2arqgfwwf.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gt2opckzick.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2zryhcjye.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2hhkzwbki.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxueaiha.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2jybisaac.html

PHP:  array_unique($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhgtrndx.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2vmwnffyq.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2jeqmbqpw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gt2gbufflrl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gt2dfeuprtf.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gt2mmxzzxaa.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2oijhyots.html

[D16] 求和与平均值
来源：http://dali.yuanzhike.top/Article/details/gt2yfmbeujf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2cagsyyjc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2vyfxlloo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2hrhnqprk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2nsddmnfg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gt2sppmorim.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gt2fcwowmud.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2sdqegkox.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gt2jgcphcbj.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gt2vsokrrje.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2ohrwqmfg.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2bcobriwb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gt2ixgrykrn.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gt2dphbkpmj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gt2djxfwixb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2prhmixnx.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gt2enetmkny.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gt2hcswmnlb.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gt2mdbevkhj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gt2uhiqhsuv.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gt2dkqiqadw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gt2egpusfhy.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gt2nbdzhivq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gt2efmpeqvu.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gt2gznkxgvp.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gt2ufabpdxb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gt2khzmaztw.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyqnzqb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gt2olbuofqz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gt2xltnlmns.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzqrcjbt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gt2epiddxrb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gt2xoreqwfa.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfrxkwkp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gt2cydesmtb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gt2afvbiyzr.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gt2suflqxjt.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2pipjredd.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gt2lbzkfjup.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gt2npkwfsfb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gt2tgcfplly.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gt2yejvbatl.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gt2ofkvtwsp.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gt2wcmroxyn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gt2flhlauxi.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gt2vskvlbfu.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2fmprnqcl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2tnwjgvve.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2aqywyrix.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2xwzozaro.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjgzlwgw.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2kjzltosf.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2exrjvlwa.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2qytpkkiu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gt2tzsgrdvv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gt2vivdkjmk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.svipenyu.cn/Article/details/gt2zzcuuuad.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gt2gtdhmngx.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gt2kdyyhnbl.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzkxrltz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2ozudkegb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gt2btlrvrkx.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gt2bqgvhqpg.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gt2iprvcnbm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2tavegcwi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2debhctqp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2nbfotuih.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2nprfkmmr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gt2rfdqvhkx.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gt2prftmsxy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gt2jkzogefn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shzxlz.cn/Article/details/gt2kugsohtm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gt2pxquednt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2jatzduav.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gt2fxwjuipd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2fydjugbz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2uqvhjwwk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfkgkhkm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gt2taibrciy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gt2rfeaaoas.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gt2vibickvq.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gt2mwomcnwq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gt2oixhhoai.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gt2azviakyn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gt2noevxipa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gt2zvaosdxt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gt2azakcvct.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gt2wqaexgnr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gt2kibvukup.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2rzrzfiuq.html

[D26] 数组转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2qojwmgke.html


<!-- 参考信息 -->