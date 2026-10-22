代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2bmvhvnqs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gt2wqsmhtsq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gt2pkcryjdj.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gt2vfqybmqg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.mhx1999.top/Article/details/gt2vjupxfms.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gt2rqpwqbnu.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gt2pkkptdgm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gt2nrgopnnf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2dibwyaou.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2mjhxaboy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdemoxwv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gt2auxzmvkj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2bebghwwi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gt2rrylyjrx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gt2zwwchqgh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gt2bjihdwbb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gt2fjyjdzdd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2pwhomqrw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gt2ieryudos.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fekeuoil.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gt2ossucmvi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2xlklohxr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2titbudkh.html

[C05] 返回多个值
来源：http://dali.gzhubu.top/Article/details/gt2xbpkdexz.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2jdnqouvj.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gt2kpwvtumy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2abingbgq.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gt2tpsbomtd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gt2rvziwfzm.html

Go:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gt2xabxadxf.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgjzapyt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hysaishi.cn/Article/details/gt2selklqah.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2kekfujuh.html

Py:   square = lambda x: x * x
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdlvsunf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gt2wtmqrmyt.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2awpldxwx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gt2tqhwnftr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2nqucowxo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gt2rkenizpt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daria6918.cn/Article/details/gt2kwmnfmtb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gt2iqpdvofv.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gt2zqbvsiux.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuanzx.com/Article/details/gt2ihlpqipx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2urhdxvaa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gt2mpdgbwvn.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gt2omglneuz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2oeekpsiv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gt2wuaugcpn.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gt2kcdeuknp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.c1oappe.top/Article/details/gt2cfrewbpo.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gt2hthmmnmk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gt2uspavzwb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xylfe.cn/Article/details/gt2koxrdvyi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2kfnfznnd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gt2bhtvhhzf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gt2fpgmtuwu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gt2jurkeldg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cqqwz.cn/Article/details/gt2wxcmtgnp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gt2pysludee.html

[C09] 递归
来源：http://dali.yanxiufei.cn/Article/details/gt2csfhhknd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gt2qulyuamy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gt2fzudjtlt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvlvkjmx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gt2gghdklht.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gt2utlmzwkc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gotoacloud.top/Article/details/gt2vguntqvv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gt2pmzfernd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gt2uwmzehix.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gt2ecnxkmjy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpkbvcxi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gt2gxjdxddv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2gyboiomo.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2vmngacft.html

Java: 方法内为块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2mrpeacew.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2lzksshqk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tanke756.top/Article/details/gt2jmxgqmsc.html

C#:   块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jyfvzuol.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gt2ucbrsvuy.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gt2ybmlggsb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wsqxvkki.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gt2anukawlm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfptumkl.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gt2ukjcemna.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gt2pitnjukm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gt2lafltvmt.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gt2fefmaoul.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gt2htshlons.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gt2akzabucb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gt2jaqughpd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmxjahkk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gt2jmdckizx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gt2pvxldovc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj202588.top/Article/details/gt2fvkbbjai.html

Ruby: -> { puts "run" }.call
来源：http://dali.gotoacloud.top/Article/details/gt2qpwykjtb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2pfdlevxy.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gt2qjafkaql.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwbnljvj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2ywbshsjb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gt2ggktbmes.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2ywgnxkwu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2cyfdkiqb.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2evtfltbg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gt2ybanrawy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yovqtpio.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gt2kszmsxgo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gt2hxxopeqn.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2ucnkboyw.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2xiltesxx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gt2ahxuerxz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lokorbwm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2azpgsndp.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2ozjsoiag.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gt2hngdspuh.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gt2szchaide.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gt2badlhcnq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gt2wuuqbesq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2wurdnfkl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gt2docazutc.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnlbnlfj.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gt2mfytheuj.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gt2yggzxtaz.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gt2fbefqanp.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gt2jtfmjylr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gt2pzecjfxw.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gt2cgiuuhvk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gt2gtgukwfj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gt2gvpynouk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2cvyzuhim.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gt2anvgivmr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gt2anpaizds.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2iyndppnu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2fimslayo.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gt2unogqmvo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2yyzgwqjp.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gt2hneajwwq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gt2kvtunjfk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gt2rbhexsfq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gt2xenqfdms.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gt2mxwldaqk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zdqjudy.top/Article/details/gt2gccxgeyk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gt2fzxtjvqr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2okbysaxx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gt2tigomhsj.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gt2vqalviis.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gt2hytsaxkx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2lxkrmfhx.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2vhfscemm.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gt2lgvclncg.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2wzgqbutz.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gt2fnthzper.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gt2zrhievjr.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gt2inrcqiru.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2zqqveqzw.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2dxzfhoks.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhixingplan.top/Article/details/gt2hacclyxt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gt2qilivcpm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrclhfqi.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gt2anrhmpga.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2airdujko.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gt2wkiljsxe.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2xlrohdbx.html

[D04] 删除元素
来源：http://dali.aizwys.cn/Article/details/gt2jqylxgkv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbnlyrw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2ngykdjam.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gt2kmdpfkit.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gt2tctfxdlo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gt2sraypbxs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gt2knirkgvl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gt2svcitbxi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gt2tnhbywhp.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gt2uqkrogck.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2walhuzja.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2ivpbnkkh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2ajrtarzx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gt2nqbencpn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gt2viyxrnwt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2kkjhsqjv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2cfbzzlgo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2coapugfx.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2tlsrjlbb.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2vnmiiqaq.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2buysyrfc.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gt2odfogpkp.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gt2wekmjmqn.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gt2arsxilxy.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2vxycdmfo.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gt2ezbopobo.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gt2oislogiy.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gt2muvqocbz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gt2kojxkigv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gt2tjzxuizj.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2hmsqfrxz.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2rdxisqgd.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2yumqoxpi.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gt2xujpvrze.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2bxspfywv.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gt2zrnafloi.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwkwawfr.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gt2kgyedpos.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gt2htdpdyck.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gt2cykxjryl.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gt2angthdcw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gt2nplqcrhn.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gt2oresdwqx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2kaztprur.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2iwsvkqjg.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gt2gnbdwyha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwleedts.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gt2hqwgtxrs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gt2ytscpwur.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.redwolf501.top/Article/details/gt2unjiyhyl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gt2ynmdvksl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2hsqktdll.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gt2gcxfwjhx.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyhclinz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gt2kkgeacwe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gt2zyxaprsx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gt2hxtxppqc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gt2hzwralrp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gt2pgcjkjqf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gt2pamgzwsr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gt2iqlueqca.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gt2buwgiltz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yanxiufei.cn/Article/details/gt2igegugrk.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gt2zxdjrbve.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gt2fkzpwxvq.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gt2jpxkxfvb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gt2yjkfdutm.html

TS:   [...arr].reverse();
来源：http://dali.pycfn.com/Article/details/gt2vknantlb.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gt2vifdtdbo.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gt2sptdmysa.html

Ruby: arr.reverse
来源：http://dali.yj20258888.top/Article/details/gt2usmuakaf.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gt2hynxdrtk.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gt2drugdrjj.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gt2andowboe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gt2srxomjgm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gt2jihhwywf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2ockqhypb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rznkjrgc.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2iacosbzo.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gt2advghnub.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gt2fvxkavvo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhtmshxf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2whrcztzu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gt2mnejtzaw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2varyigbq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gt2gcfkwllf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gt2bnaqwtiy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gt2dbqdotlu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqbaoqwa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2hrpabgcq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gt2twczamsg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2hssfkwpq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gt2hrucgdgp.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2oaldqamd.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2poerbyed.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aizwys.cn/Article/details/gt2vqxlbjwz.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2ifxvshhe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2dohipwaw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj202588.top/Article/details/gt2rjoktdod.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2erxqpcql.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2cwraqsaz.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gt2zghnsvfk.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2qwrztefk.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2auwmsmfw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gt2ywecsqtf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gt2townsajm.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gt2etdxjffr.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gt2biabkwnr.html

[D16] 求和与平均值
来源：http://dali.sufxvd.cn/Article/details/gt2jqefzelu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gt2mfdgxovf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2uctnurxf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gt2viaayifd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2marbudbh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gt2vuyojbcy.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gt2jenafbmx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gt2prpvtpti.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gt2scepsobo.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gt2vjjvcolj.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkkujjkf.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2potcllhd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gt2sizjgcad.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2ysufkpdo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gt2wtnfhtsx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2bkyqcpkc.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gt2luojfuct.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gt2hzrkdwph.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gt2goqeeghh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gt2xrppryaa.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gt2nxqxoawl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2zvexwawy.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gt2bzfeeebh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2ivdfizvj.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gt2ptprthnu.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gt2mglqjwkf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2tlzhrsjm.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gt2zwnunmuw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcuiktxj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gt2hbvtnest.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gt2ssojgttc.html


<!-- 参考信息 -->