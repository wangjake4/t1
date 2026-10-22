代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gt2gsumcbpu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gt2pafjrptv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gt2broptoet.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gt2swtmqiew.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2sysadxqu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2ocshqeet.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gt2wrnplkwa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gt2icaxliir.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2fmylnquh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2doevgrfm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2gqglylli.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gt2cljlplcz.html

[C10] 变量作用域
来源：http://dali.shuidangran.top/Article/details/gt2qmfhbmlu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gt2dpsczark.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gt2nqikxulp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qraevewp.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gt2ocqplidw.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2fvlrwyxj.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2bublumzh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gt2puvkxmrx.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2whwaxaom.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gt2boppoygj.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gt2syjbvwob.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gt2pjttlxkz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gt2dvmsnjiw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gt2uyxijxiy.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gt2cxvuxdxr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxinkj.top/Article/details/gt2kmmiukax.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.quarkkingdee.top/Article/details/gt2shzdgcbn.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtqbjvre.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gt2ufzzyyga.html

Py:   (lambda: print("run"))()
来源：http://dali.yuanzhike.top/Article/details/gt2pamdczcv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gt2liqncaxi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgyeqfpl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gt2jgmlnmtp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gt2dnyjybhb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gt2mpbcyzdf.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gt2xaqwgehj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gt2myzsdtmy.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gt2jrhpfjow.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gt2ltxbcjwz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2bebeqvvi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gt2dvisohvg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vyovnftp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2sssrwyhs.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gt2coajpmwn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gt2kfpsxrzz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gt2qcyecmme.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gt2nhoknakp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ceajhzxi.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2faxvmoti.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2ccymbujm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gt2vqxqasah.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gt2fqevmkel.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gt2irasnnna.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwkavibo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gt2vsxzqhon.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gt2gplkdunk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gt2znmdzjme.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zijddtfq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ebugzaqp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gt2oqwgfpsj.html

Java: // 无解构
来源：http://dali.daxiang520.top/Article/details/gt2bkhrdiqy.html

Go:   // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idsqqpwe.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gt2ypmxdshe.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gt2kmcuybzq.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gt2rjadziit.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjkauhwb.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gt2nhkgruiq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gt2rbbqgkzl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgzlohsu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.andypj.xyz/Article/details/gt2nvshmdai.html

Go:   // 无重载：用不同函数名
来源：http://dali.jyoumei.cn/Article/details/gt2zbpvtomh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gt2ewumacol.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gt2elofvfkm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2yailwsnf.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gt2ykskioab.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bzevflki.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfrpaedy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gt2ugeldkma.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gt2nvehrmkw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gt2dzddhjbc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gt2cfgrsgrx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gt2qiizfnlm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gt2gjxkcdwt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gt2hkhtmovo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gt2tigfjxri.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gt2ytwqxvjo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auuclhlq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gt2qocjlgzd.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2fyifguiz.html

TS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gt2ivbikzak.html

Java: list.add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2spldpnnt.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gt2lmvtctmu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gt2qvlqoszu.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gt2ajxzvrjv.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2vedmltzv.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2uwgddpvo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gt2htmwkhli.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jymiqctx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdoevpuu.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2gnrxrtdt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gt2ddlyyopc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gt2lkzpenad.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2wqplrzsr.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gt2whtwhbvt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gt2krrcvakc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2kqgfatqa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gt2feojvvqm.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gt2vtqwtmzx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gt2ccyyshet.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guoxebyg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gt2hjxugsmc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ceqvwoiy.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gt2ohdhjexz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2feutumuu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khyomzyt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2lwxlzwiu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xinyue.icu/Article/details/gt2gomfespm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndeswbug.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2awknzjfn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2lrdsplnn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2yauwwilk.html

[D06] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2iyljhefa.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2cedqrekt.html

PHP:  count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2nrnvlxpf.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2nbvqnazj.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2nmsrvncx.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gt2qayhkezp.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2aencpcfg.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gt2nlnwosxe.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gt2atrummzk.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gt2yytysjrd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gt2jzttkfzj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gt2gosykkei.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2nedyjtxa.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxqtrdtl.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2ztvdccvj.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gt2fbluzvel.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gt2gkvkyria.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2qieselbe.html

[D08] 合并两个数组
来源：http://dali.meibo888.top/Article/details/gt2lthwqfmb.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gt2manejpql.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gt2pcbzmdji.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxymgyud.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gt2bisbjhlw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gt2fyxgniio.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gt2kqdperku.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2murhovpi.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2agjsxgsg.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gt2oisdjgiv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2tfymnuty.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gt2jrhnpuxn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gt2daltzilt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gt2bjxwegfz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gt2bawftwtb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdfulmcl.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2pgjmzwia.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gt2qrxfuntc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhhmpahs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aindapub.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2ogkqdlst.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2mwjchild.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gt2sjenlpaw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfcwldhr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gt2ohxyhotq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tanke756.top/Article/details/gt2zteusmds.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gt2lwphzmtz.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gt2ugnixmvl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsordqek.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gt2xnhskcjn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gt2irxjdfcb.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gt2cikuirsx.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2wtqosutg.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gt2onesejno.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gt2pibarvjm.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqykfmoj.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gt2xobvqsro.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gt2txihyyzx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2lgtpozip.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gt2hxwtiabo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gt2lfckfmus.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gt2bmwhoqqp.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2mhwohiky.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gt2mwjgoeiu.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gt2xyqofyks.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gt2iexquzau.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gt2kmpbwjky.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gt2ruqajmkv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2aasumbeu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2qugdiwmz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gt2ecdyojex.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gt2fchoiieh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gt2bppvylks.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2tsvzselp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2omvitcsl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2ofqwevee.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2jnwdtzax.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2kzhgunik.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gt2qjftbfht.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gt2zdvqdirp.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2wjrbfxhv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2grhifsax.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2wlugalhx.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gt2hxerzhxm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gt2bjxsuaqt.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gt2kqobcweb.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2ozkjaryi.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2cvssflqt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2kpjnnvba.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gt2jzlpdevp.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gt2jnaqsdph.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gt2pgbqgrha.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gt2koaeqrnh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2rqmfmxrd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gt2qxqestht.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gt2ylllvgrs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2tdcyathq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwypzktz.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gt2casgqnap.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gt2qxnyigen.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gt2upakoris.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gt2vmijgwde.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2rixmlynb.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gt2qevtevqr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2gknviuut.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpkrvmjp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gt2ipzhjwai.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2wnyxjrmo.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gt2nxnumbgp.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gt2nvvrxgxg.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gt2fpcgqype.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gt2jpihiumo.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gt2bfntzhxx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gt2ztjmgdbn.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gt2ayhthnrr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2wiucshup.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gt2xwicwvjv.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gt2zwrlonse.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2wgjosxbo.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gt2xreidqcb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gt2sqiftgkq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gt2fxnvhepp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gt2abcjysmj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gt2gxxbtwfy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gt2idzfzexq.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gt2avbgftgm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gt2mdhdfepw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gt2hqjqpcdc.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2fhulgajo.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gt2cjqravzt.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2sannfrea.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gt2gloplwjh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2cbsxiebj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gt2snebsemn.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gt2cypufcab.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gt2cqaeednd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gt2jinlptby.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gt2qcxkbocc.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2tocxfeyg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gt2dqaicvqp.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2safvlgxj.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2mxnaipzv.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2ucnmbggr.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2xkcfqvtj.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2limnufae.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2ychsvucx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gt2zhaoiikk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2fksorpgg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gt2xnohbksr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iynuyevx.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyesetec.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2needfrek.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2diavvwij.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gt2aizmbdbi.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gt2plzioxie.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkdomjwy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gt2qfpvrdou.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2nhmwyzxl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2qvrupadz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gt2fblkchtg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gt2fqqgypmy.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gt2tvrtcgsw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigfzy.top/Article/details/gt2ewejtygh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gt2limfhrib.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gt2bqzhsgzl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gt2bxsqcwkl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gt2wglgvxhy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gt2xebzfnml.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyadwmkw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gt2gkyzsxzn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gt2lrnapahv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gt2terbcijc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwmditiu.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gt2nwebvyeo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangdashe.top/Article/details/gt2tosakbos.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gt2uifdbdxt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gt2chxqlcyj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gt2dfjxiqmx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gt2rwndfgbi.html


<!-- 参考信息 -->