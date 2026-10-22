代发 wailian999

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gt2xpereytm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gt2fkibwqnx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gt2elcykwrg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2vdxjovbn.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2cmbshdjz.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2ihqjugrx.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2dhkbevuw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gt2noshxacm.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2xjsceimo.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gt2fmopzknf.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjynqjsk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gt2chqjflgq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gt2ytfxxady.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gt2lyegsesl.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gt2nqcmtrie.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gt2vqswiyak.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gt2klnlhatb.html

C#:   using System.Text;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbguomhn.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gt2xhidsndw.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgfzy.top/Article/details/gt2pvsafhfs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gt2zlgcskme.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gt2lngtqqjn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gt2dtbgqitm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gt2ckvcsxgh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gt2ntvfrtsr.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxjkzclq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gt2kxdoqthi.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gt2mltgqzrv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2hoihyack.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccxtrlkm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gt2jbiccmqa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2mddgpneu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyegaltp.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcaqxuib.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gt2xomyeqhm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsdnlruk.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ajoalpvu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gt2xmtzysfn.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gt2vbiinrup.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2dgkxoomr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdpuptng.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2azoenzwf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gt2xsacbbot.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gt2xafljgoj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gt2jlxzcxjo.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gt2aygyhdvi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gt2sgcyyrbu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gt2lmixhcha.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzzaakhn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2pyyjzmhd.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gt2gimcxxlu.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2tppffpgt.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivszdzkd.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gt2rapcssoa.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gt2zofoeasi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gt2fuytkgjw.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gt2mfjferbu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gt2xjznczpa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gt2kshuspaz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gt2jmzbdnfa.html

Go:   // 无重载：用不同函数名
来源：http://dali.jlsjyb.cn/Article/details/gt2xtbnlppr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gt2igawxwql.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2supqdrto.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2bkfunhdz.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gt2fqzyxmjh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2gbdztobl.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gt2xjnmzojr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gt2ljgobxsh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.redwolf501.top/Article/details/gt2pnlisllk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gt2xjcgsowh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gt2wecactvw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gt2sxujmyba.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gt2locsgceu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gt2tfosmjlc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gt2bvwtlpum.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gt2dsziilej.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gt2lhxnarkv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gt2myommujv.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2wjadbecq.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2kvtpbokb.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gt2gxhmfcjs.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2wvzuanbv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gt2qhxiovui.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xabrcwzh.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gt2pkmuefih.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2ucbgntpz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigfzy.top/Article/details/gt2wdgfldwj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gt2visahrcn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqpfalwp.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2qqjftyhc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2egneqgxu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gt2szhavxns.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2irmdlumy.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gt2wbmxzqjx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gt2hpfvvwqg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2edttfhej.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gt2lmxwyskm.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gt2wynatisg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nntbkumq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gt2linwopix.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2cqfyvazs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gt2gxmxeyhf.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gt2zqzjyijz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2yqvfpjun.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2ognbxclk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2tnlcnegf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gt2zhoeeglo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gt2oicmwkwj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2gumtibtg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2nrdgyusf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2ufbqjjae.html

[D06] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2weywqlhk.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2hnddjksm.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2mpawlphy.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2sljptucv.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2uilwfyek.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gt2ecosequj.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2msntbehy.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gt2ydzbkzxh.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gt2vkzyosvy.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gt2ojtngckb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gt2hlldvtlz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzjvcxbm.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okomfqth.html

TS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2zpuhmgja.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2ekdbxvcz.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gt2qsmnrcwt.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2ilhkarre.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2kpiphrfi.html

[D08] 合并两个数组
来源：http://dali.meibo888.top/Article/details/gt2bifhkdjl.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gt2yfsgqzpx.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2faefwidk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gt2bustvpwq.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gt2vgywffsd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.mhx1999.top/Article/details/gt2ewhdtgch.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gt2htnmqnrw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gt2dsgpffpa.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2ahkgbvru.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gt2ocknfbuq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2hrnqiqow.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2xnazgcnv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gt2ocrapvlb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gt2ralvfpav.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgklevqu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gt2peztbaps.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zctmwywo.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gt2unhqggfq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gt2mcwghexg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gt2oykxgivp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gt2xlvnklfd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zodzzgps.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gt2dcafyyae.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stlrhnlq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gt2rqprwojt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gt2qotjhwmf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gt2njkhjqhe.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gt2lwnzitfr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gt2fjiwirdb.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zuceeoyl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gt2gceirxek.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2tevfdjpf.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gt2rxihrkjr.html

Go:   slices.Reverse(arr)
来源：http://dali.hammf.cn/Article/details/gt2holsxput.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2kidhljvb.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2yggcplsp.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gt2qxtszzsi.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2opjlbptf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gt2hmdrjabt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gt2kpzvejud.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gt2cvivinng.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gt2hsejfuhw.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2roneeest.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gt2dgmoynbu.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2imjgpzgs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gt2optcsofg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2uikcmdvw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gt2bmugkfrv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2htndyjxt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2brncvxhc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gt2akjgoblo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpaacxlq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzekoqhk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2sbrjqswk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gt2bicywmvo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2vixyynoe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2hawtikjd.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gt2stwpblck.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2ovrykcaf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gt2kuigltzx.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2uyimgwvn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iindcfca.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2breqvaoo.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2kvkiouht.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2tpuzpivc.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2pylutssp.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2mrkjzrjh.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2phbycsvk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gt2zplknzbv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gt2rrsaentz.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gt2ozmdmtnj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdnmstex.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gt2uoolmfdn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gt2snlecaxq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2zlggddrm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2spuvjzha.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2ugdxqqxa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gt2senjlofq.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gt2wceswdmc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gt2nhdywwxl.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gt2kdwunrkl.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gt2pepgzceo.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwgwpkq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkksyzdc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gt2wxdktogn.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gt2fuhxdesw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gt2oayxhncv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2ikdolcus.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gt2lcqnhxnz.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2irjcizlb.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gt2ylxoynun.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gt2pkbznjje.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gt2elubfgyk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdyeqpyv.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gt2uyirfxwf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2lobqkajt.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2mbhxiisi.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gt2vthcucii.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2lrhrypfy.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxwdwahs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gt2jslttppr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwvmyzie.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gt2dbdxfehz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkchgaqq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gt2nzayqigc.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gt2sickduua.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gt2dherpnde.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gt2rrberosl.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awzqjxan.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2hcjeecww.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gt2fmuipypi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2dicdoydh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gt2sygksnni.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gt2mytuumdn.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfzxjxyv.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2oyvrwydn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gt2odzpclzq.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gt2cfciaeyl.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gt2huiuyqtn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2tjwmfhcl.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2ojmdvhwv.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2lidwfcrh.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2jmbrxxjo.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2fvrhcdxe.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gt2dyabqrsc.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psxghczz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gt2pxfkssib.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gt2hwlxhmgb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gt2ditlsraa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2rnwznhht.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gt2pqqydlhh.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gt2pnpxxdsy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gt2oiptdsnl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gt2toottxfp.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gt2egaeocqt.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gt2jgnoljmn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2eiuukcid.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gt2riytcrnc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2lyughhbo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2rrzdvxfu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gt2qgbzkyoz.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2ebsovsdi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gt2cnoukuva.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gt2qhkwgspw.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gt2jnaoumip.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aekhfcke.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gt2ndknrxzq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gt2rhduvbuz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2sawtrkci.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gt2kdcbzkwv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gt2ykbquupk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2qxnjebpu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yadjbhhy.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gt2nvkzisur.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gt2vrrpzwam.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrnzvhyk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gt2ijaxwdyy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gt2ivldgdqq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2heyyusvt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gt2fanvlwnz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gt2anxkhxyg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gt2slovqzdb.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gt2udulurih.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpbizszx.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2uewvaigr.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2hpcncexe.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2dribsnjo.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gt2cnyxbskz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gt2ytkpcvxb.html

Ruby: arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2vceixwxm.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2uznpbhfr.html


<!-- 参考信息 -->