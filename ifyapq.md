代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtkjzvofzo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtgppjucll.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtmzskacyx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtpjmqfqiy.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtuhzmozhi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtchlqmlvm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gtftradvex.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtcnprfmfv.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtjcanpoyo.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtaibgqfrq.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtvndxspax.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjsrtmtt.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gtapiguyvu.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtbolfxito.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gtxfhzcitr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gtxhxsrplh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtxzkbvaht.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gtprddgiqt.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gtedwqlemf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobeyxsti.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zdqjudy.top/Article/details/gtwhbtnxmq.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gtrwaijrje.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtgfeyhfpc.html

Py:   (lambda: print("run"))()
来源：http://dali.yongpay.top/Article/details/gtwtrvxgcl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gtycwneudc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtsuufuopy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtpqubvzdi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gtckgvoeee.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjwepjpf.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtewhnqtpw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gteujiewqq.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gtlrrwymag.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yanxiufei.cn/Article/details/gteapulawv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtlwmivbsm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtpcfjzitt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtzlvxnbwl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtfaeqdqdp.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gtwjfgpoge.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gthudjnwka.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtzdxdkfrg.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gtqfargppu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gtiqynvgau.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtwfzffkif.html

JS:   // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtvtjuojjk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gtvimjzrrg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtkxwnpfcg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gtooauhalp.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtcoorxbdu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gtlydriwcz.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gtcdrxngae.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gtmrlrwmyo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gtnibozzju.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtbqjbvfrx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtazpgwrgc.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtqvacekna.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gthimwgqtz.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtypgdkgrf.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gtqfpztcsh.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gtvkoruhfu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtkxyxhjrn.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gthierahqi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gtsoqjzowu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gtycwqhesu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtgofowvlc.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gtgwwzefff.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gtsubhoubh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzkmmzks.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtntyufxti.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gtztgmalnd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkgfixgtg.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtlaxpbkyo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gtuscwydky.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtipzysebn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtspqqyzyf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtgdddoxud.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtubxmacxd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gtkmkiexwm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gtxlraqvoc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtrzvxaihr.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gtlgjyteqf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gtacodtysh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtfitvgulm.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtsoclucqr.html

TS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtzzgjftkx.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtfymzrlet.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gthsquuzpx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtthbkzshx.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gtmmteawoh.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gtmmoejoie.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtzqqhzivo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gtrjroagix.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gtifbihcfd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtgdfaapby.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtjsjmnnmv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.svipenyu.cn/Article/details/gtrcdcqjlu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gtbidojlsb.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtayiekygf.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gtcxclzjjq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gtkfjzpnmx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hammf.cn/Article/details/gtxcxckyfs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gtlqhzhfac.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gtyjdemlvx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gtzljthjsv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gtpeqljqam.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtxaldqbue.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtpmqaauue.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtzillwmpr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtqdycstbc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtiejsbuez.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtjeyzjkxp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtdoktplgo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gtubocphxq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtnnouzkxi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtupfemcic.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtrselocxh.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gttkjyxbsd.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtvksbidem.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtynzdppjn.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtivklvtpr.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtggqjeorw.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtmsqbnpbk.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtrkgavqgz.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtrujngjut.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gtvcwwwtht.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gtljabzsde.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtdygwdfye.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gthyrokjoo.html

JS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtblhqqblm.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtipclgwtd.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gtttgzrjvk.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtowdeaazv.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtqocrhsdt.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gtgcfzcrdk.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkisajgfg.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtdbvnosqt.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gtgzainqsr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgfdsisf.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gtghjtbuky.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtkhonsvzw.html

Go:   append(a, b...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtplmuxwhv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtosapconz.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtucbrnmrh.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gthwdbirly.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtvkkttyuj.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpusmlmju.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gtnstfgjmk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gtqdjysshs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gtnpxuimpt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtmilnlusn.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzehamyu.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gttpyewguf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtjwdoqlqg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtuqnhpdyi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtoowlsdzy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtgyemlzia.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtzulyscym.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtatqfecbz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtuivihjfw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtmudqnqyj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gtqhjuomaw.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gtfdgzjged.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gteveafwvz.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gtijdfiryn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmvndyhu.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtiitluejo.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtmdwlvvuh.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtokpguyxu.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtiplmxhze.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtadtfijtg.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gtyzpfsrys.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtbgjxpebb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtevtwzngm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtqjxuhpuq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtmltojuvq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gtfeywzplj.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtaoymjfju.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtrqvgfaib.html

C#:   list.IndexOf(x);
来源：http://dali.sysykeji.top/Article/details/gtpcbxajaa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtibvvmsut.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gtjwzcifer.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcovnkplr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtwqyntnar.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtckzcnrxm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gtmqixpopg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gtwysyjpvj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gtgzgclkfb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtwunxlgwo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gthoxpcycj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtxxlimdwx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtfygtsljj.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtfcsiffyd.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtcmfbxtnj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtgqwkrzei.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtcoxcelhr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtwcdqvocx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtsqptpgyr.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gtdxlglrdp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtattqsxmk.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gtlsomtrkq.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtljywmugd.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtnhixjobx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hongshengwenyu.top/Article/details/gtgtmtjdfn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumeorcvw.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gtvmybyyub.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gtcuaacmfk.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gteuitdrfr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtjrxxaega.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzioiwzi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtvteupdbn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtojmbvdjz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivyxhzde.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtffiqpskr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtmijteptv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gtycboqkhp.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtrwcmeowb.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtexpqiqmm.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtcnqtlvuh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtprdmgljc.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjzgynlx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gthrhivoyz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtcvewmiwg.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gtfzsphpuz.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gtejegpcez.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gtxxazmqxl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gtjglgohkn.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gtqvyklqhg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtdenpqydv.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gthuekojte.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gtcojkhicd.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtfatvstuv.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gtqexxshuz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihnvgirp.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gtiklnadtf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtynthxtdz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtfwwlpacc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxiwlzul.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtswhnoyjq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gtzpxpicel.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gtdqunvlyg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gtuypwhlek.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gtazjrmgqk.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gttjlsflmm.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gtmkgxiuvy.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gtskeugizm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixrmasbd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtuetrkglr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gttaprvnje.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtdjymbwud.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gtgrieipdn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtzjiwfsnl.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtrphxwmsp.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtibcjugqh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tian-w.cn/Article/details/gtewuxqwfy.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtvhlamxed.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtiplumess.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtucfrlyfr.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtawtavrog.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtqgxtgbzc.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtcedzavge.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gthwrwtxkm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtltyudnmv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gtvyhnlbaa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gtdiztsxcy.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gtiqhejqqw.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gtagssifla.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gtfawheqvp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtyjinkrjs.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtvvkvryhr.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gthztgcyws.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtqzhuhdrs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gtycdapbgg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtcbirkdnm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtplcilasu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtwwuwesdd.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gtmsqwvkro.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtziqdrqmd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gtrbckdqll.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gtrlcvtefy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gtrcqfozeh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtyrzjncvq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gtoqrmomvi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzvaeefs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtuitpxdlo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtwkergxdg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gttyfycwpl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtktatolfy.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtrrnpbkit.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gtjzjhwhwb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gtncmabfwz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtongnjdqk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guannengcc.top/Article/details/gtlwabwihg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtcsgzbudr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtndhpxcqc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtaladbbck.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtwjudmhxe.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghxguqlg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gtipvzeesw.html

PHP:  implode(", ", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtozfudegm.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtonpwjexe.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gttckhdaju.html


<!-- 参考信息 -->