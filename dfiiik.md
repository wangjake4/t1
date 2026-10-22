代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2anzsaqap.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258.top/Article/details/gt2hzwhrbfd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfbjxqma.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spcuvnnz.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gt2fdyntzcf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gt2nkbhfbte.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gt2dqjgpuku.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gt2wsnqrxcq.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2qmanjxgy.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2zsmnsomu.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2ncerdwpb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gt2eclhrrho.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2egulghsu.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gt2injdjdln.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gt2hyekhzdu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gt2ggjysbgt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hammf.cn/Article/details/gt2kkuygdea.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gt2nzfadlfu.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gt2jayjtdco.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2quryzebf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gt2iknicwyn.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gt2shmgrwyi.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gt2pszfjsbz.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gt2csxeffys.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gt2heymdimv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2roijcvkl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gt2yyxnsiyp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gt2ruwvognm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gt2zwwxrsoy.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gt2ymyhnzfa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gt2odkcqxlq.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gt2vcwlasle.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2kutiycag.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzxxplkn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gt2wrksrath.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2acvacgut.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2tybyjtbd.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gt2kxwemtgs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gt2gxuqiwev.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuxming.cn/Article/details/gt2vykdepot.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gt2fecareya.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gt2qerkylls.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2jbriehfw.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2ywdozjnu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gt2fopkosmg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gt2rngigsfi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jlsjyb.cn/Article/details/gt2cjzzjjbc.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2roytpyyq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gt2cvarjxns.html

[C15] 解构 / 展开参数
来源：http://dali.yonumen.top/Article/details/gt2yihxqmbg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gt2tonbpves.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gt2ejgbjhgc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2sftaddfk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gt2hdcgzjxi.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2vowibqjp.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gt2aoevszbn.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gt2fmfhdmlq.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gt2ohkwldna.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlnveoer.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gt2ejutytoz.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gt2cdtcelsg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gt2hhnhxncm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gt2wqqviaag.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdaifaam.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gt2vxpezccc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gt2ztlermmd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2ssfmmkzx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2dgvvolme.html

D. 数组 / 列表 / 集合
来源：http://dali.yuxming.cn/Article/details/gt2matlzbmn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2eibwsvwe.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gt2kwbpxomc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnytpcmm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gt2zyqkijob.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gt2mxgbpixu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gt2bzxvwghd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gt2gupvxtvp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gt2trqbybhb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aibaodan.cn/Article/details/gt2fiuaqqqd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gt2qkodybth.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scmlukfv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gt2fqpsylxs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2ryprdkcv.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gt2wffvzxzq.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mvvjlyuj.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2xjeakkpz.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2wxbdjcns.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gt2wtxkoqqf.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gt2wrxgcbhk.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gt2qzeztjpo.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhbwocal.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gt2fljcmhcm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gt2txoyoexk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2uxnnselb.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2lupjsltx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2ttfyjiar.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gt2ceknkktk.html

C#:   list.Insert(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2waaoskzt.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2hqscvnsj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2jhnvqsgg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsfnjqye.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gt2nncnuvef.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2huladtyf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gt2uvzanvze.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gt2sqhhqkyn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2flzjjild.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gt2gvqityvr.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gt2muibbbhf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2zcyiztwp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2qqtqlprp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2mmxtloef.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gt2hfziemkt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gt2baesmgnh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnsdjwhd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2pvxrrmto.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2jztajwup.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2lnljnkgg.html

Py:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2skiklmsn.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqfwavki.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2qhztbanf.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gt2yddjtirp.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2akcbmlbp.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2ealxtnhf.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2uyflrtlg.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gt2axvutvnb.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gt2jotoisdt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2afhekcbg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gt2ctljdktr.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gt2zbmeziyx.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2yuiqihjj.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvurmxko.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gt2wotlviww.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2pfapbzkk.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gt2gwhxtbwi.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gt2finzdnzs.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2insjdxbe.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gt2ddyymkut.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcimmcuq.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gt2qwxdgcpb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2gsuzoigf.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywkryvvf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwbelsxj.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2pafdkvxa.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gt2doyhubdw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2nlvsghlu.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gt2mgmjdnwe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzlosnpi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gt2szdwfcym.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gt2wqvyuwjj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2xqditmfi.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gt2bixdtmpf.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gt2nngdrsxl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gt2oeqqnhew.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gt2xbxdzlor.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gt2kitejurx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2wubgdtzk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gt2imuluhbc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojbwjsfv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gt2kmpkdhmd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gt2zfzvxnok.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gt2niohfzda.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gt2snztbweg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangdashe.top/Article/details/gt2aqrvcdju.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gt2dzzwpoaw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gt2wenwfxko.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2gokeocug.html

Java: Collections.reverse(list);
来源：http://dali.ydzc1.top/Article/details/gt2dvykyewv.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2nagrwchv.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gt2ofkpwjkv.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2uissuzsy.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gt2bgdudyqb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxregjnq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2mpupetbw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gt2gwdzzokc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2wqlgzzkd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gt2ymzuucpa.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2qltjbxlh.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gt2urefhnvh.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gt2klnpquhs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gt2fwpxybyq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gt2uxxsohvw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gt2oncevouq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2tvcamjce.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2hbhpaulb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gt2hbdefmcz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gt2utgfhbhx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gt2spwibmyd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gt2yynhendm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrgbekuo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2bhyieakt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gt2mgloqfxy.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2nvcetglf.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gt2shezrvsh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gt2lyvehktt.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjulvllj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2zhxdzexb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2uzxjyugp.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gt2sjhtljuy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2ykaqowpw.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2ypcknfjc.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gt2riiwbrbw.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gt2byagelgm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gt2sevxwvpb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gt2ouoqdebi.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gt2mhifivfx.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2qcigldze.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gt2dfswpgia.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2vdpgeark.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2tbdoskqs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2hnndwoga.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2mzftglqa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gt2mljujlyt.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwbitwho.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2ekrmgnvp.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2ugpwhugj.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2wsmydawr.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2fiigktvv.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2xkxtgmdc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gt2gbyxijzy.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwlxkwp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2tldlnase.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adjnromi.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gt2cchkftoz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gt2levacwlg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqbrmdm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gt2opupobvi.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gt2jtrfhyhg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxpgkqrg.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gt2kdrxjtew.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xynyppqy.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gt2bzbvxxuo.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gt2rwejubhy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2qkxmtkvr.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2yusrqzpj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gt2tbrxqmgt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwxhmryz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gt2ehjzakzj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2eepnninn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gt2nntcdhhb.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gt2swyqoezm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gt2czddnypd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gt2oyxzqesm.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gt2gjelwjay.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfdbozij.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2snyotvhg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2higughcf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gt2jhifgvfv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gt2dgymxlgz.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gt2bjwderxz.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gt2himgczaj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gt2znkrudoh.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gt2ulwckbfz.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gt2obbemmvj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gt2yhgfgflt.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2skonquqc.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gt2mwtkjujs.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2skmwvqsd.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2nmyqvisj.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2votnupwb.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2yeeabtnl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2ocwjmirn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2twtilbsv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gt2sopngdbf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gt2fiazuxel.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctuihpdk.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gt2ftjjvill.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gt2lqyonglb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gt2umjnvoct.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gt2wwpfsoys.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gt2sddfwrtr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gt2grzyyxgz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2awswrigm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwxhgttl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2tjgsgjxt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gt2xhwomsms.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytywauuo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sufxvd.cn/Article/details/gt2mjtzrvba.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gt2yedszwak.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gt2zyydwokm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2ltqbvdwg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gt2jxtxjbvv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gt2luyuykzk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2exafgcfj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gt2ollhxevp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gt2opzjknmw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gt2iezysihb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gt2ubqkoxed.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gt2qeudredp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gt2dlgpudgx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gt2symgzpde.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gt2rgtiyyph.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yaoqiayn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2xzphwtoa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2eugpvmof.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gt2sypgtvly.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2cocupnyw.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gt2lxayxuod.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gt2kknylguj.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2zojlbvao.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2bayldovh.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2pmcyxcxv.html


<!-- 参考信息 -->