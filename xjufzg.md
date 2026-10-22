代发 wailian999

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtknyfrlzq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtesodgfsy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jlsjyb.cn/Article/details/gtofdakkpe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtqnmccxfl.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtvrbrbyvg.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtotgwcrbr.html

Go:   花括号块级作用域
来源：http://dali.c1oappe.top/Article/details/gtufllryfj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtumiqcjgx.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtntfttqgj.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gtfunhgpef.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtrifjpovy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gtldyuisvi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gterbsfmsu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtejzpxdsy.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gtasxbbymd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuhhipdv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyonkvqg.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtsgfozphm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gtzfdpqgnu.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtghlaouiy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gtvftnouuz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtfcwgeciz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtwjlteqnk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ppjwa.cn/Article/details/gtopjgisch.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtmuwmibvm.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtfligegqd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtuklsslli.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gtiogszcma.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gtxixlcorr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsqcrzly.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaxqvkya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtafuatbea.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtperrmmhk.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuxougqj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtvowqvxvg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gttlzdlqls.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtfxrkkluf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gtvaaditxz.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtjpcbhrsl.html

JS:   // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtczsjfxkf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbqcffkxu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtyebazqjn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gtpqexjjmf.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtkpcciggr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gtezdvrgqr.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gtkhrvkupr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwlzqoel.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yonumen.top/Article/details/gtfibnohkg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gthhzpliam.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtbsaaeabx.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtxhzvqgcj.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtpxmujpur.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gthnsgagfb.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gtrabiaxal.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtnmemqrej.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtwvnkfeob.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtgezuhdss.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gtraityitm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtskuvqtee.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdopwwupu.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtmontjhyj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gtlupbmxny.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtkgnsgslp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtphkehjmx.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gtiyytjmph.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvqbkxsfd.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtjivrriin.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gtggzzgrke.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gtsrfomgjb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gttoqlhgus.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gtzvpxviyz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtukatpfgw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gtiazobzgm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gtuyhjciug.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gtldobisja.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gthyftaqvd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gtsypopzmq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gtnqveewwo.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gteogshdci.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtktcmrxga.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gtiroxtnhe.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtqjspvjdi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gtlnptzxcc.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gteupuhagc.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtvbqgftll.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gtcflkfshx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gtqwkznxyb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtlupzcyeb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtjzyrctnz.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtdajqchuk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtfpvfmadq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtyqvgbhfh.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtosvmavqc.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gtugbyldjo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtrvjentkb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtihtkfzpe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gthicsxvhl.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtvectnnin.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtzosllrom.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtajprrdef.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gturmiyurh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gtcanuoyxs.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtkifxpehe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtuurhyrlc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gthrfcsgeo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpxtdjnt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtkgaiuzwe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtkxvkyqat.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtbirytllb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtdmxbfudo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtewxerskn.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gtwoifwhjk.html

Py:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtghslkuso.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtmdttpcce.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gtbmscqhee.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtyhhcqikj.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtzsjbwjqw.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdtiecyw.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtgizyiypk.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtwirelrwr.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gtsqjyeabp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtroywujva.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtnegyluoz.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtksyaycoe.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtghwhhdtu.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtuspqyqwo.html

Go:   arr[1:4]
来源：http://dali.sufxvd.cn/Article/details/gtmmdmtnih.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gttbihjyqj.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtwrueqaue.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtfxcgvuqt.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gtnzdoqcxq.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtyhqncmii.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tianlin.xyz/Article/details/gtksfqilow.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gtkzebycor.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gthkijblwq.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtbmayboyb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gtnrzxeyao.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtwddocalj.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gtxmhxcbcg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtvlumvopn.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gtyrxrenmi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtqzgbqsfa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyerhxbt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtinhooxpi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtogirhhhj.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtqshrmcwq.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gthahvqsan.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtnlgpwcwy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtdxyiezxd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtmucaaxup.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtrgkvfwdt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtcafzlrhi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gtrnjgzvbr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gtjusyarus.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtaryitacq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gtpruvxdft.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gttnkscbbs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gtxndbpdjg.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gtdufpumgk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gtjmtdahre.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtfpufqzms.html

Java: Collections.reverse(list);
来源：http://dali.zhengqikj.top/Article/details/gtodrscvjr.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwejphklb.html

Ruby: arr.reverse
来源：http://dali.tianlin.xyz/Article/details/gtnfndykat.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtgekaezhf.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gtjifyvftu.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtidhmyqju.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtcovuvgxi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtsuonrrpk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdddhimf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gtikjltryv.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzhsiupa.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtycnhxjcm.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtonyqqyxe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gtigtwndqr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gtjyygfobq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gtfdxnados.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtemildvig.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtgkjkpaja.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtzdkehoqn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtqxwvqtas.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gtfikbqgns.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gthbidzpip.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtkmyfazds.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtilodzfbf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gtppkgkyac.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtndohwwyk.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtyznvvsyq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gtaiziodxv.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtocwmqxom.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtixmqumde.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtfusznwje.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gttmdcmzoo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtwdcflxjt.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtdqsniofb.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtxpqyfece.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtgsusvpvu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtplnbowxm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtvacihrcy.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gtfddeogto.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtbmtbcljt.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtdeunyihx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gttounjkjh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gtenjnidbz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtdrqmwjlf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtpkwemhqw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gtvtcynsmj.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gtiwxtmere.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtujfntkhm.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gtcitmnuyc.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlfktqjj.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gtcfvlnkii.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtefdivicy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gthvotlnki.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtbzgbkmku.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gtmdzovicm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtpanbcjbi.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gtrlfwqqlg.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtzszreqzp.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gthhhrymqc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gtmnzkavdq.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtfzexhibz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtqmldgxbp.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gtamcwehtq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gtsjntjetl.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtolexxrps.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtdpbmemga.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtnpdcubup.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gtjgzwtibx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbhoknse.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gtvoqlaoya.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gtlcpzejvm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtyafssyog.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gtsawugkpc.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtaomzgavs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrrifjlg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gtjdcndqmq.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gthefhhnaa.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gthqhstmot.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtqpvkgdxi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtkfatpwqg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtlgsvvdgf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtljuoxgnl.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtvkdkapud.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxboiycd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtafqiwoby.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtvosjhckp.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtlfdvwqsd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gtcfhaohiq.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtrwibjtpn.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtrpvvvvyv.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gtjlpuwvez.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gttpxbckbu.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtukhhrogk.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtqudgrrma.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtvzdhgycw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gtymhcjimk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtrqgedgym.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gtjsnvctrx.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgjbgrrv.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gthdbvflxd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtadwelajq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gtqdlktjck.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gttlnmjbxe.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtqdserlxf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gtvendnmtu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gtzvlvsmnt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gttrdpfkhr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtbojvssdf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gtatogoisc.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtaglrpcem.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gttkdarhzq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gtofvzwyjm.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtlbumksmb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gtkoststdb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtwztvhxxw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtyzqgnnxu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtrqasxwsr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gtmrkkwbck.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtkgagzrtr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtrqxufzux.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gtwkgpddhc.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtplrfenbv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtvzyyigen.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gtltojhgyj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtonhdepsv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoucftcxn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gtjstdylej.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtjdsbprne.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtdkufetmg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtjcharsbz.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gtfbyyllcp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gtwbfkcfng.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtapivcooe.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndwwqmrv.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtcjvxulxq.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtxjdmdsrq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gtkurkntqy.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtqpstrhyl.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtxdhwlzfb.html


<!-- 参考信息 -->