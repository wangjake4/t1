代发 wailian999

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gtbejaibfj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtziytuxed.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fengsongda.top/Article/details/gtvcfslvkr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtzvdoomoa.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtjlgqzwxr.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtksnvpjvg.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtvegrlvkc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtdwcxaiuf.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtifqpmtqj.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gtyqaofbvq.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqtmqczc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gtevqvrgil.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gtiresztya.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gtchakaknk.html

Java: import java.util.List;
来源：http://dali.vqdsnc.cn/Article/details/gtmrhnucwb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gtttrgaljk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtnepbofcv.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gtynobxghi.html

[C12] 立即执行函数 IIFE
来源：http://dali.xinyue.icu/Article/details/gtsmrwnscm.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gtasasrjdw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gthqgacsfn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtkescxlvi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtssubhdut.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ybcxt.top/Article/details/gtrkyisvss.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtchjcukum.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gtsehpfofj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gtttzawtyt.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gtegmrjhhi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtzsvkeyjy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtqyfumbzv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gtgxgqtedq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqepqwsa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtsytoecqa.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gtqxtbznqx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gtijbpikdf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtlqfvqyeb.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gthrfgurxy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtzkloptjx.html

PHP:  // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtatvyfacq.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtvamrllpm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtvakijxlz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gtpwrgwwxe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gtscrfzkof.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkniujkmm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gtbsiprhvq.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gtevjcndkz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gtnljmxthg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjbqsvco.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtsvzhxtjq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gtechfvxgz.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtlgjjmxhe.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gtncmrqjsf.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gtvgmozhde.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtwcrgspjj.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gtayvvzhzo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtkewnnicd.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gtcaxxiqvt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtmzetxoyf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gtbmgwjgux.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gtghvdgxvx.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gtbaeblezl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gtntdrulwa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gtljytbzeb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtikacrugx.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtifsqbfdz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrlqbzvha.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtrrgaqxgq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gtisywpqhz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gtokzjurts.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gtbybvruqj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yvedp.cn/Article/details/gtpsjqipui.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gtednzqrsm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gtsogeziro.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtljctnerl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtuwoxgbmr.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gtegrrkfmi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gtymjhqgob.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gtqtkwkgwu.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtxbzhebjj.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtnklznbmk.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gtenizgmka.html

Go:   arr = append(arr, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtxnfcrhji.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gtfyosxplh.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtufmhenvn.html

[D03] 在指定位置插入元素
来源：http://dali.9152youxi.cn/Article/details/gtkwwnzywa.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtvsspldrm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gtpokpowrd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtsxyqwpig.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtwsxzavln.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtdmbhiqbd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtlttmbwkg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gotoacloud.top/Article/details/gtgpytwzyw.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtqccnhkzr.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gtiaurijzw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gtebbfpylr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtdxhhoadk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtbehtptjl.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtitvszyab.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtsaqbfwxd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gtsfsivntl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xziqi.cn/Article/details/gtmognblfq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gtlgipsugg.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigcwoavi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtmwqvclmb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtgnwwinzn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtapbutfny.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gtdjmykcrr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gtsyufjhag.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtvqmxkdhi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtsoylasjo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtifhcneve.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtbskwoqkv.html

Py:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtnrkzwfgn.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtntsazfcw.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtenvvkirs.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtcyuylwuw.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtxqeznpms.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtsiswguxk.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtnjnskgpy.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtqssthjqc.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gtwzyctxqm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtwnnxrgfu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtgsquxdhd.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtcrydqdqd.html

TS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtfcqnwpsp.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtqsdercoq.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gtohccftud.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtctnbsjio.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtfbeytprb.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtmkndbpsj.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtjimajeoi.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtpptzrzdo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtnznviuxq.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gthvoywybc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gtxziitszw.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtaroybvab.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gtpatvzqvv.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gtrgiqaolk.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gtazwdtuer.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtjibrvgrt.html

PHP:  sort($arr);
来源：http://dali.yj20258888.top/Article/details/gtudnbjzdq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpqozkpz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gtztmcilxg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gtadlouhub.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtkwnpfjnq.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtmtcletgh.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtosquvxqf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtdnqtxvde.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtiqebtpsd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtcdpoxtwr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtkffsmlhj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtfflxfbho.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hysaishi.cn/Article/details/gtvwimzeyq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtpdjtljlw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtnpftqchk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszybfghk.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtixpdckqj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtmsgxqjfx.html

PHP:  array_reverse($arr);
来源：http://dali.shuidangran.top/Article/details/gtxbcjmono.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhiwuduotai.top/Article/details/gtmqpcohlg.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gtcmeyxris.html

Java: Collections.reverse(list);
来源：http://dali.9152youxi.cn/Article/details/gttpnvvkkz.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gtrojiobdt.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gthizbayri.html

C#:   list.Reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtfdwdjydp.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtbexaiocz.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtnkuvmwfz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwwcyiqy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtiyxtxkay.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtycgpqocj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtkwasdodf.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtijlpqfnh.html

Ruby: arr.index(x)
来源：http://dali.wangdashe.top/Article/details/gtnrfgsavh.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gtyovfosff.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gtmibeikmp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gtctsafhkc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtpgifhuqv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtxsrasbdf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusukjkwb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtajslqrkv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gtkjrfxtjr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gtcjxhxfwp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gtlgifjppw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtlctlgpul.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gtmeoqpgpu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxhdjokj.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gthihfgnaa.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtwrwruoay.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gtyphucvkh.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtztkpbwop.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtdwriughz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtpjcrlgid.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gtsrmhkqbo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtfjbyqwut.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gthfjzzszc.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtenkiebej.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtgudeerso.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gtlfvdjaur.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtsuooxmhh.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtjdclzlfs.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtetzzelqv.html

[D16] 求和与平均值
来源：http://dali.sufxvd.cn/Article/details/gtrhkhxkog.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtcpxvwrms.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gtretaaifq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gttxjnlhbw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtficqeify.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtytjkputg.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gthyqxuetl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gthmezucli.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuookeocm.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtzufbffap.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gtfvneyasq.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtrcelisjz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gtjkgmyqhk.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gtwvwdlvqb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gtqwdbkrip.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtfquljkxr.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gtompoppim.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gtcppvpbvn.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtbhkxpbfz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gtkgqfiriv.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtrwpmkmgw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aizwys.cn/Article/details/gtpseqslyc.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtwgzrsams.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtwcgsbdts.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtznhnskte.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtfctpcfly.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtgivdueoo.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gtflyiicuc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gtdrphtpdc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gthdumpguj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gthhjerrir.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gtztkdavet.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtjdrfgwaa.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyupxsag.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtcuohutwk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuxming.cn/Article/details/gtrgfsfnaz.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtuxtsecqr.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtjvuzjauw.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gtfufnrgld.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtxpxeaoyo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtghapnswj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gtiprmaodq.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtlyqccnoe.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtinnlypgw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gtjhekwrzt.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtmcxhpvuq.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtiysbrisc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gtkzayiejb.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtpqvexins.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqjvvsop.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtqeiikstb.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtrnsojspw.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gttpbsnitn.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtwtvysqyr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gtuzijswac.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gtrslmppjk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gtyoyaazcq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeodvtmh.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gtdbjpvsyk.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtzzwgnbye.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gtxzcagbay.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtgnjhcjot.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtqfancnqh.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gtjockijsx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtaeulpmiu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtsyjtnhoi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtxytljvqo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtxjxjeiah.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gtmaovmusz.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtgmoeftsb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gtcpbgcfjn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gtdogrvpkk.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gthhkqevcy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtgklqhptz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gteyyokwzf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtdqycyabv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtvpxmszib.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gtuxhkaxit.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.c1oappe.top/Article/details/gtfnblzell.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gtmxwtcvsd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gtwnwzzyqz.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gtbiotmutx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gtyrihvfzt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtlkvddhgd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcumgxif.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gtputlsojq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gtiyhjydti.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtxodqfljo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprxkfdlt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtlhwkzgdt.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtfgqojjwg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtvuzgpwbi.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gtwhvgfynk.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtbocyabmb.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtjjqwvfkf.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtppheeaxz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gthvftsvrj.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtqqceuxbj.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtylkshjok.html


<!-- 参考信息 -->