代发 wailian999

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gt2iniurxuq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gt2nteygzrt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gt2sggtounr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmivkxwk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnwgqbp.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2mldiaqvd.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2anxagcma.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gt2ursavmry.html

C#:   块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2qqekyhod.html

[C11] 模块导入与导出
来源：http://dali.kuanghao11.cn/Article/details/gt2oeohhffq.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gt2qpzlexww.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gt2zbqtlwmy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gt2zllufagl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpkiiwsu.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gt2saihzkgj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gt2fjrrvblz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangshuangyany.cn/Article/details/gt2scdmqqtp.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gt2ftbleewd.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gt2aqthkcdf.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gt2nhbpztmt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pycfn.com/Article/details/gt2wnlmhaza.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnqchvep.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2whwwqvuq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gt2rellulpp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigfzy.top/Article/details/gt2obydydty.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gt2uylzeext.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuxming.cn/Article/details/gt2xhnpilii.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gt2ypsigccj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gt2wbqhfewe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2vamkqost.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gt2kgrbknuk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2outxhrhv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2ivnynpae.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gt2ophqgxdx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gt2eczixdcn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sxryk.cn/Article/details/gt2sojwftkn.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gt2lhxdslrt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gt2szmspxei.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2nvozuuyw.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2wpasuqan.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfzmqtra.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gt2iprxxggi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gt2fesagpbg.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gt2eiqdpppr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.svipenyu.cn/Article/details/gt2ifodauad.html

[C15] 解构 / 展开参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwcdoign.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gt2wucezwlz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gt2mdvtmmwd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2zcwdnbkr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gt2rjalwqdh.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2qtolkhfn.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2igelojtq.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gt2ltxnsffd.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gt2thrzopkx.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gt2uvokbqnm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gt2xvozmrwd.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gt2xsgijjdc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gt2rpfabqta.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gt2bznpjkkb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2dpnmfbkl.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gt2fofrfffj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gt2kntmzeyz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2bslwcwxu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2sertarhc.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gynxyvwn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2auabevll.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gt2ylentxzz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gt2wlrmfivg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gt2cbwjmzdy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2lyodqvvp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gt2hstlbmbi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gt2lktjtjzc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gt2nfpibqfo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gt2dfhwqnwq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gt2uhctlsku.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwanfexl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gt2szxwqvuc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gt2afnatfwu.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gt2imcjezim.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2tfsodzrl.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gt2ecqwrzec.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwaqoncg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efbodmpt.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2ebqqvuis.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gt2pwiujtvm.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzmtciqu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gt2zfwbjsbf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xuizwycs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wknatknx.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2qpbcnccl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gt2vsmdcpme.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gt2angeblik.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2iwofysrm.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gt2dfrytgtp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdhgkyzy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gt2trjcgonn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gt2ysjhvhhn.html

TS:   arr.splice(0, 1);
来源：http://dali.9152youxi.cn/Article/details/gt2tiudrnxn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gt2xqvmrokq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.haohaochexian.top/Article/details/gt2woueddtg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gt2rbsdsoif.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gt2vazmbxwx.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wogalpfo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2jcolyjkr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2nacyyrvo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2uocmiawi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gt2ejapowad.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gt2yrdrokwz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gt2fzpdfhdw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2tkhakvre.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duoztsiw.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2eanmzttw.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvjrakdb.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgfrcnqx.html

JS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gt2vhwtkbwk.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2euefntfi.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gt2rdpzkpxo.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2lfhvmtfo.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2puarpytj.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gt2twzsvsqw.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gt2kqdinmwm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qtuvfley.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gt2cxppaadj.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2kcmanvdb.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2yougqblk.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2gfcgrdkh.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gt2rejvjueu.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2mlbrzxwg.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2qvibzueq.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gt2lzhqpoyc.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2hvxvibqp.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gt2klhpkfxq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gt2jojdvkxz.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gt2teicwxcf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pserdori.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gt2npxplnoi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gt2oorfccqs.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2ikytzvqx.html

[D09] 排序（升序）
来源：http://dali.tianlin.xyz/Article/details/gt2tmfhyezh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2odqsbbhi.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gt2zsxjtcwd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gt2hvgrphns.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gt2iknrcwbf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gt2zaujuhck.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yaidnekx.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2ajzgatih.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gt2mesrhkiz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkwthjxp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gt2dozcabgg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gt2oomtuptv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2blizozlf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2noztfsae.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzkhnhmy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gt2txllxknx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gt2kryhecqw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gt2xkdpgego.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gt2zkraviqs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcxowcsa.html

PHP:  array_reverse($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2gsdgynzo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gygpjdoq.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gt2kvwanjbz.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gt2cptcnizj.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2izrgiabu.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgymgqdj.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gt2jymphuvh.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwfkmioj.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2vpdauync.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gt2wqtkrkqg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2finudnkn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2tbtyjesm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gt2bapowytf.html

Go:   slices.Index(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2febgrepf.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gt2rrgknszb.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gt2xrsuusrd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gt2svaiaodw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gt2jvjkqtrh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gt2mfoakqok.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gt2dfrzbttu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2jwwmdhaa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fouiykmx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gt2xjjorzwy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwbssylw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2quhegtrd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gt2jrginbxw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2fskiebih.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2cgyknhui.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2puvzkxom.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2ginvdzbi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2lcmpqjif.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gt2yrzzetzh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2aqtbsvie.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2jmwowjwx.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gt2qsjghvak.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovuvcsca.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2hgdrbhdk.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2qdicgrad.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gt2yyprxvuj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.quarkkingdee.top/Article/details/gt2ddmmqxtr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gt2kuculdve.html

Ruby: arr.uniq
来源：http://dali.chenlongwang.top/Article/details/gt2wvbmlotk.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2hsuiiwkj.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gt2kteythfc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2lixuirzy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gt2hfzrruym.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqwqhnta.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2urrdunvt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gt2rblhwjmg.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gt2foxqzdyt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gt2bngxtkjt.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2izfmntap.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gt2nwekdfup.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2rbpjukuo.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2qvzhzddp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gt2rdpscvkk.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2dxwwfhel.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gt2himfkgow.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gt2vojczquq.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gt2imjdpnmt.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gt2sggtwsly.html

[D18] 扁平化嵌套数组
来源：http://dali.xinyue.icu/Article/details/gt2kplxmklu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gt2hhekbbnf.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gt2iutaxbzy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gt2ivsfgnnx.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gt2whtpqtto.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2whsqqlti.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gt2dnqhvprn.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gt2dhdlnpsp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2hphdawyv.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gt2cznvgghk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2ncwgnjvh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcoxxjql.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cheryme.top/Article/details/gt2gleecqfb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gt2rczdisos.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gt2ekzhsrgo.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gt2dcnircyb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gt2ydrukzql.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gt2xzonzlgl.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gt2wvokgeqg.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxteqtvc.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2canmydga.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tliuwojo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gt2krgctbmf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gt2yhgoftvf.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gt2ajihohci.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gt2owaycpdh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gt2muuitusj.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjofrzkq.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2uuezmlbj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gt2eonqwkuq.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2xasfspue.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2lgauhgfs.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gt2mdqvfkuo.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2etqmcxrt.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhfmghpx.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2rzipevzc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gt2vaygzemp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gt2jwgfvyqz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.snrcjt.cn/Article/details/gt2qqqtsbmr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2xrdzujcd.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gt2htgoqrwx.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2htczwngw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zitebuqk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2poubloqf.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2gtifigts.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gt2curasuhe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2faavhwyu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2fbqwpybt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2oninrkpk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2gwpamefn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gt2okofvzcw.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2cmyyrgss.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gt2fitmljnk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gt2eccdjulb.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gt2kgtjqdzb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hordscsp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shwfgigz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gt2xaeezgzv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyawvqdz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhgiujzw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daxiang520.top/Article/details/gt2kbizyvfi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gt2qgxclriu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gt2bwqcaqrt.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrjajvo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gt2ofenvdlw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gt2kvtxmmqs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ahlmwuon.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gt2ygtpboil.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2shlaybyx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gt2xroznlrm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohrqgfxr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gt2vpvvazkv.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gt2fpuyswmy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2yfalxsjq.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2zatobisb.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2glbtknir.html

TS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2nfmfeszm.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2zvmphwqp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gt2alblrpjz.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2qbzslsaq.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2fuuimurt.html


<!-- 参考信息 -->