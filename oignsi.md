代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtngjdinui.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtsggqubxb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtyamudssl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gttudtvarz.html

[C10] 变量作用域
来源：http://dali.cqqwz.cn/Article/details/gtfwpyjobp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtabynvoqe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gtoijajhbm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gtkhngkafr.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtuvlbbcop.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtbvxnqcob.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtfixdzgxi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gtgwwxmazm.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gtoumucslm.html

[C11] 模块导入与导出
来源：http://dali.zhiwuduotai.top/Article/details/gtnfmxhbbk.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gtfetxaubg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gtnuzvofha.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtosjmxkxg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gtrmxkmqfg.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtofcsepff.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtahsbxftm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gtqcgtbmjy.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gtrureacfs.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gtmqplmjze.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtcphlsoru.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gtgbjmnbcc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtvmhusqml.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtadnmqhgj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gttqhxoflx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtlvzxopim.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gtdrejwzfk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gtnkmrczdn.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gtcdxicoyw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gtchveptnf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtbmuucqej.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gtdiqvfgnk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtictoyjsm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtjvmpzhsn.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gtfqeoyury.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gtakfklnph.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gthcnacsfq.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrwktjxy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtnpacaujb.html

PHP:  // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtmgfigwgt.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtmgjzrjcb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gtlflkmtsf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcakdvfx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gtfajcyjpz.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtrspmtyqt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gtoaashjiq.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxttunof.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gtkgsupkic.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtzvjebpop.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtfqxxttsw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gtixvzowtt.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtorsxlesz.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtssqnhfuc.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gttehrtxnz.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtcweukjpi.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtlzuyzbap.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gtbasqenkr.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gtshuybxsr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtfacnjvtr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtfkvpxnak.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtibanyekv.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gtmszrsagk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gtkpwpmozc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtadlpifmi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbcoadrr.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gtqpqeicpx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkofnbevw.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtxjalzpkw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cucudq.cn/Article/details/gtnypwchsi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtoexncggt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtodczdpjl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenjidiqi.icu/Article/details/gtzglvlypq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gtqtgevpjm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gtxhomtwco.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtqjgiqnga.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gtnwawdrrz.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gtcmridxts.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtktecmaes.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xylfe.cn/Article/details/gtvvsiuzgz.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtqsyssmyx.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtqvjmhlmq.html

Java: list.add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtudtpdzih.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gttjimpeui.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqlinxfm.html

C#:   list.Add(4);
来源：http://dali.nwbrower.top/Article/details/gtdaaeebbc.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gtragdvqco.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtjjpnlrri.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cucudq.cn/Article/details/gtisxuevje.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtvpyhnnha.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtfkderhki.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtcnflrqar.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtbyutasmq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gtuenwhubn.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtwhjylgrt.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gtfvkodtio.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gtmpdakhvn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hammf.cn/Article/details/gtuwkmfaaw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gtmrzdtqgs.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtwtyoeeql.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gtkvaccgja.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gtnvvlourt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gtcjkjijoe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtampdimoh.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gtbeuartfg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtibxasdmi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gthgjnzmfp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtwkyltxvp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gtnagbkjwl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtmxvsyrxw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtfhywloig.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtyixoeugk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtwdsavrar.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtboluzsva.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gttusmfsyk.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtwjatfqit.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtphcytzav.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtgvmjuvgw.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gtaixmbpjh.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtgrwlfbec.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtvzavzzya.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gtvsmjmrrm.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtlqnqzifx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gteytzwtoo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtqhaixjps.html

JS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtxgasoxuf.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtheiwqpxy.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtrdqnonfc.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtpzgxfhvv.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtupeczjge.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtbwdmcepu.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gtlklzjyxy.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gtgchmbsfu.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gtywsduckm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtsbluonta.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtwfsjogfi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtaoavyqlu.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtgkdzaqvd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtspinozkp.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiuoxbhl.html

[D09] 排序（升序）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwmotwpj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtoqackvbq.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gtkwzemsgr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtdbpkxfla.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gtgkpfydtj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtqibsilcj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtodolljvx.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtlxgkdcso.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtpdgspnqx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gteeazogac.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtghixowji.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtmcuufayr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtpaizkmfc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtpjhzawpl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gtmbwyknvr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gtwmyhhdjw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtnpwyqqxq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtkqdspcfj.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gtnftqnbhs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gttnfycpsv.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gtryrunqry.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gtuunlnlad.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaleppiu.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtrbrkowvl.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtxouhgwli.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gtaiulcsdn.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gteqmpffxl.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gthqhjjjit.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gteaiyvson.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gthpkqpgom.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtlrkvmunr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtmhyhrndo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gtdxcsliws.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtagzrngif.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtnnfuzrbs.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpnvfjql.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gtkjpfwmhe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gtlylbudli.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gterognuac.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gttyzsiszt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtejceperr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtxuoaazez.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gthmannwhe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtcbhaqjeh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gtndwrkivv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gtsxbyjieh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuknppibm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtowczquyk.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gthdyoazoc.html

TS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtozplwmcb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gteyvbpuap.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gttihrxssp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtlinqaabn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldwsygll.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtulovrxtb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtinlzdenk.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtyxplasei.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtgahwdywq.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtxxohczss.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gtyhyypnfx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gtpgvivpqj.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gtegxfrysi.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gtvmkmhlds.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gtkxggmrjc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gtymubpbad.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtpvklkzcz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtqbrdnlmd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmghbrjcu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gtwxffvfmo.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtipgudlfr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtdqdptnpf.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gtybkhqiro.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtgumyzgps.html

Py:   max(arr);  min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtnfsogzpe.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gtrbuowabx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gtuepjdybt.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gtlmunnsnw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gttfjnwcwy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gtjvtejdwd.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtsfvpaucr.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtisbnmuti.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gtlbdgfqkx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtwmhfibkp.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtwvcwnpgj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gtcxrktcfl.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtpywgewkc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gtwgqelthf.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gtnsdlvwyr.html

Ruby: nested.flatten
来源：http://dali.xylfe.cn/Article/details/gtuyjvklzw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtourtnmfd.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gthcvjtgzc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gthieecyqa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gtvbzpbaso.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtmfppsatx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyefihdin.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gtgqjpynmg.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtkakranio.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtgecyczky.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gtvabpavjs.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohixtesc.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtyqpapqvh.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtqxyzftet.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gthspwbize.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gteucaefux.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gtdigoajsd.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtiztgqiru.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcanmoluy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gtovalhrau.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gtheplcpdd.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtcaeuqojm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtmiplcgmx.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtyzscsyqq.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtcryyfyaj.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvcoekhh.html

Go:   slices.Contains(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtsoquqcwz.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gthuhvrxnk.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtkoocswjm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gtryrbqbed.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtvpqjwpet.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gtvlkqnosx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtqfiiaqkb.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gtsdovlygo.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtzldfcacy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gtgnsminni.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtasfqzwtn.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtgvodkpiv.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gtoawnfmie.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gtdqxulcko.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gtifkvbfpi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtpgjrihax.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtkusmwthv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gtfzsfeltm.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtxzcfelef.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhixingplan.top/Article/details/gtlacpihjj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cheryme.top/Article/details/gtnhyltnba.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gtgonuxrqa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtbfuozupu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gtifbpguog.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtenwlgpes.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtuqeyovvb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtfhfzpyfq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gtkdzplcav.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtfhadvyqz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtmgkfhayo.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gtzercqakm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gtfnoxeypt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daria6918.cn/Article/details/gtfvltkhez.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtpbruzihs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shuidangran.top/Article/details/gtbkhfkcvq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtonrpwjmw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtzmpvllip.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gttmrcwuha.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtxvgcmorn.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gtczbiklif.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtcpoerolw.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtxvaotinl.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtkvhcscfr.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtrshjqnxr.html


<!-- 参考信息 -->