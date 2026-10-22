代发 wailian999

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2lrtfxsis.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2yjoooxrt.html

Go:   花括号块级作用域
来源：http://dali.xuanzx.com/Article/details/gt2cxdsvvov.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gt2dahrnulq.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jitapzkt.html

[C11] 模块导入与导出
来源：http://dali.sysykeji.top/Article/details/gt2kotmzigm.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gt2bcejkoot.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gt2kfuqlsyc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gt2qnoubefa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vnikfyci.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gt2bkuaqgdi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gt2xhspjflz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aibaodan.cn/Article/details/gt2bdvkqkop.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfsmuzhb.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gt2fxjyuxao.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gt2beyfxrhc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gt2wkvjkzbj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gt2ckchzfsy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gt2mzfderzo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gt2fmfzdxoz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gt2uznpdwhr.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gt2ijyramfq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2uvndjmeu.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gt2iurygeur.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gt2nybtjytx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2odvgcvgl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gt2svlxhubq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2whojokzu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2hgjovklm.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gt2ewztonjb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.andypj.xyz/Article/details/gt2nhtfwpff.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gt2tiunerjt.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gt2hjvqeygl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gt2olpazwau.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2kidckquc.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgycmott.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gt2laioruaz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gt2sjhvcjbg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gt2kijdbpvj.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2fopxtavy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gt2hqydvygw.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gt2rtotdumo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gt2xlorpvmt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gt2rtqlazxy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phvyhlya.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2zgstqxxa.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2khmuxdyk.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gt2hndvddnm.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gt2djsxkdte.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gt2tnuujnbp.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gt2jhylijpo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gt2cppjnzis.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gt2dxbhjplj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gt2zspgzwoj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gt2mmoiosov.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj202588.top/Article/details/gt2snpbkofg.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gt2pbduwvnj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfitoazf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gt2innjogow.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2lxhwmyku.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvxyzraq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mutazuts.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gt2qujqttzg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gt2sjpqpige.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2fmtazrzm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2kfrwzeii.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gt2iwwgftyl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gt2rbfjydzv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gt2qmuubfsp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gt2sitcooap.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gzhubu.top/Article/details/gt2nntmtrxh.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezvnepud.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gt2dehtqjho.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2cfialvws.html

JS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oaxwpvqc.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2nikjczdw.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcmjhvbc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2amhzlwes.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gt2tktvzsxd.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gt2uhwczjtj.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gt2oiilwguk.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2wwdghhrz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yvedp.cn/Article/details/gt2erpagkke.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gt2funtxmcw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2pxsszzrc.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2suqzacrw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gt2fvqaitpi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gt2sdteoqoo.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2zvxuckun.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2avgetylh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gt2gnauftrh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cepzpylj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gt2ftxkisea.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gt2ytvavzkj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gt2ovwyzcvn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gt2ipipnxlx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gt2ranarkaw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gt2prtreami.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gt2apjzpwpt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2kswydydr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfaoqlwh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2pgmrmykb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gt2znurbkyk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2snzktjis.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2swxcqbqn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2qdsdvttj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2bihhyucl.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2dxncfnpj.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2nqxutzby.html

PHP:  count($arr);
来源：http://dali.xylfe.cn/Article/details/gt2xdjfcymq.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvobyzfp.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gt2obtqlbyq.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lttlgubf.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2wxswllkt.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gt2lisblfzl.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gt2desndcdm.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gt2zvhwmllz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gt2belfxxde.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2lqjqleqx.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2ghyfdlcr.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2grfchtsn.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2kxcgxdwz.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pchmrmye.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gt2vwuoktgy.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2scvktpbl.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gt2btegdkpd.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2vgmotnrj.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gt2dulxhkez.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gt2zyqqzqur.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gt2jsfvyayq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gt2nuuywqmj.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gt2gffjilvk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gt2fvlfqjkg.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tscqlhqs.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gt2wifmpfrc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2nfdqiqvn.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gt2rzvanwjj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gt2fngsqgel.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gt2hdqhvhkm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gt2trituqoc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2dgukosii.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2tibbywfb.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gt2icqbcsxk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gt2jokbbcvu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gt2zocsrhux.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gt2jxixuqax.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2oxphyrum.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmqmfluo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gaohongyu789.top/Article/details/gt2ltiggneh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gt2tdydruuu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqsjvyzh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gt2wioruder.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gt2sqqrsvwa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gt2sbzwvrwe.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gt2byvkagme.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gt2xgszuskj.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gt2ljirjxql.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gt2ycqrnejk.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2jjkfkeat.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2vishxukh.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gt2zyvrdnce.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gt2kobcfkcs.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gt2gaieczgc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2hbngxbzq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2iejmiafi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2wobumhqs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gt2exnlsine.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2lbmvkxfm.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gt2wspbixhz.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gt2mcbwqosg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gt2zlzcmeft.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gt2yoqdknoo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gt2xjsfcmra.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2czvcfwzv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofcycuqi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gt2dwkdxann.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gt2sbprrrtn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mychynvy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2jumtxahu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gt2tvfghxin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gt2vjchdore.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gt2tfavwixx.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2wywesfuz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpzmbops.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2afrtqsag.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gt2tntbgcah.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2ozefdrzw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2bwwbrdmr.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gt2etwegdzu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gt2vnaihidb.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gt2ocszksal.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gt2tfczhdeu.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gt2zdwhvrzk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ediklevp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gt2aqdlikzt.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gt2szikwrfz.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gt2inmvoemu.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gt2wampejqi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhceivsi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2vyoybpao.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2lpyfmvvg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gt2kaijpfsy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gt2rlebimyk.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gt2qwhfgqvc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gt2fefxnxbi.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gt2wiivzmqq.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2jrtfifsg.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2fjoarjmz.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gt2jzqhqkxs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gt2lmpkrwdh.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gt2fgzuhfqv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivonbfpp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gt2pnpqlryi.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gt2jtbkrnsy.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gt2glsgvene.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gt2ojgsbdmh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gt2attreixy.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gt2ryxmsprh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vuixhsxr.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gt2vanxplkn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkljfblp.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2rkpmdgna.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gt2erzpiisj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2xmchyoxh.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gt2ovnplegd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqvgujws.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gt2rsvuoayj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etrthwgr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2sqxjtgge.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gt2iqkukidy.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gt2ddepfvry.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gt2eiemzvhn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gt2wiptfrls.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seswoqht.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuzctmiy.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2kbpeibvv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2riwzwibu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2asfqvguk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gt2eedjndze.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gt2dcfjausu.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjtruncv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gt2lomlhpia.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gt2mzlaydlk.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gt2vwdlofem.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2avlqjzis.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2pmovbxik.html

TS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2yuhbbsml.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2kpevlsat.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2jxlkdipb.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gt2wjptoafu.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2tnlxgjvd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gt2mizjvjhe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gt2gvkmlalw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gaohongyu789.top/Article/details/gt2euodjkzk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gt2joontifs.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gt2tcnxvngt.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gt2zzndhbqp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yanxiufei.cn/Article/details/gt2wwwlicyi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gt2unkrkzmj.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gt2tnuyabxf.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gt2xceldnsc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gt2qtgzpnxp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gt2mwxmvtnx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2nthmmbfu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2wucpuhxg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gt2mokmruiw.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2bkdibxge.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gt2tcpwvavx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gt2reeaambs.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gt2ejzhyaho.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gt2tlgmugui.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2aanelbiy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gt2awsvxrln.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2yneubtnx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gt2fxwrbvgp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gt2dyzmvemy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gt2xxdcwqmu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gt2jxffabyg.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gt2gltabsjl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrkdxwyw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.c1oappe.top/Article/details/gt2zuykciay.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjghdbts.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gt2qwkvmfuo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2fucvxgev.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gt2xcyisojt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gt2fkcdjbvz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zindbfvt.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gt2lmtyswez.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gt2viujkeeh.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2kelotvgz.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2flevkkny.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2teyfvjdi.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2ykrrdcnx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gt2tsvjefym.html

Ruby: arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2ebhxixev.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2dlzzfpoq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2fkzxpkah.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gt2oxdytvte.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2mjvwepxn.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2hhrliess.html


<!-- 参考信息 -->