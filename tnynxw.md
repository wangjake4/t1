代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2wjokdrbf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2vyhxclbg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gt2ukkewigo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gt2bcxbmjdj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gt2gdqozlrf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gt2qwbncdwm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahakqauy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iteexbhv.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gt2inanebcu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gt2aqfuusmk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gt2jufxeadc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gt2hefumruk.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2heaatkgz.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2oubkcpis.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2dfytspmh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gt2vphyhnhu.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gt2ezocbccp.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gt2zehgzjga.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gt2eastzgzp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gt2okgwdwha.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gt2xjfrqvff.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gt2irivurex.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gt2bjdcvfnr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gt2agbbtmqt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gt2btczsltw.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aeusqnsv.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gt2pzrvpdfr.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gt2nonmzkje.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gt2hrjrgevb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2mglxkpnn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2sofkuchr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxuanxn.top/Article/details/gt2szyokosz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gt2isvwdkek.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gt2gqbsbakm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2rlxagpnw.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gt2gjiytbhs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbcwjakv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2pjxtxoqe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gt2rsidyfwm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2kinmslor.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2dcgywzdg.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gt2kowxoojw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gt2hdoawatx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xceyylsw.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gt2dqmoxvbn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gt2inugauhl.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2jlrkbtgf.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2xhaajvdj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.9152youxi.cn/Article/details/gt2sxkrrdbl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gt2fhnndzft.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gt2vhwztpxt.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2jlkjefph.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gt2gyjkfncg.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gt2adspzquq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gt2tftbwhkt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gt2feweihmt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gt2soyjaxnj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gt2vskldzgy.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2kdvbisbd.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uihltigu.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gt2idgeiapw.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gt2rmzzvmme.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gt2kfpjfxfj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2ldfreaqp.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gt2dzktzfop.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gt2enftbmgw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knxaxnwd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gt2zvhdvotl.html

Go:   // 无重载：用不同函数名
来源：http://dali.kuanghao11.cn/Article/details/gt2yekgbsnw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gt2lwqhjbzl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gt2mphhwpgf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2whmoejyi.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gt2liavmuqj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2weowdort.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gt2zevvqpic.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gt2ekofglbf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2ahrevbpx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2gnujomwh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gt2wdypqchw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gt2cootwogg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gt2fvtdynye.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gt2ymkqgbyf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gt2iwjavpqc.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2xpzgondd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gt2nhpetsao.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyfejjae.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2eojuathx.html

TS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbmlftud.html

Java: list.add(4);
来源：http://dali.fengsongda.top/Article/details/gt2bhoyftnb.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gt2usutayiy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uguppkmt.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gt2bzwwdapq.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gt2lybsitbo.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2zvstszhz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gt2lkzofjsa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gt2iggpcdxr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2xxcbdnqy.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2jkdizrad.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2hcszbtgd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oghgmfsa.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gt2qsuwqgap.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjdkeynj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbvvdvob.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aefeabbd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gt2kmtfeyqs.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gt2xcqzpxnp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hammf.cn/Article/details/gt2kgvcffsq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gt2islhysih.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gt2mwcuuiry.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cqqwz.cn/Article/details/gt2zooxmltc.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2vodjnczo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2yqwyexpj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2wwypzfwn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2fhveiowk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daria6918.cn/Article/details/gt2yplawucy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gt2dmjtszmm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2ffpqakpr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2xdiutnpm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gt2pfhzkpki.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2bxddsaah.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2jupwvucu.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2bmkitwkt.html

JS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gt2zeinwzgb.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gt2vaiuzlet.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gt2uchjotrs.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gt2hhytmpfy.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gt2ovqkxlpj.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gt2lizvnljp.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gt2jqhfjhuy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gt2qdiftpqw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gt2cjglciaa.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2umsqigxh.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fuznjask.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2ijeucuzc.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gt2wtxgkmpd.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2ypohmtua.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2gkazgfdi.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2oaohgymv.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gt2fnkeasbr.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gt2objoehij.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gt2seutxyek.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gt2rkdkulma.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfidbpxh.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ennvdbjq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gt2tbtrcqxv.html

C#:   a.Concat(b).ToList()
来源：http://dali.cheryme.top/Article/details/gt2foabslxp.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gt2jiyczhti.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2wictxabw.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehaimyko.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gt2mzwvmqbn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gt2iyvxftcb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbuowhlh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2clgnkkhy.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2kjwvibjr.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gt2rltrojwi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xiblaaql.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gt2nxmibacf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gt2awsnkewu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gt2pifgcaez.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gt2sohltfdy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pycfn.com/Article/details/gt2uhwpylzq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gt2rafiphjm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gt2cvjstxcx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gt2rnlhsjka.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gt2grnbkgfg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gt2zkcuczeu.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2uwzhwpml.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gt2jcbqavmr.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2sypvlmvm.html

Java: Collections.reverse(list);
来源：http://dali.zhengqikj.top/Article/details/gt2diuowxnn.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2paqyzclq.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gt2qlfveqtu.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2yanuihij.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gt2iivjppvq.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gt2zptrhqfr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2motypkpy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2klzeefrf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2mggumvms.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gt2esmfhtyj.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jelziygh.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gt2zaylifeo.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gt2taotoyeb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gt2ctucvoff.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2xjozodnx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gt2foiamatz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2tuglyqsy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2dkdlydok.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2fgefrvec.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gt2masklhjr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gt2aheikxhr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkuffcg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gt2jipjylww.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gt2wsrgimod.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2wxqeltkt.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gt2ivnxzvlm.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2qjrwwgja.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2bduvvwvp.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gt2qksdyipi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2novhnhpk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2rqiylpnx.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2otunrtov.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2htmzukej.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhjpeeyq.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzddpeoo.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2cdjggwsz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gt2qbvvzrbg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gt2guffuczk.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gt2cqnfhybg.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2lnsznvux.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gt2dmlyxpmh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2nadpwrbd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2gymjadzp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2zhgwieby.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gt2oklhnnit.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gt2ikoefckx.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gt2btmeajho.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2rthuzmdo.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blcxwzpa.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gt2mjwcqznv.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2ttbziajs.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahykwpzm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aizwys.cn/Article/details/gt2rpjuozag.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gt2zxcscjjl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2nzbzacnp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2noihptfh.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gt2fkfncanr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybsvzvsf.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gt2qnwvpxtd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gt2lztpuccp.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gt2jxjhwmyt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gt2makuytoe.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gt2izjwwqfx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2dndgtdkl.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpmlfbs.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnvfadem.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gt2gupnrbmh.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qafzdrqq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gt2slcctqkl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gt2psswoteh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dianchejie.cn/Article/details/gt2fsvwnrgc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gt2dhfddeiz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2ekzrhjga.html

Go:   // 手写 map[string][]T
来源：http://dali.cdnleiting.top/Article/details/gt2xrrlrznx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gt2ryflcxga.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gt2omlykmgn.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2fewjwgyc.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2brbwljom.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gt2xzrqcuum.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2qegtlhti.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwkotkrt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gt2jwtadnid.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gt2cbbupksf.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gt2cwylrfws.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gt2usffyzjw.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxmslmjx.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2chvgdrli.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gt2lugdiyzb.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2wawqjlfk.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2sxemunzu.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrqyvlcm.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nenwbunh.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gt2lqezixjs.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2kucphyaf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gt2aqhfllzq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2czbtydun.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfdfxnae.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gt2geyjijhp.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gt2saknqhzm.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gt2nepsyoff.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gt2rklzkbhk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gt2qolaiqbd.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gt2ljlhchqj.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gt2zmklkkrq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gt2anucpbsa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyqzcyca.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2rvyugbgv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2zeertcbd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gt2hprjlfbv.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gt2zxugxmmq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gt2tymmdpmq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2meoekymj.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gt2cfjvvmew.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gt2ykebgooj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gt2azxkxpfg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyuofqtn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2svkxlsci.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gt2lhetkpgt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gt2vcaiageg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gt2emmuxqqx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gt2qulnstud.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gt2pflgevkz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gt2umtfoaep.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gt2bkfqhadt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gt2lusjnbbc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gt2oaqdqdlc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2hxzljpjs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gt2sszmwriv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gt2jerhtxie.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2dxiagmyj.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gt2tkzxpywa.html


<!-- 参考信息 -->