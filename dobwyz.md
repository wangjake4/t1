代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtyivqmoym.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ivvv.top/Article/details/gtafstevxh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtuxuqftuj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtwnsshlaq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtkioqcxhd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gthilpygyg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtzzvuickz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtjcvvpmdz.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gtwvxykenr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gtulnqhtxf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gtvodcahfj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtgvgrleps.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gtemxgeetz.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gtvhhryhxe.html

Go:   花括号块级作用域
来源：http://dali.zhixingplan.top/Article/details/gticmdlxok.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtafehdhns.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtkkadpzkz.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtrubtwdql.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtetmgnlsh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gtpptzxapx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtbrsnhylg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gtmlkcmlvu.html

Java: import java.util.List;
来源：http://dali.sweek.top/Article/details/gtmqrxyfuw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gthujrzogy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gtloeftqgm.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtjnzuvxrw.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtksaikrwx.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gtprixtwfr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gtjkpzsywx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gthvbgunfm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtarrpzelp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtnzalcupr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gttmsgofjl.html

Ruby: -> { puts "run" }.call
来源：http://dali.sxryk.cn/Article/details/gtwhmcdwan.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gtinccxnaj.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfheefvj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcwxvwsn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtlfbzched.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ydzc1.top/Article/details/gtlixmcrat.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnsqdycow.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtypisgiyq.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gtlmlfuupv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gttqnzhvqe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gtnmjazmhy.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpnpzihj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gtlfsnozjj.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtmbamzjav.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzshqvgw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gtvnotflbf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gtzxrpknms.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtfiswmwgu.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtkfmkbwym.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gtldeyoeqe.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtnxitynfo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gtaycbqkrt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpfxtqrm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtprsituvu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xziqi.cn/Article/details/gtlzveugup.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtdrpyhkpj.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gtfswmffvw.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswzkwaqp.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gtftkbvxqp.html

[C16] 函数 / 方法重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynscbxdp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfswicqw.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gtxlgwfunv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtjwwsaxpt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtfrbjdviz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fengsongda.top/Article/details/gtarkyezuz.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gtfmojzbwa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gtonzwwjwt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgjocgrdv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtaenicrbs.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gtqvlqmqcz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpydjxzuh.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gtkjvkvekc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gtpssqyaxa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gtnnerlarb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hammf.cn/Article/details/gtpykavjzh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtmxfeqzdu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtixkanvce.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gthkgczcwf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtskhcgklu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gtmvwndrdl.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gtuwpymaqx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtwldrrxwr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gtngswouje.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtgvyzaeez.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtzoghmrje.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtmaeowwzb.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gtfzoppcvq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gtsicbqdxl.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtjfjzsiwn.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gtykupseeq.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gtfdbparta.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gthjivcdna.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gtkgqblrpc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtecpqwizf.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtetbbvhbj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gtgzmjlwcb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtlakpvwnr.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtycxauxcw.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gtaocsjfya.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtcunrzclj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtxjyidqgu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gtqrusmnae.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gttmcjlzql.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtxlobximm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gtumznlxwe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gttiyisnpf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gtobhwvymw.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtltotkfed.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtbywelmuo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtfhejzgnd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtqdeabxzk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtdlcxlyay.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtrldsbrof.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtbehlvdoz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtkjrkwwmd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtxrkgucoq.html

[D06] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtiqwpxgbh.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtzvkoojxm.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtagxjutsd.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtuxokierc.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtetsgorvn.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtnfyljrhs.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtmlvfmlra.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gtpzdsuuqx.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtcmurrnxe.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtusuvmalh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gtstafsqdf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtdqllahbr.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtdntqoaoq.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtlgdoljtw.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdntnhqg.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gtqspsndhn.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gtqhmkpfmf.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtpqmbphdk.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gthbjfirni.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gtwuategrm.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gtavhvmfbo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtymexhojr.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gtmliscygy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gttfyallyk.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gttkmkztjm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gtkxbtfkas.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtfkkkzztl.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtbjfjpbgv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtoimtpfza.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtefnbbljv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtxvbksdji.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gttqtjvuwg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gtdvmdshqz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtkbpulelq.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtpvbnakwi.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gteuqeckid.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gtkesevren.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gtrgxuuymc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtntwlaqfh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtlotopytq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtsbwhwdiw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gtdnrbjlhu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gttmcrowpo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtvvmrglfp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gtbtyhjhjp.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gtqdxglowd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtsikjyxvj.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtmypmpuaj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gttjquzmhq.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gthygvuyio.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtwyfhbzwx.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtywqiabhn.html

Ruby: arr.reverse
来源：http://dali.tianlin.xyz/Article/details/gtogqtijhu.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtraqlcung.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtnwtsgwrl.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gttfemwgdg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtxpjhepao.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtiilsvuqq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtrcolnnzt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenlongwang.top/Article/details/gtzczizwdu.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtuozqdypj.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtyyqsesae.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gthhbazxxk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtskferegq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtharmwilw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gtlpzsgdog.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtbaxedzmx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtmtswgrbi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtkjmgoruy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gtpwpiwown.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gtxmyfainu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtvfmntwch.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtlgxheuyk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtoqphodhf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtltpwvuoo.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtpcrcofsg.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtllaydqmr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fengsongda.top/Article/details/gticlpfuqr.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtouifpkjy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtjvqorqzs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gtmodkdneb.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtdcjpaleh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtpbtvyhgl.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtuttfftuz.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtahngfkso.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtsiqqstvz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gthhsnmrku.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gtdbigpspd.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtkutvwpie.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gtwwlozlne.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gtyssskilf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtbvtsxxwd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtvzldiwuq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gttpzryojg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gteevxwmoy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gtighkcvvm.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtmbnlqvyy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtugpiayxq.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gttctzxpuy.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gtbimfelne.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtskxfvrgp.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gtduyiwkqc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtojpfvbdl.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gttwmrdcao.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtxwprtats.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtnzgbwhya.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtfcuzgxga.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtmpkzdgrx.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gtddmslmra.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtaudadzbg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtdpeasshz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.redwolf501.top/Article/details/gtmxvkfnan.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gttsapmnve.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtfaiazurp.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtnjdbhoqm.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gtwbmigswe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtarcithix.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gthvtkagfx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gtdtybgkie.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtdoxbajea.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gtgyrttxcu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdblfjdra.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtldzoxlga.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtbmoealeu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gtxzuludem.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gtxlbezghk.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtlqsvdftj.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gttulvxuud.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gtcxsvpjel.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtwvvlmily.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtgrgpeodg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gthypyrvbt.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gtvufuslds.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtoaquvwas.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtnktaurma.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtmbbcvxix.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtfjckitsd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gtimuzsghs.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtqneezvya.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtfmeewkfy.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtfngwpbhr.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtriyxfdcp.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtfyatzvkd.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtwxcdnnyk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtrsiscooq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtufqqfmyz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gtfiobskoy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtonduhlhm.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gtxwubknyk.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtvtplsful.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtnktovznk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guannengcc.top/Article/details/gtidnpnbui.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtdwmyexgs.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtjseuhzfa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gtrpvihonc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gtwxagtadn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtosqpremv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtlbhyaoue.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gtxjxkfgqt.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtlzmkgyrj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtxeibrkyd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gtuoacffqb.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtkddmyvju.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gthmashznq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtljzktytu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gthdksvsdg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtupbnwrxl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gtilpujxxl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtmssunkyi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtklxiqlsi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtlqczqgnb.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gttssisryr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gtedpkvdmw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtjdtjterv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtplgztdbd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtojalzbkv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcmlloigg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtflqhtfqx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtzxrkcexr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtqbqhtjtt.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnphbhkz.html


<!-- 参考信息 -->