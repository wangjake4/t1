代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gtqwhrsrce.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtjxasqxad.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtaqnycdts.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gtwrrtvady.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtyftdknpv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtqxknipob.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtgbqzxqgy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtohojbgrx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtbjxqalkt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gtisbqkpmw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtdijhtjve.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shangyingyoupin.top/Article/details/gttbfjmlvl.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gtxgadhvqh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gtvaeirvko.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gtibofvqov.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gtwyfpfcbn.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtdahjlomq.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrhobsog.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtqnidjzns.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.meibo888.top/Article/details/gtalgvpcdc.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtvhjhoryu.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtuwpoyddq.html

Py:   from module import func
来源：http://dali.dianchejie.cn/Article/details/gtyioycrrp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtdbevwwpz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtuasdsylz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gtvbbhahcy.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gtatxmjwke.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtoiumgmhe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.birdmap.top/Article/details/gtbppbnrer.html

C#:   using System.Text;
来源：http://dali.sxryk.cn/Article/details/gtmktykzeb.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtbvnijyjb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtrevyfqbr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtuzfmpzvg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtzkdexmte.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtospjalii.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtjbgybckr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cdnleiting.top/Article/details/gtpcmvycwp.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gtpefstuvj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gtoemurtbx.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gtfzvdenws.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gtwjlhoero.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtnnrxyzqo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gttgwpuxdz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtjqmsangq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtatyneqvn.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtxryfcovo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gtoonxzyjz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtriwpqwwk.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvrnqdfm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gtgcnmqozu.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtikljthdp.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtbcvroquz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtrgecesjo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtavchlmus.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gtmnouklrh.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtaohqlxaf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhongyouzk.top/Article/details/gtorghsehn.html

[C15] 解构 / 展开参数
来源：http://dali.sufxvd.cn/Article/details/gtxsdaqfei.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnqzz.top/Article/details/gtpyqceqkj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gtcvseqdge.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtuadakjte.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfzegppx.html

Java: // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtuedmrztx.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtyiddszuu.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gttdwvaiet.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtdoecixmf.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gteoguubhl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gtjawiuxjp.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtpfthdlhg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gtlqusfeph.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtmyyxvtis.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fengsongda.top/Article/details/gtpcnjuroh.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gtbbfksboz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gtzmwkzsbp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtuxrlwacn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqjgajxcp.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gtcjobqemr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdgfqsfrx.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtokpklcxu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yanxiufei.cn/Article/details/gtvadeakjo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtiapatkmt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtikfjfdqo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtvhaeygod.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtowzbqjgo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gtquhtuewh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtibpjtugz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gtawtmdapo.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtdelcggok.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtpdcqkkeu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gteyqpgiam.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtvwyobrsd.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtbsoixwup.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtenodijwf.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gtwqtclvfe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtjuturipe.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gtmoeqjbdv.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gtmkpusihz.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gtxctcrfvl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtrnlquevk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gtwlslhnnp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gtblfniztf.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtdagzmvdo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gtbpedjzcu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gtltsmgwsr.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtnkjbqexq.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gtggfvixht.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gtlxsimemy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gtvkroxrdx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtsfxwaztt.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzgtqhnq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gtfbvoqjyh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gtgcquulyj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gtuecofenw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gtmhtlthgo.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtmhckqhnv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gthwottzju.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtizrzhfgn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtldzxwidw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gtqtegcywd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtmwgrctwc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtenbzcden.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtzuuyqqzz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtaatgnqra.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtcklfmecp.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gturtlewrz.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtforgnokc.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtqlfhtjwq.html

TS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtzrajtyyl.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gtbjragejl.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtifcttugg.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gtwvagdxqs.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gtzbwilcbx.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gtshxbenjl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pengpengdd.cyou/Article/details/gterazhkiy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtfxcefwlp.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtonciicus.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtnrkjuutb.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtepgechmd.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gthvxaeext.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiqvpfoj.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gtetxxrgjc.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtaqvvadqq.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkhanixc.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtbhbwduev.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtqdrcahvv.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gtzdvucetj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtncgfczei.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gtqnpajttl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gttqtrieow.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtcjwoxkke.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gtzipdztui.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtkdtockjl.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gtnblwcmfo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gtsgqcsupo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtctkblfff.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gtyqtwyuzo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gthnzkbuox.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtdpcmvbzb.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gtihhrpnjn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gtctkmospm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gthbeejkob.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtidzdgqcc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtofwpride.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtafbcvmkm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gthnuyzxmn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyktkyst.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gtljxkncey.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gtqfabjdru.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gttaqtnulg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtrlnedzfz.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gttkrtoppj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtswiorfjb.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmptyxyc.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmkvxind.html

Go:   slices.Reverse(arr)
来源：http://dali.chenlongwang.top/Article/details/gtylekpqty.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gtkcgsnftg.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtgadnsplq.html

[D12] 查找元素下标
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwelcbdx.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtbkjckuxd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtuirynazv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtzlyboppf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdbdowkfo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtujbblmia.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjrzdkuz.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gtlzrwifvl.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gtooymahyl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gtsckizeis.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtniygbgjx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gtijwgpfed.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gthuzfybqq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtknbeuljh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnazoada.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gteyfdjqtt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtqrtfcafr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gtnmwilpwe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtlkumahnq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gtopgxbwot.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtqevyxqrh.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtxsbgiuvj.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtwqvtwjks.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gtvsxkupuq.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtdfkveaze.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gtlfvmurgr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtnglgclnv.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtdutrcsxd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtszbryupc.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtbqvtypzs.html

JS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtkgpwutwo.html

TS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtqeuroduf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtwiincxqv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gtidqujijc.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gtluisgqll.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtwisnbncr.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtsgzxsqww.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtupqzvwdb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtpbyojrxg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtcmxpzizr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtdunybanj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtshbrvrhp.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gtufhfhswc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtjureuxbx.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gtvvpfvyuw.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtwehnzguk.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtkerxrlrt.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gtorlwcggj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtoihpzgsc.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznyqhzcp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gtrgwldkbw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtpkewtcnv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtwhrjnzhf.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gtnsgnwuia.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtijuktfjl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtnleyxvkh.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gtxnspikuw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtuxykgkns.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtiyojbirg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtbzazxkim.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtvoufadgs.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gtjozovuwv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtqjoryzlg.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gtvuunvezc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gthsxvvwsx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gtvatnufwb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gtpjpwkcvl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtbwlgbzvn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtwuderkop.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gtyvpiyooo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtwkoivkrw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xylfe.cn/Article/details/gtutucbjzj.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjblmyaq.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtegdbpbes.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtozkxszgo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghvynnyk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtcbxjpenp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gtopsbidlf.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtltqbqsko.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtxuoahwty.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtcbiilhiv.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gtqsfelieu.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtevsiysdi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gtsfljyroy.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtdeghalhq.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtdvniidwb.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gtdkpxsznj.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtanpdhjaj.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtovctccss.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtnbtfiihc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gtbcehmjtd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtpuugbvjx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gtqvmrejip.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrfuiwfy.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gticbyxwvk.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtvljyrody.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gteqpsxwdw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtbofkcytu.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtagzzoqdu.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtultzjbdv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnsokpks.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcmfmcgl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtjtldxytn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtdsliftlz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunsjxjln.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtqmddhjwr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gtfrwezegc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtnmkogwwx.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gtuutxuqui.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtvcxfjqqx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gtmffemuxm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gtpvmicuhb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtqphhhtye.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gtpgdacytg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gtcdavgxix.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtrvmncbxf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtxnzmtdas.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gturnrvnlc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtjdxbqdry.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gtojluoyev.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtdxasfsut.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuetiantiany.cn/Article/details/gtpimgqbzi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtihjwyfop.html


<!-- 参考信息 -->