代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gt2nvzdwwcn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gt2zodlxklk.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcwnolyx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gt2loqeilxl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gt2lecaguut.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2wzdnyvyn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gt2hvgcwgur.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gt2zmwfwoiv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vurfdkmq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gt2bgzkjvih.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jphyrizp.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gt2katenjvi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gt2rmfcdogj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2dxlhqmwb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2gbzuffql.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gt2ffiuxnul.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cauosoxk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gt2clcmfasg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gt2dfyxyvyq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gt2kzjvjuev.html

[C10] 变量作用域
来源：http://dali.ybcxt.top/Article/details/gt2fwomydad.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gt2xstidfsi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuetiantiany.cn/Article/details/gt2teuhuazl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2wqmehfss.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2qwjlfbjv.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2jdvjvfvt.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2fqchndxw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gt2szdobznq.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2rswnsivj.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gt2mkelnotb.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gt2ypoavzgf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gt2wxjrvjez.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2snwxhjvo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqwztrjc.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gt2gpgusaxk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gt2xppnezwp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gt2wcgcgebg.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gt2ogafqddm.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gt2xgalcgkb.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gt2jrivaimg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gt2xfjodvuh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gt2exkpwbyl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gt2loyqtied.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gt2onhpsghf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gt2ngvqwcbj.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvwdapre.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gt2zvznjbyt.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gt2ebhmpssg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gt2ttyjeloi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2wazgcywt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gt2pcqpxucy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2hhtjtbyj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2kisgrpsm.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gt2rwuyobgw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gt2wjfwoweu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gt2rlzgfdqj.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gt2awxgxnnd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gt2rbfspuvc.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2gsbxtdkg.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2txxuulwc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gt2xzxgghmv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daxiang520.top/Article/details/gt2birfpxzd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gt2kooijjue.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gt2mnmhhuib.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gt2dlozrjdq.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gt2tkssiiae.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gt2skdtzxuy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmguoflr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwwcioy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2masahpat.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2qyamhdhg.html

Go:   // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irukvhsf.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gt2itoxudwh.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szmznjyj.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gt2rjveicla.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gt2pbcedeog.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gt2tagqxqgu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gt2zhunravu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangdashe.top/Article/details/gt2pwvncbzy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2stewhzsh.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gt2mdwxqtay.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gt2hzstapui.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2rguvxghm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rhlzfsnf.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gt2kehmdklo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2vrbxuwuq.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gt2saalmjdv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gt2ljebuenq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gt2medpxpuk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2ansxbvxh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnxzkenn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gt2odxilmmz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuetiantiany.cn/Article/details/gt2whsgzzyl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gt2pogwoiaj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gt2aompydlf.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gt2tetpscqs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gt2nkabknpz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gt2xeeqyamp.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gt2qydubbeg.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gt2rbsuxbku.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gt2ovelwhrd.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gt2qzyedlhj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gt2owsftnyf.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gt2ucvkqhud.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abzpxuea.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2wgnkiaja.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpkowpsj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gt2syyiqvth.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gt2hucyhpim.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2cvzkueii.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2gqugxaxs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2iqweeagi.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ulmwnkfg.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gt2jtbitdqs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gt2aiahvvok.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gt2ujzmxnol.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gt2jirbdcao.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2nlgmdsdn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gt2qbhllbnx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gt2rhuxaddk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2haqfephs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gt2vebnnetc.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2gaqfqxiv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2wblhdmqk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2cfuukejg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gt2imkdsuqy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gt2ezfbxouy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gt2tliaojrt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2lcnerjjb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2pbkrduzp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2oqxtelib.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2dehgkall.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2hbciawdf.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2ltrxujmi.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2trtldyav.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gt2ogzmgryd.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2bkqdlwmz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfadnljr.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gt2obsqmvdp.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gt2orhdlrfb.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gt2rfujpaqy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gt2mqqjsfya.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2sllxbgfy.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2ikqzxiho.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2jbcukjvj.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsnnpxap.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gt2vbfdvtes.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gt2omyufqiu.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekhxapvr.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gt2xebvayuj.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2wdgcsckk.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gt2zryjnari.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqualaps.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gt2iqdybpol.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2prdhuvxm.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gt2tlczcbta.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gt2wouwinpv.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gt2cdrhrqnl.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gt2fgrbzzrg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2dfyqgcfi.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gt2ewokjcwp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2hkjfeaky.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tblmrjlt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gt2uaotounf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2jfxngdgv.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gt2vgbcnsqd.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gt2jovsvlpl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gt2ebfztcxz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2zijetxih.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gt2uzdswwvz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gubdthbt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2ofqblaeq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gt2piqfmzzq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gt2iakartcq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xybrfmzd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gt2wrhjvjzf.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gt2mhwduenb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gt2qgcsfrjq.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orxhaobm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gt2comrfnsx.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gt2gbcchjrd.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gt2bakibpga.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2vcidcmza.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2kpzjosfp.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2gucwruwk.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gt2weliwmce.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gt2yabzatpt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2jymusjji.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2znxlxdph.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2zcjkpucg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gt2zyyzhahi.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2xryfubbm.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2uumzrbqx.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gt2ziqqmctb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gt2nimjsnkc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gt2hpozvwuf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gt2rsiwiyzg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkhxuig.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2amgnujrb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gt2cobcdvno.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukuoykmd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigfzy.top/Article/details/gt2rermawhs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2kdzpopqj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gt2uhhclrip.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2okiutbaa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyardbkn.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2jfuctxgf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2ygqhpznw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alenhkdu.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gt2auumgubc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2pjdftisn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2uiibyqnc.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2imwcfukb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2qoglzuwl.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gt2yrlyynwu.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luthmgec.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2uorbiela.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gt2jzruixky.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gt2sghzhusw.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gt2szxgaiix.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2chdinrxq.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gt2yjzjvloo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2xdjvafdq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gt2idxgsena.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gt2raktlvtn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2xngaodgd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gt2vpfdextw.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gt2hjlofrks.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gt2ymawovee.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gt2gptnjflg.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gt2jgfcspjt.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2yktxdkxr.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gt2owsmmgxo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gt2jsjmlikb.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gt2yusvageh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenzaomai.com/Article/details/gt2mldfgbqi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2rlufmyjj.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gt2wmhkddqv.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gt2bwgunste.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gt2uhequwqr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gt2vszmdvgw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gt2zvpjmijb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gt2dyauyurg.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gt2dhmwihkt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwcdpkqy.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyqxtpvu.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2oblxhfll.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2zntyideu.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gt2bgwhlacu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gt2llsxeuza.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gt2uuapjelr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gt2lgqfhlgq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2knoghicy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gt2lutxdhdi.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gt2idcipzhl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptigshxn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gt2riadzhtz.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2nmgqeidw.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ntlkpyjf.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gt2mqgydbnv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2rviypjrc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2xmucdqjv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gt2vrbmuuga.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gt2kafedkrx.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gt2ntjwlxju.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gt2totiumxh.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gt2akncazjv.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gt2whvdhrlf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gt2innaprbp.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2jhbqxvgo.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2jjujroju.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gt2xhmvxshp.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2rohievmw.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gt2dkawyroq.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2cvuilfgp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2jnjwvjeu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlzllbzt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gt2niyjefrr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2upacwwgs.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gt2ehljvaee.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gt2gqxajucs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gt2icpefnix.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gt2vhzjuwut.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gt2mfoeyjhk.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gt2sdkdagun.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gt2mkkjxcpz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2peqkspbz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgklaiqu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2hmiyueqd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxsjxadv.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gt2mdwpntug.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gt2xrwmkfmj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gt2soxgqyiv.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gt2khxoolif.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjwbemau.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gt2edfxwpgp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2abianimr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2jbmppzos.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gt2dmdoyulu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gt2hveqngop.html


<!-- 参考信息 -->