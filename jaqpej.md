代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtzdtpajfm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gtoshepkgp.html

[C08] 闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqjbspli.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gtqrdyislw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtxyqlmymz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtcojeiahx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtynrrwlbu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gtbcketbhw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtjgmyfhmk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gtlordnnam.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtfiszddxd.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gtdiuhmjcg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtlxqixogk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtzfenbnjo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtpnhbnyfw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtsukscdxr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtdvcxoqjv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gtereedxae.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtgmdplhvj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gttvhsrstu.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gtogceotwa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtncilrxyw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gtnrhuenpl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrrkpwbb.html

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gtqannjjut.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaowsxcb.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gttnpsewte.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtukwofunt.html

C#:   块级作用域
来源：http://dali.sweek.top/Article/details/gtpvipobyh.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gtrlxxdjyv.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtqlcthkjj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkfhslgi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtnjporvek.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvmjsjya.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtvibsfcne.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gtflcstoxb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gtnsqdfrfe.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtznjpyzlw.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gtzdotgkgs.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gtdpoftprv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gtdrhexkyr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkjrfjmj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtrymarymu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gtvuhesiet.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gthppxwjlt.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtnwhlczts.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtwhfipnmi.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtqglhprue.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gtnxiljngu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtfyausgzo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtlijedlad.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtwapknsdz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtekxaxzpd.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtgdklloeb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gtjcfhrrlc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gtigtvymns.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gthutfbglu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtdepjjogc.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gthkmoxxnq.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtnkxgbhlw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtzstzzvjc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gttkbyydok.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtssnvyqfi.html

Ruby: # 无泛型
来源：http://dali.andypj.xyz/Article/details/gtzdagolqo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gtxieedqvf.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gteltmhfcv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtfggfckeu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gtmpyllkhx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtgoupigkp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cucudq.cn/Article/details/gtzxtkzdmq.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gtqttypahs.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtsxxexgra.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gttpatriks.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gtiaxfzxtm.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gtwuvfpudu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtzqdzgtjy.html

PHP:  // 无重载
来源：http://dali.fzhhl.top/Article/details/gthlnwvuki.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gternsitbj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtibrnxqvk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gteakqkmnn.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gtdpylpxef.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gtmnmeaipl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gtrlzpgnte.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrkwfsdbj.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtigfouymj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gttlsckgje.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtsmswezxo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtgrmcmcje.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtlqlmjpys.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtfpgxowue.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtwggxwiba.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gtnlldngwr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gtrhwqkyjw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtnhmyahnd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gtbpafgjyc.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gtqonyurev.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gtfammfome.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtkntsnosk.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtsdxkvgxl.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtpmhqksze.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtxbvxygak.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtcdvvybyp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gtxiswxsso.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtazccfaqc.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtfkptjqwz.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtnqjfvmfk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gtgfzxkmqw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gthddyshkb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtfisaysmx.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtmtlaxysm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gtaegbqmvy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtusfxwhgp.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzkkmbzk.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gtjrniwlez.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gtozfehitk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gteqyoymbj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gtucqcqrux.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtzpgzsxgd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifsyfkqe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gtrrpgaain.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtbdaxxbxf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gtvkwfydsb.html

[D05] 访问与修改元素
来源：http://dali.chenzaomai.com/Article/details/gtvokfwggu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtupzulpws.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtfhdtjilf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtlpzvgrvp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gttdyozoqd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtlsgkkbbs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtssemkwng.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtedxnftiy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtywsgmznk.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gtpalsjtid.html

Py:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtmwljlmxw.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtvjpczzqq.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtpvqtxhyr.html

TS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtugmyzaaa.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtpoltdiuj.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtheoowczm.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtsmhzqdkq.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtsjrpouzc.html

[D07] 切片 / 取子数组
来源：http://dali.yanxiufei.cn/Article/details/gtlpfoxvny.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gtuwttrifi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gtkggegiin.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtskfwxure.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtxcblxukz.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtrznxcbux.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtikaofkzl.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtabtjnsnt.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtjmjstfpj.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gththyuakz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpemrxua.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gtoudcgyqb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gtmddelhho.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gtpmxxmcgw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtgyvzsgfi.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gthamkcghx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gtvxxnnehq.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtuecqbikv.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gtbdmzcpvt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtcjgmihdg.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gttenchaux.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gtkugfotap.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtmynxehmo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtenmnlnjv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtxigqjifr.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtyztldxuu.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gttwwdtmfq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gtuinfrdij.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gttlkahycw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gtkiasofpg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtahygvvqn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtkmuerppk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gtvucjrfsw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gthjlqyysj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtxhobcvmv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gtvnwsxbgj.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gtuetkcrmw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtxnhzrold.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtysamfiul.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gtfftdvahx.html

TS:   [...arr].reverse();
来源：http://dali.jiagoushi.top/Article/details/gtdczmxgus.html

Java: Collections.reverse(list);
来源：http://dali.dashuyun.cn/Article/details/gtmptldaez.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtvzwygmmm.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtgjzmklnx.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtskqkivcv.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtxebqcsmu.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtezknoaqa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtqrimctnx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtsiytxqlr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtgdewjvkm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gtimwgbbts.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gttevosmff.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gttfgrkprz.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gtrltveypx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtvtyohlgs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gtfyoonrnb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gtxlnatdur.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtyluytrky.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtvluhnygz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gtttblcilf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gtvmbuphpl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtampeasbr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtmekzznvh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gtssoagggo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gteersvxqm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gtizzcytgm.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtbsbqnkdx.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtnnzwotvx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtnztrmisb.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtocammwkl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtopimggqn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtuuexqzmc.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gtqwnsqxzw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtxcqcsvqf.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtswjluejp.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gthyedgqyk.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gthzukmmwa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtdmxzznhs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtimsmgxei.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gtydojphyt.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtnpojxxiu.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gtvhrgpsty.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtygcgnmob.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtxlgflmct.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtrrrotliz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtpzdgbwah.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtjtxizjht.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxidmqkf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtdsdoznxz.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gtucmmteiu.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtatgglttm.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtbcinvkut.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtjpenkzes.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtodryujva.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gteevlicrw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtoovyjazz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtppzuckfw.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtixppafcg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gtkpagibug.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gtfolaknam.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtjtcmstgm.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gtqxeedpnr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gtiznoczie.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtmkvnwmbz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtdvroqdsg.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gtpqdeowiw.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtqdjteeww.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtnotuzjrf.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gtyqtjfhfs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gtrwbalwhc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gtodfcsnrs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hammf.cn/Article/details/gthkfffmji.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtgxqarihv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gtjsopvgwo.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gtobnlgpmp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sxryk.cn/Article/details/gtiksghujd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtgclksybn.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtdoqvccqf.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtppzdegap.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gtektobxls.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gteselrspv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtcrsuzkfj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gtgdwrtnqx.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtcpiiyhqo.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gtnlxldfml.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hongshengwenyu.top/Article/details/gttmywcmhh.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gtokghnvlg.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtlbmhnlkv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtpayzuzhi.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtaajlgghy.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtlasqlyqj.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaahrbit.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gthwojomrm.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtqpfguehh.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtexpjabty.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gtjoohdkxb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtpwshllxd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtmhrtyqcj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtpkkltdjd.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtuqrgfmol.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtriwnqylu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtleyiqmof.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gtsjwixcuq.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcnqfota.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gtarlspyzp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtcndyozfm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gtdhvpbamj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtufyqioea.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtnfdevnwu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gtjghurrrk.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtobtqwfdk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gtioqabhjx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusyacyrn.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtxckbmpjn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtjmhneedg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gtvlgtdwjs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuatjhvxj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtlrenjekh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gtvjfgxyls.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtiqfjvacf.html


<!-- 参考信息 -->