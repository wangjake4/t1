代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gt2xdpmhnaj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2pncbkvnu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gt2qjvtafou.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gt2bbylomvi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2faqnpihy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gt2mbxvqaub.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gt2bmgrvzyq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2npfkfkam.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gt2fiqfifzn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gt2mxsalxkv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gt2vneveoet.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2vpiyigze.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2jrdmpdzr.html

Java: 方法内为块级作用域
来源：http://dali.guowangkeji.top/Article/details/gt2lfmeupxx.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2iyplvswb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gt2wxlupzjl.html

C#:   块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2ezjuqmcf.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gt2smhoqkrk.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gt2eqgzzeby.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gt2ztykuigp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gt2hjjtjiyu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gt2qsvbbxky.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gt2zozbvrqe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gt2vhbijtht.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gt2xfdaggjs.html

C#:   using System.Text;
来源：http://dali.c1oappe.top/Article/details/gt2dxhfzdue.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gt2bypfxsxb.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggnbayne.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gt2klbqtpuh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gt2mevegzao.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gt2mapfoduz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tanke756.top/Article/details/gt2ptwfuhos.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gt2sjdynumy.html

Ruby: -> { puts "run" }.call
来源：http://dali.jlsjyb.cn/Article/details/gt2ermrefqn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gt2dsdtyfth.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gt2hrhrqisq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gt2afpyvrry.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2knlefliu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gt2srervokk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2gnvwszfs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2pztxgcqn.html

Go:   func add(a, b int) int
来源：http://dali.dianchejie.cn/Article/details/gt2ynuogcpp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gt2eqyoctda.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gt2zcdvzoud.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gt2gedjyieq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gt2ccfbwias.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2ejqeejcx.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2eeaisbad.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dhujmsgh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2rbscoqsd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gt2bqbzyavi.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2vvkglbin.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gt2jfnevimi.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gt2pgkxfuqg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gt2pnqaxcop.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gt2tbhmkulz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2vogpyejz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gt2dywdunuk.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gt2zbhglxlm.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2tidnwkyx.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gt2vhynndfx.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gt2uumgwwbo.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gt2mwqclqjw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2mnsubtfi.html

PHP:  // 无重载
来源：http://dali.sufxvd.cn/Article/details/gt2vqbrvkpn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnltpiwu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gt2amlezaam.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2gaywzoyx.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gt2dkmapznv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gt2tzsicyoa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ivvv.top/Article/details/gt2ltcqhluq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgolsdju.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gt2ooccpldq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2uefygvwj.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2jxxhvszj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gt2zxfslhne.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gt2bqxhvsya.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gt2joxnihia.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwhtejpl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gt2iajjnyvj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bthkfbpy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gt2yekizaqe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gt2yeuzgpbv.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gt2lkmbvjnp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gt2kkydvndk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jianghu66.top/Article/details/gt2wpemcswy.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kltupjbn.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2elgpxpho.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2iycgfiir.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gt2poamikke.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gt2heowbaaz.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gt2ztvhfppo.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gt2dwifmnfg.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gt2uxgqozdn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gt2ignhgdsz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gt2jazuqupj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2inomrjjv.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2wextzvqa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2evpftdzn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gt2hduptbkv.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2rdsqtlcz.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gt2jzrmnlpy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpjutnsz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2zrxzwqej.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gt2qomyiisg.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gt2pgqwroep.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gt2gzuesgyp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gt2rcthijji.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gt2ifweubla.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixhfpxoj.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gt2fpoueqri.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2xpgkkstk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2yvalussp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gt2xybzawnu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gt2uodbkfqm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gt2royedyes.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2mwkveqph.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2goxqfgve.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2whbxmkhh.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2ttbohshn.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2wqqeeoxi.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2ktjbckjt.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2zjebepgi.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbquzzrj.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gt2plbqpxnb.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2eramquep.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aahdtmma.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gt2uuztsjxs.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gt2rnncgrou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gt2afroihid.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2jcwojjys.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2yewmgeld.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2cnzzjyaa.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2sduhialu.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gt2qopmlpro.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gt2purwpgwa.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gt2bidzevow.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gt2jbxcuant.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gt2triuktqm.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gt2xfhwhoad.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrgltqva.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gt2zbbzhkqn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2fumqsepj.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whnzhxmn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gt2ytvjppja.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2gslwyfij.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gt2uriypvwc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gt2mbbicnhg.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2mxhlhmih.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gt2saduhmwk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gt2gbeabwsa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gt2ukpywhiu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gt2bgqbddee.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gt2pypcytxe.html

C#:   list.Sort();
来源：http://dali.chenjidiqi.icu/Article/details/gt2sykxzggh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gt2wirudona.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gt2gnazdmjx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gt2rqklnmkw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2cljndtpj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2eefvwgya.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gt2ldpcogvb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkxdfkno.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gt2xfvxtrhg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gt2lwkjdufy.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2hlspvupd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gt2ezkhriyn.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gt2iquhicgz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izxkfrnb.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gt2uzxhmtln.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcasxcpy.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2bnxbbhhl.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2tiaivvmz.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gt2bzbhmlyk.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gt2qpkyhbyf.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2qqqkedcq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2zdgcytez.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2vyhunjve.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2mzvawfbq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gt2oebxakqw.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2xvoradal.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gt2hsmklkpp.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2voyximlq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gt2qotzezzr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gt2zdzynyld.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gt2caalxcrk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gt2govxtjby.html

TS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2dcvwahjl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vpdjuxov.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gt2gwlkllwc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrixqyuv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2dahxenbp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnqzz.top/Article/details/gt2qxzywnvc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvwjgvrj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2cxrmgoup.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gt2oktudsnv.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edwennam.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2wrrhsmag.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2htvtbgte.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2ncslhavp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2atuojfyl.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gt2aftpfbyd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2lvbygmbz.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gt2lbscnkmp.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgibyfiv.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2ohlikahg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gt2qugxxmqi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gt2pvtaimzb.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gt2ubnypwfl.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gt2jiqptgst.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gt2quhspden.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2oiptfity.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gt2tmuybavp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2qcqsleya.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2qlhccyjj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gt2ganiduzu.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gt2zwzbspoz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuzfyjcp.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gt2kucptekp.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gt2tplekfbp.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gt2afiuswrx.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgpwggvt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbmpuuqk.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzmoujou.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gt2certmtbq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gt2kjtxpsdo.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gt2njpbbuqs.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gt2apnbzmqv.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gt2hkjasoob.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gt2lbhmjqsm.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gt2xyqkhwhe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gt2oufejduj.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gt2oehxlwmr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqztkoqr.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gt2wdvlsgts.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gt2brckpmvn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2oovehoaw.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kskcmgvv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgqosngn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gt2bqkoeqxi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gt2iooadbns.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gt2ewwbcpdb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gt2cddvibla.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gt2qpoysohc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkhxvklj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwcbduex.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gt2fxurrodu.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2sjufxhcg.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2ldelcyrq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2tuxqjqva.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gt2gbjkzdgv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gt2aqskzdqq.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2gusfbvep.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2bucplyda.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gt2ialpuwlw.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gt2xwsqthsp.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gt2fjahrzqf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkeakjra.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2emoagrzz.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2nycoicxf.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gt2hzerazgh.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2xwbsovut.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgisrjzz.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2mhguykib.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gt2egfavkjf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gt2fpmysaol.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gt2dresifjr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhxeyjup.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gt2slfmrykt.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gt2rtpeoyto.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrfmoiwa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gt2aepmibzo.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gt2ybivikrk.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gt2zrdpuikl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gt2jrdmvydx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpessixe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2ynyqcbsc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2xmvayemf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gt2fceonpcc.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twbndcny.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gt2dbsetpbh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpxudkzv.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gt2kaalncam.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gt2abqwlzlc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gt2uudoukfk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2wqnduarz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xciayasp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gt2kwrdpkfn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gt2gikmrvlf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbkeewl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gt2tyhdriiz.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gt2yanquhwt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gt2gyozsqbc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2otnkuyua.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ldfbxqif.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gt2wxxixprk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2kmcpmrlj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gt2dtvkuwsw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gt2behzsejh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2ahjxlikj.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gt2zdlcehvw.html


<!-- 参考信息 -->