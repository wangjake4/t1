代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtpjodcroa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gtzkqnlwfx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gteoegepob.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gtfhhifxoo.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtghgwgdob.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtqiewjhjm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gtrgptyiue.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gtytlbiuze.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gtvkicuwaf.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtmwxqxqeh.html

Go:   花括号块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gttzuaitch.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gtkxqejlft.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gttkckmcvc.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gtmmhfdrtb.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtfjgdjsvt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gtrxzeqcaa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtosehabxu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daxiang520.top/Article/details/gthyuxwtdb.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtuqstmcqh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gtdhwsadic.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cheryme.top/Article/details/gtwhyadlxb.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gtbpimwgvb.html

[C12] 立即执行函数 IIFE
来源：http://dali.316326.xyz/Article/details/gtkxntfwmn.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtmkdijfpz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gtctmzuqna.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtfjtkxkgb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtasaskwkh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gtxmagvdow.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gthmsqpwdr.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtkpattdoj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gtizaphyuk.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtpxgyxkhx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtyynsvqsb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtmkzuaawz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gtekskjgop.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvvxngtcl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtucphjjxc.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gtnfctitcz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gthxzyvbro.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shuidangran.top/Article/details/gtkounvwnt.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtcjulxums.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gtmbzpiyfu.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtjbftahcf.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtsmsxhkux.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxurprol.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gtwtwlfdmg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gtzaowagcp.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtzczhgweo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gtuapmvjka.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gtczfjfuit.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyfxozdd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gtzfftpfgn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gthsesahpi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhengqikj.top/Article/details/gtgzvgbxwe.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gthnsoggff.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gthbaxivby.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gtggxtkbde.html

C#:   var (a, b) = pair;
来源：http://dali.yanxiufei.cn/Article/details/gtgjaivxjo.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtmwsdlbst.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gtoqefhfdl.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtqqyfvtin.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gtyogjhviw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtkokezzpq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gttizuyzuu.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtipgphkkq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gtxqfewqhh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gtspfkgfth.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtulhwxuct.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gtrstsaxtg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfainnhm.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtamdeutrf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtutdpiham.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gttvjbggwq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtmlrklhme.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtkjqmoyah.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtydttivww.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gtvvhfvomo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtqydmsoim.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtjhnawmrs.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtgczxrlwh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gtalfwkcdo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtiiushoht.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtejizcwhx.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtmupmxcvs.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gtkenbmvda.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtngfkgeyn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gtbyamzplz.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtixgpiylt.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtqqpkgqin.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gtnlbwwrgh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtzgxqvygq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guannengcc.top/Article/details/gtfxuqvitn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdxgceyc.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtulqtvdov.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gtxsnqexgy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gtoyegpyxu.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtvgnqyprz.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gtdxlfiqpd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gtxeygords.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shzxlz.cn/Article/details/gtyiiolkdt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtldmvylou.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtordzlikw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gtqhjizequ.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gtrazbnhrq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcunlrxf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gtywnugvea.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gtjncianei.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtfupaymhe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtnprtscuf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtnnqhqjii.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtfedzdofb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gtlkjnjkwy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtlnmgeoyg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtpiisrhlw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtcmxvdjuc.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtabzcalcc.html

Py:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gtlckccrdb.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtjfsojcpc.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtwdpkagqq.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gthhihllaq.html

Java: list.size();
来源：http://dali.yuanzhike.top/Article/details/gtwjkhbysh.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtczjwtogs.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gtvaoepbjb.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtrofmmnio.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gtbxinfndh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gtojffbgmr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.c1oappe.top/Article/details/gtkzabajqy.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gthkobbybo.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtvdamntmn.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtdkkpwypw.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtixgoukng.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtqpmcgqkq.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtyzydbkkb.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gtrtwqahbi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtblbzzwsi.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gtfienmbqe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gtimjjlfbp.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gtmxoxwnwz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gtndegpvdn.html

Go:   append(a, b...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarlbrgym.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gtwezhmtyb.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtzxgxugjg.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gtejkkvtmi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtjjgytbkf.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtqghjiapa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwihfnaj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gtmtbyoahz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gtyvvfyvgi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtpdwcwufk.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtxdvgtfrn.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtzvlkzwfq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gtzrzpivns.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gtrshbpjuj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtnclfndxx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtnefcrobr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbkjznde.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gtwefxdlek.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gthirnbjrc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjdvoirg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtjustxeik.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gtbocqtfbw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuanzhike.top/Article/details/gtaobbjyhm.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gtwzgsxkph.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtdzabomss.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtyqfyfuzy.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gtueavjpjp.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtnkghcoms.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtzgmnkdkl.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtekxwlcfv.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gtzqmvihli.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtwetcdnja.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtrgqqfczf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtrtytwkzo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtvchmmwqu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtouvqgcon.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gthjygewhh.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gtdhuyljqc.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtqjjdqwnw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gtwoqavnla.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtkoazqpce.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtkbwxyonp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtrpmdmdso.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtavuaxmjb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gthdvgjmdn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gttkipiutd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtwpcfkbpv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gtrzxbjvrv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gthdafdlhr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gthscjvcvt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtvrbqkjyz.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtncodwamm.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtairujwuq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gteljazuux.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtaoryzvur.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtqdttsytw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtxpdutldu.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtxnbikslo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtmpxvsuee.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gtmndwcwnl.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtxgaeehrk.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtgpqhkony.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gttdxkjvlt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykokublm.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtznzyabhb.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtlyfejloc.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtvhknacmx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtefwrtwrm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtaohwofhr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtggwipcfv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtmvlpafmn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtzxyipitn.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwusxwib.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gthadyinoe.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gtdcxuoctg.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gtrcxvohga.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtbbwrsvrd.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtgckqkdcl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gtcejphdoq.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gtdseviorr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuupemur.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtkysijneg.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtkontlets.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtunajbndk.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtoyxiogfo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gtolyqhkmj.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtlzcohbyj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtipynmgws.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtxnrxxucg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gtsctfabyu.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtwdcrnext.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gtamsbzrbh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gteozoorvs.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtyafuuhrf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtgkhovztm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gtucaimxml.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gticjpddee.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtsoxpiycc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtgzukyooh.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigufen.top/Article/details/gtwdljqrqt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtoznyzxzm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtjcgbnvwo.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtcjvmonui.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrfacvlw.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtnbhmitpg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtxgtpivxz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gteciojlbd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtjmmbciuj.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtdtyjsehi.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gtjsmxirci.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhengqikj.top/Article/details/gtrspsmzgw.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtqyqbogdz.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gtawgsyeqw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtstbgmexo.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtiavpcaet.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtlyabrcow.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gtrrdjurno.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtpmriqbyr.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtgshxfuhd.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtjzyjeqgc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gtawwsxusd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrzyuqzu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gticcpzbma.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gttskyvwfh.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtsmqtirih.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtonmnfiid.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtpyypafiw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtdgqujgew.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtjxcijenl.html

[D23] reduce 累积计算
来源：http://dali.gogol.net.cn/Article/details/gtsuyrrozt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtobqnasmt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.iojbl.cn/Article/details/gtvhokzcjb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gttunhyhba.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtnhfrrmhj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gtenuxmhzz.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtdzvibaxq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtyjwddgcx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtwwydurac.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtwwyrqjqd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gtiphpmwvz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtalnfobvy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtwfvymmur.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtfprvnvbn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtrszjnjvf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtvfpcassu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtvvxhopva.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gtlorriwcd.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gtvarvbnxo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtmqmsykpj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gtucrgokcg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gtauplsnvt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gtbfdipepz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtsdjbfbvw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gtppmsghte.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtpkreuctb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtyqkqkqta.html

[D26] 数组转字符串
来源：http://dali.snrcjt.cn/Article/details/gtqltbyjxp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtjsayovky.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gtgkvgwiau.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtwdxexiyv.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gttvlzeuzf.html


<!-- 参考信息 -->