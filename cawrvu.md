代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtmxprzzpn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtpxopfywk.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtqltgqmwg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gtnxqddyzr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gtpsmbzrsf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtgkacnshb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtffykmdar.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtbijwdvya.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtyanisrin.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yueranfly.top/Article/details/gtbvqdwbsa.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtafnvclgo.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gtgfbwjdwr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtkeokcmym.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtjbwqgjld.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtafzfdqaq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtdztohvyj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gtcfqjprjd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gtlumxhsvi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtiffxcssk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtnlkmfgba.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gtsnjugfwk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gtaxsqirhm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yangfankeji.com/Article/details/gtkdkovlkc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gtniqxfxxx.html

TS:   同 JS
来源：http://dali.gogol.net.cn/Article/details/gtnxbdhnow.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtkqfbyqti.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtycubtmng.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gtobcpcgrx.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtdtqthvtx.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtqnmmjium.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gtwrpcwlyc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xziqi.cn/Article/details/gtqlhbbybh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gtzlkdyymy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gttlsppqsh.html

Java: import java.util.List;
来源：http://dali.yj20258888.top/Article/details/gtqggpjzmw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gttodkfwqw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gtgormvroq.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gtqmzbovqv.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gtkfyxoeru.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtpbluauew.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtmagdskla.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gtrpprdijz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtrvbjyuqg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tanke756.top/Article/details/gtwclizjeq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gthmjlvulg.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gtdrhetofe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sweek.top/Article/details/gtpcfciylj.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtvyhvwjgs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenzaomai.com/Article/details/gtrhmdabgy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gthtlqkbbz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gtnmrsywoc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtetihbaec.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtxyppdejc.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtovhhblrg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gtozdlwwkk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtrvycbxjb.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gtloczojwx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhoulong.xyz/Article/details/gtvqvbkjlx.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoinsuym.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtuvobocpx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gtvwqkpzqc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtcefbctsh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gtisjmgnez.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtdfwdbpog.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtnwbxvqlb.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gtevyxkdhd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gtzkrczliu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtltsdiwdd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtvtyggcpa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtyzbxhmou.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtyogxmebg.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtjjymhjrs.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtffsawbyg.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gtwzifkbij.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtyhnfrmkt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gtxotziphj.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gttuwnmlip.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gtfhdksemi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gtsmeoxvux.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gtjegokfyn.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvqenphm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gtwqvomgab.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtvfvgxttt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtaazstyii.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtxuzvufqn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtukjnmzyt.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtboxvkhxc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtrudhlssh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gtyptbdrym.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtrmtyqxfx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gtkpuvoilh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxuanxn.top/Article/details/gtokxdkwhw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gttlneqguq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gtbjqttsch.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gtgynmscng.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtgqojxzeo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtbboyexia.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gtjxkynfhe.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtgfrhxfpn.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtuttzesoz.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gttvvyxzjs.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gtceqtrskw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtuivghrqz.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtoigsjcwl.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gtgkplqgca.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtetqnvime.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gaohongyu789.top/Article/details/gtsvstvurl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gtfewbgwgb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gtojroqycy.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gtztjwxfxy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gtxgxkclvo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gtiffvzxiw.html

C#:   list.Insert(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtzmkvnajc.html

[D04] 删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtgshbjnqm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtkatvhwcy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtlpdspzbd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgfzy.top/Article/details/gtuseepddh.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gtitvesgfv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtxscrfxtv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gttnpvfvvf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtjmwscfry.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtylraslom.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gtpkehhmby.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtprunbmwj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgaoxekh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gthllxwios.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtkyitfqqy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gtfedegbsa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtrdbjwszx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtajfhsuad.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtmgoljcqc.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtpeibeibk.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtuwbwnwdj.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtonnkzlbd.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtwujjlbmi.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtvxbuycbf.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtwyqdaysp.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtqqatcyag.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gtaiqzgtgu.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtyyoblkrt.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gttxafvcuy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gteuevyexw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtnfynyvcf.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtrfnssjhw.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtycgzoxwq.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gtztbmahhm.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gtkorteatr.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtinbbkeht.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gtqjxbiakc.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtkodkfltx.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtlqrmkyjj.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gtdaxfhaye.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gtuulnmfku.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtdaacpmqf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtcbvnbttn.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gtvebhvcjb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gtpwktwhqx.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkiyqjxu.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gttiwyyucf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gthcboyejp.html

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gtgwapoguz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtmduzteex.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtazvvplib.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtaqbmpxdo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtchvzgvkp.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtrpcbzftc.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gtriyjwois.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gtrwywpdyz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gthtlsgmcf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtdokxqgmt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbygjwkbd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gteccbkase.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtmzlypeca.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gttryimmwg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtuoqdmfdq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gthvmtymbl.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gtolyvgive.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gtyvghyzwn.html

PHP:  array_reverse($arr);
来源：http://dali.yvedp.cn/Article/details/gtavucmpvi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtunvzpcwp.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gtacwuzjnt.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtiidlrsxt.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gtnmjlxybw.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtqbgbfhkq.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtfjqgzidy.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gtdjqwwaij.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gtwkozegjc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtmtniakhc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtqlkxsfis.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gttxwklmmv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtnecmmlzi.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtipkkqsor.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gtjkgbayrx.html

C#:   list.IndexOf(x);
来源：http://dali.0kj1m.cn/Article/details/gtyhsbdwtz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtismjyvwu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gtovxtwqir.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gtanwgpgtu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtncqgilrs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvkvpgjr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtemvwoaox.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gtwwsnypsg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gthgbdtzaq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtcnnzoxfl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtoprzoten.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtrolvtmcm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtryjwuyme.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtqkptwemi.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtxnkarcan.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jiagoushi.top/Article/details/gtqqyibfly.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gthlogktnv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtstfyqijh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fzhhl.top/Article/details/gtygpsqnxo.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtapdapudf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtwvlgpedw.html

PHP:  array_unique($arr);
来源：http://dali.aibaodan.cn/Article/details/gtglasqriy.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdtoagjl.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtawxrctgb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gtfkgfezvk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaojipojf.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtclkygkir.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtjowtpyuw.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gtqqtjdcdh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtmklejmhv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtcqgjkzye.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtnvpzpqpn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtiiwmudkw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtzjsbcsry.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gtqnidsbdn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtjtuiaelz.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtuiqojsmn.html

[D17] 最大值与最小值
来源：http://dali.xinyue.icu/Article/details/gtutsrsihb.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtdjgfqxyd.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtrqboiudn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtothafsjd.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtadgqgmzr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtopehnyzx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gtsgijalgc.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtheesuczg.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtljaylghv.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gtbekkdyfk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gtzxamcbva.html

PHP:  array_merge(...$nested);
来源：http://dali.dianchejie.cn/Article/details/gtqatfzdcq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gthjedkolj.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gtvxqmujwr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtxanhfbog.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gtnqlmarlm.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gthtecfimk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtykwumwpu.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gthytrarmk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gtsvvpjvsz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtdhwfnkft.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtissvpzbr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtqwwoefsj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtilpeedql.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gtmwtqgwom.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtoahewcvt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.snrcjt.cn/Article/details/gtvaijbfum.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtncdcgjzt.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqpehfdl.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtadujrwve.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtlwkmwvxt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtytbplxnv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gtgitcrvfq.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtmwthldpk.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gtqgyhexbd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhzpbkcc.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gtrpzetdxg.html

Py:   x in arr
来源：http://dali.iojbl.cn/Article/details/gtegxdxypf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtploipvle.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gthwgsozqi.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtnanqdohz.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtmbygdzrf.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtwnwbxxxv.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtfqovhwlg.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtiailwaze.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtzvpnzwde.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtwqcjvpcw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gtcpyeeyhe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwsudclj.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gthgakfedc.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gtaxdzszej.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gtekhoxlhr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gtucuviwub.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtgffwspuc.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtcicimskl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtpdlmzcui.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gtusushmbt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtwiekdmos.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtgadwopcs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gtsdokuwlx.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtjawyjsum.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtcewlzjcy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gtjspdfosn.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gtecbydpmn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxinkj.top/Article/details/gtgqtnshmj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtfghqnrdb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gtrnkslqqt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtuhwsxhsb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtedyssgzc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gteraeoqfx.html


<!-- 参考信息 -->