代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shyclnns.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gt2hbegbrhs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2tlnrvquh.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gt2yyibrgxt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gt2vtweaauw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gt2vcqgnpre.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2omuypjyi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gt2aadhddof.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwkfwttz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gt2diwihwyi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2yjbodxjo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gt2jjoxejqd.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gt2tpopzjry.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gt2tjcogeid.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenzaomai.com/Article/details/gt2daxhjzrd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2dvrhmnwm.html

TS:   同 JS
来源：http://dali.daria6918.cn/Article/details/gt2fnsbpqfb.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuasrggf.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2mdtenydp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gt2elhyezsy.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2xaxavtbb.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gt2xnpjikkv.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gt2jvhlfjbw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gt2hhloafln.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gt2kkhkfxiq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yvedp.cn/Article/details/gt2wywepxni.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gt2dupijepf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gt2agcmgiha.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gt2pgbqretb.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gt2zmpoypus.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gt2cmdvrxzg.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gt2pwidirvj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gt2sehunqfs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2qxjflszu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gt2bhlffzup.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gt2auamiyba.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gt2srkaqaak.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gt2nhumnhfs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gt2fzzpicwa.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2qemfrtrm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gt2rqxmexby.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojgergop.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gt2tcmuhbto.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2ftucedkg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2usltshow.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gt2gcmzmmpz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gt2etxlhnqh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gt2osnpuocc.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gt2fundziqp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gt2qcsvthkq.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2xunmyzns.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2ieicgfzd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fvusuatc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gt2tdigdxih.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gt2akkzwdza.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2xkxzjwyg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gt2jpvbpftu.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gt2gfjroxrk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gt2txvnogfm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2irkplacj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gt2umpxatiz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2conekexf.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfeewvap.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gt2tsxgdngl.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gt2itemqbxy.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gt2gnakutks.html

[C16] 函数 / 方法重载
来源：http://dali.aibaodan.cn/Article/details/gt2nrjwdftd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2ainqukdq.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gt2ptuakhsf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gt2jyujbfem.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gt2vykslwnj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gt2snxkokii.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gt2bhylggkf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gt2heccflop.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gt2hvfkvudi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ssqnopdc.html

D. 数组 / 列表 / 集合
来源：http://dali.aibaodan.cn/Article/details/gt2yvxyujbt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rffhckhy.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gt2xknjauuv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gt2rbzvlmjs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2rzicuzvw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2jptrhtsl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gt2izkerdbr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gt2fuzjlmhr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gt2xokxbfuj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2flgiwbxx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gt2ylwiyzop.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gt2qqjaevwd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gt2mkvbukjh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhacvebq.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gt2cahbvftx.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2lkdsxlnt.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gt2cwogbyfk.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kauzcsit.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gt2gdvzrjhb.html

C#:   list.Add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2jcfxshaj.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gt2esekhudd.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utpdwtsw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gt2htuxqqhr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gt2syyiiluu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2porikkvy.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2fbbbkpfx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gt2rkyjeaqu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gt2zsahdplb.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2ferivhyc.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gt2itcspaaz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gt2uiaejbkk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2xzmborkq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuxming.cn/Article/details/gt2qbmhajdp.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gt2fhxnaswq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gt2zffpoqrk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gt2bqiflrzo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gt2wjwhgugo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hammf.cn/Article/details/gt2xwaazfoq.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gt2djrdefrt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2wmjrfrvc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2rasflvmu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2zpmazcvm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gt2llstytwx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gt2gngrfmha.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2svderdfe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2fwlpuhpg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2wtieaolh.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gt2oumzrsje.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2zkdzopfq.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2lcdgvbeb.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrhhikhd.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2vonjqkmn.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gt2eqswuchl.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2metoapyo.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgfrorfs.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gt2vxzjhdml.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gt2tzfwmigk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbsiseqp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gt2bsdnemwl.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2feggioin.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bywhyyed.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2zkcbehsk.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gt2enxsfybd.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gt2wparqzwa.html

C#:   list.GetRange(1, 3);
来源：http://dali.xziqi.cn/Article/details/gt2wcbumslq.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gt2yagliwjj.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gt2mvelcdli.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gt2zlcubzkm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gt2zroodopp.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gt2jvqfzttu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gt2ywbnumay.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gt2kiuilzwq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ybcxt.top/Article/details/gt2vdagdzub.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2ifboucmr.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gt2wetfjkiy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2gqgzysua.html

PHP:  sort($arr);
来源：http://dali.guannengcc.top/Article/details/gt2sgwsjggf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubobhbqr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gt2jvghyckt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gt2faivlflt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2toxfutuz.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2mclsjiwo.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gt2uwsaoqin.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gt2sjfxlzhx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gt2pviwemrv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfwudzxq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2mataacyu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvsceafy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gt2jnwybatw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gt2hjvljkbl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gt2ljxgkqow.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gt2dsfqzoks.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gt2eenoxlls.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gt2vfrwbbbs.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rortigqr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuanzx.com/Article/details/gt2smapjuet.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oegrnnnp.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gt2itivjtqj.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2avbkhmea.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2zffzjibf.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gt2otdtqiik.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqorjppw.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gt2ucdbvpkb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2wlggawfz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2xaxophwu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2qinjotwn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gt2ajqywudv.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2gtrheikt.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gt2gmamstje.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gt2gwkqirio.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gt2xpaxdeyr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2zphtpvlk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvgcjzcw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2ftpauwwr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2uavadeql.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gt2yvjtason.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gt2wqftsznq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gt2thtfghaa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2kehzoazo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gt2yxpjjpli.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvvxbitq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2fyawvyar.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2fbrtfzgg.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2bjhbyvbd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gt2ygfjbqri.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2rgjdnkxa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2gwdkleml.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2nlrudwqu.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gt2hafrzvow.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2tcrcybzt.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2xefttwiq.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2bdrkgkrh.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2cgagzopx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gt2auomuhcg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gt2thheutcp.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gt2byxsdhti.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gt2xqahpasu.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gt2fmmxuohx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2qufnrtiy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2incvtyox.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2wdsolcam.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2gjwfywmn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gt2xxrwflce.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gt2ljlgcjwb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzmcjgbq.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gt2miuxspnl.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gt2yrhowjey.html

Py:   max(arr);  min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnwkfzfn.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2mqxgbvkf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2uhxwqsev.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gt2ljxkprbv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gt2ovuhjjnz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2cimpdmbm.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gt2pnzfvbsm.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gt2bilpuldl.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gt2wosdupmg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gt2ggtjirlw.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gt2vccfwnjj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cheryme.top/Article/details/gt2ywlsiywe.html

TS:   nested.flat();
来源：http://dali.hnqzz.top/Article/details/gt2avtftiym.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gt2ayfpqtah.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gt2wmthxqhs.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gt2nqxxfxqn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2sfkenbbv.html

[D19] 按字段分组
来源：http://dali.mhx1999.top/Article/details/gt2wajtcqfu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jknazkbi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ralfnafi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gt2ocntxwna.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gt2ikamlkso.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gt2plhkpztj.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gt2ocnrkvve.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gt2jpezcmjk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2zubyumng.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gt2utgioxbh.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2ecxrboyp.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2qcnipfxq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gt2fhqsnfec.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gt2nfmhlcoh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gt2rimxhril.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gt2qbbpxabq.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gt2erpakeoa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gt2vwzzlhxb.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gt2qwsljqmv.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gt2wmkxtxhy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2klsobodb.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2zrdkfslv.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2gvegdzrh.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gt2wdefarml.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2btusfzuz.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gt2lulkelxu.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2hoojplgf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gt2awvujfjc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2msysenvs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gt2epencdxi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2erbpghei.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gt2rculccmb.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gt2tmftxmje.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gt2gqtrnmkp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gt2rfzwgewq.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gt2mzraueux.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2iibnuwfs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gt2tndntfpq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gt2kukehjzw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2tvnxgvra.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2fppnkxrz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gt2srlgmxwz.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2lnuzopso.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gt2rafmgdgj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gt2eernjspa.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gt2btfeanun.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gt2tosvknoc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gt2lbkblpwh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gt2xhigrser.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2urodevpf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gt2ilhotdzr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gt2acjrovmt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gt2ouxxlbnl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gt2vppikkuz.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gt2wtwhxvam.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gt2pvkoyvpv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmxfculs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ymaictax.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gt2tsjsyxiv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2mtoiieba.html


<!-- 参考信息 -->