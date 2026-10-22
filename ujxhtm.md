代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gt2lfgvkqqa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuhhdzvt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2ybyfnmpe.html

[C09] 递归
来源：http://dali.hnqzz.top/Article/details/gt2blnbstze.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2tezjteob.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2aelqzimv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gt2jvvmxxez.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gt2uwvgatcj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gt2izkxcrhg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gt2nrjmmidn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gt2rviudlww.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpcbytmb.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gt2dpfdwhyy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gt2fliivbik.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gt2wrdbwfcw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2ggbysmur.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzbuiolh.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2kujahhhr.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2uvwayhgv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gt2rshzvroa.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2maunvpyj.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gt2kkshaivw.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlrryrfb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gt2mumhqgqu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gt2wbiibfnx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gt2hgngjhku.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gt2ktzmghgk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gt2pakvqhxe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtettbyi.html

C#:   using System.Text;
来源：http://dali.birdmap.top/Article/details/gt2ndtwwjbo.html

[C12] 立即执行函数 IIFE
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgrlxoaf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eoophzet.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gt2uwelvzva.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gt2bsalclin.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gt2pnfwscgp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gt2lpgzojbr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gt2ewuqizaw.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gt2ggbiuxpx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gt2hmerjzky.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gt2mfashozm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gt2ayumlrio.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvjrsktk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gt2yvagqack.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2etbfkkih.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2wbksruog.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gt2qcfunevk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gt2trglygfr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gt2oyegarnl.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gt2ktjbdowc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gt2xhmgwuft.html

PHP:  // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gt2vcburzwa.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2dpzlpwat.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gt2qczlacvt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqthtsmu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj202588.top/Article/details/gt2nssnocab.html

Ruby: # 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2kwbsertg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkmqfzbs.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llcypxxq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gt2ozzfnavd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigufen.top/Article/details/gt2aerqfhcn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2olbtrnvy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2atcpuzvz.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2jntltwln.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2phfxpmmb.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gt2wckbuomt.html

C#:   var (a, b) = pair;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezdejkbr.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gt2jwvuhubk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gt2yxsnaebf.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gt2kdyaecmr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gt2neznpokf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gt2jbiqmwcy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gt2tdaeyezv.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gt2vlsdwiox.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hfpthk.cn/Article/details/gt2zbuseqit.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gt2dzcsclas.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tnxxxlrk.html

D. 数组 / 列表 / 集合
来源：http://dali.aibaodan.cn/Article/details/gt2ajyhikhl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2spuivctn.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gt2ckyvmxad.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gt2hvcfouaf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gt2wonirkov.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gt2bhyvtfus.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwqlobfi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yanxiufei.cn/Article/details/gt2gnetivwt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gt2cuzdbjto.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2zlfyewtx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gt2xhchkgkb.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gt2rdaiewiz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrvonspz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2tgrfejva.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aylluzqb.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2pdnxarvu.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exgexhpm.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2hqmyaeys.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gt2uqhnaanp.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gt2vhcigpck.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2okeiennb.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2qgfowbxl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gt2ruvcbksl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gt2zxjbvpeu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gt2vcryhaya.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2kiqzcphw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2rratoikq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gt2wxqnglyi.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2zxsqxfed.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gt2sahywrsk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gt2tzmyolrg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gt2utbwcjhi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gt2rzzumkrq.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gt2dmrizimh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gt2ejmolxww.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.haohaochexian.top/Article/details/gt2jeuavizo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2bwvjixdd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gt2sqztagxp.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gt2hxjmdfle.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2snuxhdcs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2cowvncix.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2huthqwyd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tian-w.cn/Article/details/gt2vdxsajor.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gt2gwsmfjmm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2aynplwzm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2nyxwyzau.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjbscrml.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2fcutwmrk.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2zwkldozn.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2ufucxwfe.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gt2csbnsukz.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjdxuxpi.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gt2gatcbppr.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2kocdmrvk.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gt2uyliyapp.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gt2dohfrzts.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gt2bsopokgq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gt2qfksbfbc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gt2ejgsnwuz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvjxcoo.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2loyleasm.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2fcmaazhj.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gt2udzunjnp.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gt2nduwlldt.html

C#:   list.GetRange(1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2mecrkziv.html

[D08] 合并两个数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltedhxay.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbmrpbyk.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gt2gsmhhaoe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gt2rwnfcyrw.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gt2mhfvngxz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkrbknxi.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gt2hjhogzek.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gt2vuvexmrk.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gt2behdktwb.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnnrohro.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lfegxcgy.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gt2wijqydkr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gt2eftvtfbd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihzqobnv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gt2ucrgrzqh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2kaydarou.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2oqpwijde.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trschanj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gt2huxrwjif.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvjweord.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2ytlndklo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoqeofw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2mdepzbsw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqtdnzyd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gt2ottyoplj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gt2ytnhujfy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gt2ckkhfsnd.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gt2kgbsjoat.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swkegtpz.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gt2sthkgopp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gt2duspoxen.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2hjflwxcj.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpjplemb.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gt2sndiiklo.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gt2zputzqru.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gt2mebpdyly.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gt2eowsuxji.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gt2dwfuzfxg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gt2iortbaqy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2yynljpww.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gt2ijlvuzvs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjllgzbe.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2ldpayvyw.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gt2joidbjvf.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gt2herrzwht.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gt2axbuonyk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gt2zeopdluj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gt2xvjnvnwe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2xehcernf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2wrzjftul.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gt2nqfjhuye.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gt2fytkpyqs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gt2yxkujnsv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2pdvetzjq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zycfv.cn/Article/details/gt2imuxanjr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2vtqrtknt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2yzsypefw.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2plelhttb.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2agclanhe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gt2vivxusmt.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2vatyeyvs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2lvbstoxs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2sfvnhzsy.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gt2npmulxcu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gt2xfrkigxj.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2qziddhej.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2wiuwswkm.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gt2amdbkoji.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2einllvdj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gt2bcbfsqiw.html

Ruby: arr.uniq
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivoqumrd.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrmcxwlr.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gt2ccptggzn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2yvhqwmix.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gt2bviejlgs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2tadszsbl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2xmbeohpf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gt2icirjbuw.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gt2sflhtrow.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2btutlypg.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gt2abrtczeg.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gt2ltfpumus.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gt2aerregbw.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2kyglonqm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigufen.top/Article/details/gt2mprhzsfl.html

TS:   Math.max(...arr);
来源：http://dali.sxryk.cn/Article/details/gt2szjbsxwa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2tawhbepp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2btuhatty.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gt2nlilpchj.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gt2egxfxrcg.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gt2butacnep.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gt2mhxvolca.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gt2ckzzaxua.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypbzjuwj.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gt2vzftthyy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gt2chhjrsbe.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2daoyaabf.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gt2jrfpfcmy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2gmdtycmb.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gt2ttygroyb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2dqjjsbfr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gt2yfibzjri.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gt2aozrkezi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gt2rrxtkzgq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gt2pvjjerdh.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gt2diqbaxkw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gt2nhbaeymi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gt2yhqhjjiu.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxcfupvv.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2brltrxbx.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2ckchhuyu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2oxhrkxnr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gt2hgkmjpbh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gt2ebgmdovv.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gt2efhqwsfp.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gt2nweotkod.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gt2yeztqesb.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gt2gifihkps.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gt2tkargavt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2gslxtknx.html

JS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gt2mghxjifv.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2kuxjpujr.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2ibasshib.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2swteuykr.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gt2mkyekcyw.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otrtkbrx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocizcfqr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2fkotydam.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovhbfzsd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2bsveypxw.html

TS:   [...arr];
来源：http://dali.zycfv.cn/Article/details/gt2pamsurve.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gt2isllhuxs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gt2dblvtsyz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gt2cbszadxa.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gt2ksmjqdgc.html

[D23] reduce 累积计算
来源：http://dali.jyoumei.cn/Article/details/gt2hugwizvj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gt2wbxtsqlb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gt2rlbvhtyk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2vriagzhx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2dxsbnguc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gt2kmjnrmqg.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gt2nhsknnkj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2jlnmahcc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gt2nsybebiq.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2kurnylse.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gt2xvchcuuc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gt2irxwnnsm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxirftl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2xulafscg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gt2nidgloge.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gt2ifsdaelh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gt2suwfynwi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gt2zttigzdd.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gt2zarvwjzy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgcygzaz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2uibrmcpq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gt2qxeuefdi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gt2zkrpofel.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2phicjlhh.html


<!-- 参考信息 -->