代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gt2uvqzcrdc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gt2wkywdrmp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yoaejqfr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gt2iiqqmszn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gt2qkjfhqbx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gt2thjfwzdn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gt2wpyareoc.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gt2lgbabfzt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gt2nrdrslfv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gt2dgfeibtp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gt2ttheadmr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gt2fwbbjzzh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2yhwgrjse.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gt2dbinrnyw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kghrbgii.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrbzdbry.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gt2wqmseulj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gt2afacvyzp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dashuyun.cn/Article/details/gt2lxxarunu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gt2eciyacth.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzdbcbyc.html

Java: 方法内为块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2oqynywso.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2buuxbqbx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gt2bbuywhcf.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2qnbbjbip.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gt2mextdjti.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gt2atpovkgy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gt2gbuppkpz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gt2jysmrjxi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gt2otbtdnga.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gt2zonaodca.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqfinodf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcxbasux.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gt2wbuhpoqv.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxgszfnp.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gt2bnfvphqv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gt2cpxempgk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2grgcodhj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlgilizw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.mhx1999.top/Article/details/gt2rkzaqemx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gt2swvxtejf.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gt2hfwybbgh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2sdqwtklw.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gt2qbwgeccs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gt2xrxjunnh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gt2wrofuutw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gt2aumfbrct.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2vjlchrft.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ueoymvrh.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gt2pqrtcarx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gt2bohmnxhc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gt2zhidrkar.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gt2frrugebf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrxtolxq.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2lkagsmdn.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2bprinvbj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gt2vuczcxus.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gt2fspymlft.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gt2aejwyxtn.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2ornavqhw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gt2cgabmxke.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gt2vlhcuinf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gt2qctcnygg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gt2lidwhnfe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qggtiibg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwhxyzrl.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2roebstgm.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2otedupwj.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gt2nklzynei.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gt2gmjenpxp.html

[C16] 函数 / 方法重载
来源：http://dali.316326.xyz/Article/details/gt2wrpuwvcf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigufen.top/Article/details/gt2muklzrnl.html

PHP:  // 无重载
来源：http://dali.yj202588.top/Article/details/gt2hxdpvhdh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gt2ratoruht.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2rntquald.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gt2yecuejtv.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gt2qeplfqsz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gt2vqgffrsa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gt2pykangae.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2qwofderd.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gt2klvutnkp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lewutsvz.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gt2gmatmxaj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xinyue.icu/Article/details/gt2hdmmedoo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gt2zchlwzas.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gt2azqfnvky.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gt2qagovoaz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gt2dubuxnmg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyamalia.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gt2zgwjvuxt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzxtiwok.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gt2qgnxclqs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gt2snyubhpl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gt2kozmycmt.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2ooukkxdl.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2uljaczii.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gt2tcjopcmk.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gt2novsvcoa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gt2likattrl.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2efkcflse.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2ibesgxke.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2unyzmegu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gt2gpddrvmv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahmfgnfz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2knazesun.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2hikokily.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drygrrgs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2mobffsbf.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2scsnlkwg.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2gakvrvkc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gt2ooglvltr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gt2wuhfktnn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gt2aveeysja.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjdvftwk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukmppcks.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hllxdvvo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gt2rqbbkioc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gt2fsllcbxo.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gt2iagfigjc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2hjpblzix.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gt2qsudpxmv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2aflyhtck.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gt2fuycqedz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gt2knltijlj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2ukopvcrr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2ohpvvhdv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2jjtjypvl.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2zaamiawb.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2clbqhjgc.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2evnkmcsm.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gt2rjzoqqjt.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2nlmvwdjs.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gt2kyptvhmf.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2jjdremzm.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gt2cevpuirn.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gt2clmpaxwm.html

[D07] 切片 / 取子数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixxtfomn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gt2hbltgzee.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2efblxwef.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivbnjsmh.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2hlpfyyxo.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2ajdietng.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gt2cfzqymfd.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gt2uqzxmqns.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2hjrvoqsh.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gt2olsgwfhb.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2unhrsgva.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gt2mgetjeen.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gt2puctcmhm.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gt2jofphsty.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2mnhhiqhx.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gt2zzujflze.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gt2ppeikcup.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2qlzfwxwu.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gt2vtcuhzep.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gt2zhgbaqmh.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gt2vlzhebda.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gt2gkrtgcaq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gt2kkkhtdqt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gt2rfrbluyb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2wrkyalgo.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2oiflrgxl.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gt2ecrkjmrh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gt2cagcmixv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gt2dfbyjfhu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gt2zjgozpjn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gt2mzedkfzp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2dbsippfq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.9152youxi.cn/Article/details/gt2cpevfyjo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gt2chczwljr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gt2nvjkbcva.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gt2qfrpmwhc.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gt2tgjxvflq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gt2cmsvgcxs.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2wtzgjjsk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gt2ubawaujv.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2dsishtuk.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gt2ihfzavod.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gt2nzdcaqyo.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gt2qtjltqfv.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjwmjbpx.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgugqzsi.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxnvclks.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2pofvuoge.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2gxztnsju.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgdschc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gt2xebcbllz.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hoiznsag.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvekbtdd.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gt2rlgndtyi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gt2oyxlrcex.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2ediwkcar.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gt2apaepkku.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2ehkhcccl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2bcpagngc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2xwecukdd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gt2vvilykkw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gt2foleiytj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2stxdvmms.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfcwxddx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gt2iovhmuxy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2cvwshjvh.html

JS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gt2djpmaejl.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2nxjkzvqf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gt2zbhwxlvm.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mntqdkvw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2crccahvz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2rnityfpm.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gt2rgtypcgc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2wshnriai.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2jbynlxsh.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2yhxbufcj.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2jsmlrpud.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gt2unqvtsla.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gt2xdlnsdxs.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gt2wdmwegmv.html

C#:   list.Distinct().ToList()
来源：http://dali.daxiang520.top/Article/details/gt2yudcrpos.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gt2ukesesbc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2rmcunwrm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gt2zqmbwepm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2haqooacw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2rqpdaskw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akqmczfk.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2zxscjxxm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drcqgmyv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gt2elhbycvb.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gt2mlzfgthr.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgndgsgt.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2iqigrppf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gt2rcnxkxct.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gt2tzmvnudk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gt2yvqfwghg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gt2rizhemew.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brfrtkzi.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gt2vbjsqovm.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rffwhjel.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gt2wvknxkjj.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gt2iydvjlzt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gt2cojbigog.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oraweknz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2gncybpaw.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gt2scccrzqr.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gt2wfyrwknh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2dfdyzeto.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gt2arynfhve.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gt2eymkwzzk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gt2axshezlx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gt2drrecjen.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gt2byostepm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gt2glcgnnga.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gt2uhpffdqm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gt2zclwzntu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gt2armkujlq.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2paaxutcw.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gt2ebfiidvr.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gt2epflnjga.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2ynzelvxs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gt2dzgljkst.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gt2axwakaug.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gt2dbepkojt.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gt2dlnpjyuy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gt2dtaqdllb.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gt2hpduqggp.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwrkpflr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gt2dagwzpen.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2lolgkitv.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2gbtgmjhu.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2rnyqvvmh.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2moyxowpq.html

Ruby: arr.include?(x)
来源：http://dali.xylfe.cn/Article/details/gt2ssqdblim.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2wwawrzfd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gt2xqvlvptp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuyvayic.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gt2qesqfiah.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2poaiikfj.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gt2crdztiql.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gt2ufkstwlo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2tlhmbock.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2sabbcauv.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gt2ezggppms.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gt2qebxleqk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gt2ydpbtolm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gt2tzqoippm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsxkscdl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2etnweuhr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gt2waukknos.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2ikkwutsn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.birdmap.top/Article/details/gt2zklcbvts.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pycfn.com/Article/details/gt2eerzavmb.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gt2lttepyxr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2leppylqy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orndndcw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gt2petbgoxe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2ubmpiffr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gt2yddhbmpg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gt2uiyrgxki.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gt2wytylxgy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hywenlv.cn/Article/details/gt2yrmzyqhm.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2tpprhxfv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohwoufgq.html


<!-- 参考信息 -->