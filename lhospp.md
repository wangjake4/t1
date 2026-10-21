代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtaycoeqih.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxodmnxje.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtvkhzivba.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtjmdliwef.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gttvzdljzy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gtysdnlfjy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtjrqlpoxk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gtahsrkwpr.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtxfeoesoz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtbomlltzm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gtgrxzmark.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtgkmthaio.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtrzxcpitr.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxotmqke.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gtptyzqqlo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gtpwkvjltw.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gtfhsurfei.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gtqvcfmbpz.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gtbeykuuwz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtfexrtbso.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtjlmnjakv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gtdoasacfp.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gtxgfdjkzx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtzpzeimqf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gtoopwublg.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtmynpsfev.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtotvdqpwn.html

Py:   (lambda: print("run"))()
来源：http://dali.zhiwuduotai.top/Article/details/gtmtpmlbio.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gthnazepeo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtvzujehwy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtybfvxofx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gtyofbzrqh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtfsmdpvql.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gtqfvstaxy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtcgbzfklm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gtgwwwmjrq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtjcfxpuvi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtyajbvsmi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.mhx1999.top/Article/details/gtjdruhnkq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtmejmcgye.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtvzgxmalf.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gtnvzehncv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtdhauihwu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtqhupexrw.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gtzfpacvnx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtwzgbxltq.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtwwfnyyfm.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtecrecvlt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtyarepcra.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gthkavlwhg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.haohaochexian.top/Article/details/gtixdryzbu.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtkituhlgt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfzvfgof.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gtrcklnddl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gtpueluxtb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtlxdakezf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtrtxbsnrf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbysvmfkl.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtxdklenrs.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtprkscrap.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gtwwqtlrig.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtdjvazmnh.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtrmgayikk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtlhnaxbni.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtcdsipsef.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtxcjfzqcg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.9152youxi.cn/Article/details/gtwrutaoqd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtmqmrytvk.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtebxpatip.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtxtwhggkw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gthxgpdiso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmeegrcao.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtvflvdmpu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrugrdtj.html

[D01] 创建数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtabqipquo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gtgagpzkzr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtbgxeyvzo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtwxtsypgg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gthdylpvps.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gtdnwspcly.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nwbrower.top/Article/details/gtnvqfhzft.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtdtxrzofk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gtifzbacgo.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gtfqwuwlpf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuxming.cn/Article/details/gthawbtyqa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xylfe.cn/Article/details/gtfldintfk.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtewbdggvx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtflsqwyry.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtmqfenqlg.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtlytditxy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtfdqfpqqy.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gtkwukkjlv.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtcqryqqhz.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtmuapnxah.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gtzxraglfa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gtlsiswpka.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgupkbgq.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtnjrhqddw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gtdsvzbpvf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gtyltqaiez.html

C#:   list.Insert(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtfflkijsc.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtpcbdxiqv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtjliwauhl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtophdlkoh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gtnaeuuoeb.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxlkmmpd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtvgswtsgg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gtsamgroho.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gtvmoovmrp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gttrqgiohm.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtgawejqkz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtwhxtydhm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtovdoqryi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtmpizcjny.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzorhonoe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gtwkyhftjp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtnlntauve.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtpurewwzd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtzyblcrkz.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtyioxmxcf.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtkvordopf.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtwbnkizux.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtjmpxklkf.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtahtdgsma.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gtoiuojbrg.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtneogongz.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtdhmwyzpy.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtjdkuivnl.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtxkfcafrs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtmlfpdyqm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtggxsdtge.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtbjqoqclp.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtpmticsyv.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtevicnkwb.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gtijuowibk.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtcakgmxeq.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtjicwfcbc.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gteiaelocq.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtrmxnksum.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gtgjxkgpxg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daria6918.cn/Article/details/gtukmaqttm.html

TS:   [...a, ...b];
来源：http://dali.sxryk.cn/Article/details/gtocailgqd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gtujcuucqb.html

Go:   append(a, b...)
来源：http://dali.quarkkingdee.top/Article/details/gtivwumqwg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gtzwepprhx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtarhashfu.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtznubwyqa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtbbqudcvv.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtkzvwyqqb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gttoaqfave.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gtwlltwjmq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtncpgfkyu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtrgtthdft.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtybwtemuq.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gtupplnyoj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gtxsoaqbix.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gtmiouaifv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtytkrgesw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtaayuvlsv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtldrbfmvd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gtsvcrjzkh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gttjovsyfq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gtstxpvean.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtqjcvxzqd.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gtcgywogne.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gtdbxuuohs.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoyexmqg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gtmsvfbmos.html

TS:   [...arr].reverse();
来源：http://dali.aizwys.cn/Article/details/gtvycgjctm.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gtjkvaxdef.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtdmlcnhon.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtwapqphjo.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtwcwpkpak.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gtjjqbxvlz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaznikzdd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gtvtrrwotn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtoroknxcd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtyhfwffee.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gtjrdgpoyv.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtzfqflqge.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtqfwgjexx.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gtqudncmbw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtmdvaykyv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtflyxwxaq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtlabvfyls.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gttqadhwaq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzpeqbdd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gtsbuyqtsb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gtlcdhwqqc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtoognxldx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gtqvggttsm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtplbzkhqw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtngwpcodn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgberodgm.html

JS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtrphtvicl.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtfsbcdipo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gtuudrybiq.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gthmmfwzom.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtxkreygio.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gtsgnujmdt.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtfnasrxfp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gtwajshqns.html

PHP:  array_unique($arr);
来源：http://dali.yangfankeji.com/Article/details/gtjrgrvvur.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtqhftigen.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtiwwsdfrj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtejncquuv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchicujnd.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtbrkjupzs.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gtdoxxmgzz.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtzlqcnvja.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybckuguw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtrexiudir.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyhbpels.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtqkpjzvbm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtoqncjuzy.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gtdbnobqcp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gteydhsaov.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gtxkosixsq.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtpzzyinlq.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtccohnoxf.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gtziyqffgj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtzxmihcxp.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtvgopoujm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtxvpvdubo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtfryhixls.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtrjbaeakx.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gtnoeawnte.html

[D18] 扁平化嵌套数组
来源：http://dali.yongpay.top/Article/details/gtjkrnihzl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gtbqeyholk.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtjjfrmxmm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtpqbbbnpp.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtbiphrtbg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gtjyicvrkv.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtxnokbgvc.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtfiipssui.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtacflymho.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gteatpmtfp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtupoqmpxi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gtcxnopses.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gtuyyzxzsc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gtsqeokmoc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gtopnnaomo.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtslmntism.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtkkitlyjh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtruwaxlhw.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtswnhheuk.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtjvbzmnte.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtimhdkpij.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtatvcctvy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtmgqcjzuq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gtfxsfficc.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtnjnxgguv.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gtldghvrqs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gtgzkcknew.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtvaqlfvjz.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gtnzbnlubv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gtbbhbmelf.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtqmzyedtq.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtedjhtfgo.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtliutihdz.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtcnjlnvxb.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gtrmmxadgr.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtgjesmdhm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtfmmrmmex.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gtumnhwlou.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gtzjtwkpnh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gtwalavpft.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtvedburrg.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtmvbkdykt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtnciagida.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtvngtgise.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gtcwzgkxjn.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gthwvuipcf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gtktzkacjp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtmesokkkz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtudniwawn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjxfxmfs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gtkmtnwtab.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gthkuzepqn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gtpoyixjbm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gthzdmlgqa.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtmytuqlqs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtgvlcipgu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gtygstifqp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuetfsoz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtafzvalxq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklloaiwj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtvxjpxtxv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvltzcjs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gtevugxohd.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gtfvuovdea.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gtgrgjprcg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gtubjtauwh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gtplzzewos.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtuwpefqwm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtnkhljake.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gtolvuoovo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbexgrvjl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtgdtklidj.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtioxlevca.html


<!-- 参考信息 -->