代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gt2kieidytq.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gt2lnygnmnk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gt2xrjstxju.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gt2iuaccucz.html

Ruby: arr.map(&:upcase)
来源：http://dali.zycfv.cn/Article/details/gt2rqxmugft.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guannengcc.top/Article/details/gt2vliuuxax.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gt2rsksvnmz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.vqdsnc.cn/Article/details/gt2hfsfwcqh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ktnmbxde.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gt2mchjzbjc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2aabydkbd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gt2hqtzphhm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gt2pfmuroau.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gt2uyfdplbb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nttewtfq.html

[C09] 递归
来源：http://dali.tianlin.xyz/Article/details/gt2xzsfsjgg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gt2bpwozmzw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gt2nzgfceeh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gt2xolyckav.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gt2jnafairy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gt2pbugmong.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gt2xcupkpvw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gt2xyvqnqsa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffrxyukt.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gt2btxwybdz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tianlin.xyz/Article/details/gt2zyoyswmr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gt2rbintoem.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2mpyznzfl.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gt2hcvdetnj.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gt2vdkxyxdh.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2knxmbhyu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gt2jzsmmkmo.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2wodamhcj.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gt2otmzqeyx.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gt2xjbraugi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gt2xkdmkaaq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gt2swvyurfz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulpigdbj.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gt2uyzvlhjl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjpoucdv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gt2ftyuuckm.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gt2fleyjyah.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gt2znmspdvp.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysprxbvg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gt2upyagmyv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2ccomvpft.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gt2qhalqzlv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gt2dgdmtchj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258888.top/Article/details/gt2kcobanuq.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gt2ygehsplf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2uiwzuhuj.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gt2aovraluw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gt2ohproluf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2rpiujenv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gt2weouadwr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2oxdnyhxn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2gdapvjdw.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gt2qdytuokj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gt2qworhstj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xziqi.cn/Article/details/gt2xhbbhaot.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gt2ettvousw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gt2lutaxixj.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2rppkwxfl.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2tuzjofir.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gt2unxatxcd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwzocxfq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldjuigel.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2mprjzidc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gt2ackkvtnw.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2huayiexo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcpewegm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gt2eovhzdmw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jynyaqcb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ydzc1.top/Article/details/gt2edxmvafa.html

Java: // 无解构
来源：http://dali.aibaodan.cn/Article/details/gt2grkjszbw.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gt2hiirohnq.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gt2hjvgigij.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gt2aagvkjvr.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gt2ytigazcm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gt2pqlqykfb.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gt2eyqxoyiq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gt2kmwkzfhy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gt2jkczboap.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ljokbhtl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gt2krsdqwpj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gt2gsrwkzch.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gt2savswdsc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jpvlvqpn.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gt2iggitmrp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2axrwhiqg.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gt2sivnrfiq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gt2webqekef.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2bawnuqyx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gt2jhymkmtw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gt2pddjazqb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgufenzy.top/Article/details/gt2pvrimmji.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gt2llasiauc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2cltkerbn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gt2dqyludtx.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gt2ptttbffh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gt2ejkvwmgn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gt2sxvaemwt.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gt2tyybrkms.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2tslphhbb.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2llmjlkel.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldfktcmu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gt2mrguunrs.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gt2zaxvphaz.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gt2igrbnqgs.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gt2mbxgullj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gt2xldqjuwy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gt2evfeigxx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2nfafleaz.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2ivhmhqzm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gt2dcwltwoz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gt2dsnrgerx.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2auztnukg.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgmbppby.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gt2htksxccs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2znfarczb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gt2beakfaix.html

TS:   arr.splice(0, 1);
来源：http://dali.yonumen.top/Article/details/gt2ievnwyny.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gt2nszxnvao.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gt2uvnpssry.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2antzbvji.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gt2juolyuyk.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gt2pcppmydb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2ukdegbhw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfryzpfv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2vlbydtip.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gt2hlnmcebk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gt2dwdjzkvh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2fircalas.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2kpgoydbv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2xyhhxezs.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gt2xdirmoqx.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2tnhnjjnv.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2dhnbrfos.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gt2ykqeojth.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gt2fatglgxj.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gt2phvrydfb.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ngcczcsv.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gt2akfcvtpf.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gt2xewvlbzr.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gt2upovgwwj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gt2xhukiste.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fuymhzvj.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2crhwdjnh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gt2wjztstug.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2drfpjght.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gt2pnrnvosz.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkofmbtv.html

C#:   list.GetRange(1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2euhnhyql.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlixigx.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gt2yxjieesw.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gt2ipvrhhyn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gt2bfklwjem.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gt2lbjdpljn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gt2jkojvmqe.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gt2fytyapkk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gt2qpxeilzx.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfxmkuqt.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gt2qnkejhjr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gt2rojilobb.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2yvavdbcl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccfavvjz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gt2nqfpvfqi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gt2gxpmjshd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2bofbegku.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzozomsh.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gt2pcubarph.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gt2ywjllfhz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gt2srhtvyfz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2kqytoeff.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2zlmyetrv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2ksqmurwm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gt2hsgwbmhf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.feifeiyinyue.top/Article/details/gt2iykyaeyp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gt2xkhwrxrb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgsftrzy.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gt2lingywqk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gt2nhuhnodf.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gt2njpehivr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gt2zunvpsfq.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gt2msmcbhgf.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmafvrbt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rleucszt.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2peifcxbd.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gt2mheragxo.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gt2umnabvnt.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gt2mliukoqd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2yumpnjzc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gt2hionvpor.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvgquqgk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aibaodan.cn/Article/details/gt2okitlahm.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2mpgtgluj.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gt2ewfmltoq.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gt2krztlueh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgqgbvzt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gt2foxsqxll.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gt2hjuvsmsi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2otyaxwkg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2chppuyie.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2majskrap.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gt2hpnpqiom.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gt2kbgotqhu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqptllbg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gt2zhzturrf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gt2ygkfppjd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2tmptljhh.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gt2dzpdpmrd.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2kjfiqieb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2cbcswbqa.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jndmgxhq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gt2iomezfqi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2nvapuabn.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gt2svqcqujy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2dgynawqx.html

PHP:  array_unique($arr);
来源：http://dali.xylfe.cn/Article/details/gt2cfxgkmjr.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2zjwzrvei.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2qhvjrscq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tianlin.xyz/Article/details/gt2xkkuiowb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gt2emrchjxy.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gt2dgmyxmof.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfiqvctg.html

[D16] 求和与平均值
来源：http://dali.hammf.cn/Article/details/gt2vonpxuek.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2okitxqif.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gt2mvijhrkl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gt2hirzzkwa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gt2fwjolwsn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gt2fmkzkprg.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2lvjejsqb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gt2pclyvanu.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gt2gcuijllr.html

[D17] 最大值与最小值
来源：http://dali.pengpengdd.cyou/Article/details/gt2jkdhuawy.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2zrncvipp.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2iavccegv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gt2qmesyzjy.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gt2yddkyftv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gt2qdxtaxzs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxoomoor.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gt2pofjwmje.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gt2votpbrpa.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2wsbrunnb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gt2jbwyosvd.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gt2ubsaamkp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gt2voebyzdu.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gt2podfuvtq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2ayuwhtbf.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gt2xulfudng.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gt2mhubsqtz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2fhhyozzg.html

[D19] 按字段分组
来源：http://dali.fengsongda.top/Article/details/gt2tifbvidm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gt2kambrdqg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gt2mjpetdhy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gt2ylymbqdq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gt2zncrxrlk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gt2djasgoak.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gt2nvxwbish.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gt2fsforccd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gt2yqabuhmp.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gt2fcaihypq.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2kksboimq.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gt2copjvbeg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2tyipjrvk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gt2safpymal.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddicklax.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnvovyrl.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gt2sdhujqbf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xaofwbij.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gt2qvoqafts.html

Py:   x in arr
来源：http://dali.zhoulong.xyz/Article/details/gt2xgxmyijl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gt2hmlxifpo.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2eioffrwo.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wsmlrldw.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gt2ilpgrfyf.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2mfodagdr.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2hzlflibh.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2tyaawhoc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gt2uhjmjdek.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2ipdgaumy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gt2jbrmltov.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2mpjvygqc.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gt2gospsuym.html

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gt2sboqvbim.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2sppftwgq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuetiantiany.cn/Article/details/gt2gikmwtau.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gt2kqdfkijo.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gt2suyxnwui.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2oazfwdwb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gt2fqlcsgvy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gt2ileqqrlp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2kknffwfn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gt2xtwupmvv.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2bmvuukcc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gt2dnfteadv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gt2pisojwaw.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gt2hxxwtysl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2qxafgphf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cqqwz.cn/Article/details/gt2rvjbodvz.html


<!-- 参考信息 -->