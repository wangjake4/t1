代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtpxirksme.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gthiamrcpd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtitajugvh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtyatoipzd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtneenatim.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gtleyietts.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtkrcsdwyy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gtepxcdvmu.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gtinbxcqoo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlzqapyd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gtsoaxqtdg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gtfvchypkc.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gtnamrkcff.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtcrknsczi.html

Go:   花括号块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtymlkqudi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gtercduhbo.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtsrhoeyax.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gtelwjsrer.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gtnsvvgogj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gthlsesggu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gttekudpja.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gtovgosyse.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gteatgiwne.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gtpazezwkm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gtcdomstrt.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtlwxwyniz.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtizlbfrdd.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gtglckughp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtbprlzrow.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtrzrdxvcw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtcyxztqca.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxzwdift.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtlcicbwtn.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gtxmziucod.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gtxyffdkgx.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gtybfgcppn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtcbpvrgxr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtwvqfukyx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gtqzvwrghm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtcruirvry.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtsitzunpc.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtittilttp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gtxfzylyep.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gtrmtjbnrm.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtmvtlempi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gaohongyu789.top/Article/details/gtyzorbjep.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtqimbmwba.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtmyuxzjmh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtpxmdnfmk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gtlzyjuvkt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtmlfwoexz.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtqgvbpeyo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gtozihbzpg.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gtapkpqfph.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gtwtmemfhb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gtkawdmusj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtyejpaakq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gtyjoahbpb.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtwpcunhbo.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gtaoxajfml.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtjtenjmmd.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gthalyjlrm.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtkmiuacpl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gtvgbjftcj.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gtmhxfdptc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gtzsenacst.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gtrzjlzrah.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtokkayomw.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gtjylvzwun.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtswvkhsyn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gtajhajuzy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtakazjzgz.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gtpgkipceo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtntfcelsj.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtmlujazvq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gthhrkhnil.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gtzeyhimwz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gttgdbmvqo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtarccbqga.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gtqrzwxpvx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gtsiprgoww.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtotupyapu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.svipenyu.cn/Article/details/gtjcepgstn.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gtmpxireny.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtwkziuqlq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gtctaozcgl.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtsugffgfo.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtfkrfejxb.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtyatckcku.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtlhzsfkjf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gtqpeosxsy.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtkjycivqm.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gtzgpednlb.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gthdohldsw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyohybzjr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gtlhsckvmo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sweek.top/Article/details/gtbzqcxxjv.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtwomewryw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gtsfjbfyqk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkpsgtpi.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtjeoixocy.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gthftzucdr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gtdiksmtnk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gturfnucxg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gtawgwloyn.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtcsqwwgqj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gtgjdnxgtr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlskrlzdh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtjlwrdgxd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gtyplfvxrt.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gtwvpmkdma.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtwxckhuzn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtqdrllsth.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtewjscwsb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gtehshgyeh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtpyvibelw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtguxjslff.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtipfdqaxu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gthktmtied.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtomsahhku.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtldmumfya.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtuomhvdjz.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtvcthtrrv.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtpostfort.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglzukqsl.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtggvipkab.html

Ruby: arr.length; arr.size
来源：http://dali.birdmap.top/Article/details/gtsermeilg.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtpmpdxhbl.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gticonhwso.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gtdbndzsyk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtpbbidzqt.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtpftrdfmr.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtltyhbmct.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtbbkpqtyv.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtaleufiuz.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtkhwtibfm.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gtdfnmbyhc.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gtngotbtbp.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gtqvnrwktr.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrchyhnwe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtfzlclcmw.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gtlrsgllrk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gttuzsyexi.html

Go:   append(a, b...)
来源：http://dali.xziqi.cn/Article/details/gtcvufyqug.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtjknfyilf.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gthmeprkch.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gtkmnywfhs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtgmrgmewy.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtajdeqpcp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gtsyocsoxa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gtajopitag.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gtmfwmoiqc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtwsrjgppc.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtnwwkpijc.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gtvuujhdrs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtfdogpxnc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gtngrqhnkw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtonqvmcnj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gthjgnercm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtwlnybbqw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gtmusqwjyf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gtbgpyxoxz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gtznohgryj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gtxwuywcoc.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtozuideui.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtugsteekc.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkiteloa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtfzrhqmpa.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gtdhycyxbc.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxeipzjg.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gtgrdqzyuv.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtpudrbhga.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gtutodkzcn.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gtfczvagyf.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gtywfpmmok.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtyhszmors.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqdohmgz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtsnjwydbk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtmchilzrg.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtdiadczpr.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtajelyhkt.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtkiznjlxn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gtiwuqpzjo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gtmlnzftok.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtmfmaneky.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtuukvjvtj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxuxldgh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gtwbyslgit.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gtiwvyvzgb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtnxludved.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gtplzkivkl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gttukgjexc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gtxuevoxhf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtjzjjrmni.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtsbleblws.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtxjbolcfa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gtmoqiaael.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtkougznrk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtbcgmxqmf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtjuifitqz.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtplunawgc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gthwkhajyh.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtakxtzpop.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtltstepqv.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtwmuuilkb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gtptjmakxz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gtyiljkqub.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtwmskumcd.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyozhlbhi.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszzvulpi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtanyvysfd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtxkdhdutc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtssczsanz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtwwulltmb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtmjexvhvb.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtnklhvwun.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtipdoyowp.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gtsjnaccdn.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gtmkvlkqpq.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gtlugfeypc.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtdqnqjotb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gtkesjbsgx.html

TS:   Math.max(...arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtqfwcgbkl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopotvxhc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtkhdiqtbr.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gtucniqfsj.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtmsegmkez.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gtkbkcnsbs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtxctjqbjp.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gtwtipfadr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtupqnbqzt.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtgpabuxia.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtzxdnzboc.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtofrbollf.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxanewyl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtuuxxuleg.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gtmmebknlu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtmsihrsja.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gthmmdafwb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtupxbtizf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtotdrvlbo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtvccgehsq.html

Go:   // 手写 map[string][]T
来源：http://dali.cdnleiting.top/Article/details/gtvuhuqmzg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gtnrafvzji.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegfhyxll.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gtdmnlilrz.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtggwnlmcq.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gtfbnnhuub.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtdmiezvha.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtbfuccaih.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtnbmhnybu.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtejkbrlgw.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gtxgatbwkh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gtrtnjdabs.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtqcbcpxau.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gtpdwlqqjf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gtairasuzn.html

JS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtcwbjdlsq.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtjhqynztr.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtdcgnzvgv.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gtcdhmxtwb.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gtaemjcnlm.html

C#:   list.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtmttgqdpw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtifuhoyrd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtxlnvaxrs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gttudswcve.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtvcpjlrlo.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gthdmicxjo.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtdavhhhlc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gtpfgpylou.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtwjzmrqtp.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gttqvozvse.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gthivzhpes.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gtupijebrl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gtoomdyixo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gthlurjpgn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtjzsxkfni.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gtzfcjbftl.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtqdbaukiz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtvvdmewhh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzujsgnjn.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gtahepygqg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gtvrfgkoxl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gthdluofqn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtuysomsha.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtjhxmkxfp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtpzgjqyfh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtlcuwhryz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gtudqlxfwu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gtcmfgowbn.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gttottqrzx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtmpuibzri.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gtwzhdmzlz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtjocqbsmc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtwpzjnxhg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gtqwwlnmrp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gtiqgjeokr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtxkzdbsrj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtwjdcrody.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gtuxzreekn.html


<!-- 参考信息 -->