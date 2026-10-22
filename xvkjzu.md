代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gthnnmnpox.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gtinvtiudj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtkzyydqtb.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gtpihaehzh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmtlbfdqm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtfzyjeyad.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtlgweifye.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtqqxwlyri.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gttntminke.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gtkvnsekad.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtanoezruo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtsmceeyyd.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtbktjxvyr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gtqtiotane.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuanzx.com/Article/details/gtoyygmswz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtgzmsoexp.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtfrktmynw.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtyjhwbefu.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtvlqbwvem.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gtksprsdmz.html

C#:   块级作用域
来源：http://dali.tian-w.cn/Article/details/gtevhchsep.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gtjesmjfcs.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gtgtmgfjww.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gtvlnvipbz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtraoxtimu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gtoxursmhw.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gtzpnhdnnn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gtjncehpqg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gtoiygrjom.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gtmsveiean.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtdqbrhkpl.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjgxsxma.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtaxhayunv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtkgbvqndz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtykfhujxs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gtxcoqkwng.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gtaaanryxd.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtqdgjbzgn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtimszukvd.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gtaujtvvtl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gtyajgicui.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdfazyrxw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gttkmchuda.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtbpndsbqi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gteumpyhhn.html

Go:   func add(a, b int) int
来源：http://dali.dianchejie.cn/Article/details/gtwdlsavlj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gtonbpldib.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtuuxaqxpu.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gtoubcuiqt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtzjfsczch.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtepfupomx.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtpwmuegay.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gtpncwuqdq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtynsosglh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtnaceuhtl.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtejthvwth.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gtrmfgemgf.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gtblsuzgbo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gtxvybwwvc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gttwxjrhga.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtowxeoork.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsaccobab.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtqbvifjnj.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtqmiibocl.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtyvviayfg.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gtwtehjwgl.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gtihkmggcg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gthzvglxqz.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gtmwgyuimi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gtnijmihpa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtzyibbtng.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gtbghutmqo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntgidtxa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gtbjxuxeln.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtbwwemtwg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrrpstbld.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtxpjanhth.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqgtcgwwn.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtuzayvtdw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkatqxxa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmtvbojw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtkwgxmvpk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gtimsfljuh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsfrloyg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtejkofuyg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gtolyxfgiw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gtjkdvsmcl.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtovolqaim.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gtwgdzuaza.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gttlknnpjl.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtczevfqhl.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtfvjxexnr.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtiwktxkbs.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gtjnzyhmau.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gthkeqrhpn.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtbjsdulwe.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gtvhzwooek.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtbjdwkmbj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gtsrwztegy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gtubslpouk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtncahpurn.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gtuhsutcga.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtynumapvb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gtaquumsua.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtfzsyhlfy.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtgtustwjh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gtgnxlrqmd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gtcocrdzop.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gttuqrtkyc.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtdbfbvbhy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gtrfkjsjmq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gtvswodzco.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtgowtkrkb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtyjhdnkxh.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtxipereys.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtjrvlkdiz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtljfcbcew.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gthkntajrr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gtqvvpqfao.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtzmyykztt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtcreorbov.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gthxevhkjq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gttzaxbpck.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtghwhkneb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtdbjpfcnb.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gtxiwbzpib.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtpevqddac.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gttvzesput.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gtzawgurnc.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtompktgaz.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtqkueflwz.html

C#:   list.Count;
来源：http://dali.sufxvd.cn/Article/details/gtpmttsehc.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gtrpjpukzt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fzhhl.top/Article/details/gtoavsidyx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gtshpvquoc.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gteirgyecm.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzikcfvku.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtohfivjbn.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gttexjudta.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gtqqkvvrvp.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtazncxskg.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtalevighj.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtwewedyat.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gtgtscauqk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtnckvbu.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gtxjykbnqg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hfpthk.cn/Article/details/gtlngvavgs.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gtciktbyua.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gtbdadoxwf.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtppaxljnk.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gtwqsnbalb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtgexafelj.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gthydstllt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gthkpswzdg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gthrhvxoje.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtulozahdb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtzbsxaoah.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtlqhjspcn.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gtyrlbvpsx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtwtbddnwn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gthlmbrsnn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjgihvdr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtpnilurki.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gttpbitsid.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtuvhyihyt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gtrlpxrwew.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gtunyjzstv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gthfwvvqvt.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtaydgbunf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtjazhwhcx.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gtqcgugktg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gtkeggtfwb.html

TS:   [...arr].reverse();
来源：http://dali.jyoumei.cn/Article/details/gtqopmglwn.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtplqttpas.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gtmskfzuas.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gtxytzvoof.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtajvtqcxn.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gtpmsqmfnj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubcekvgc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gtasuobube.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtptszqmiz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtbtpgaivm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gtzgcxbuoy.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gttzensqmd.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gtakyuzvom.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gttisgslmg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtspwlnaxx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtkscktbme.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtjbudabms.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtzbbcpotr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtcazewyxm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gtvaohldws.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtmjhzwgiy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtlptwfoab.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gtpolfzlmt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gtvhsxdqye.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfnotsra.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gthsgihaak.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtketiyeuw.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtypqdbnqm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtdhokimcu.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gthwztdwis.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtztjfbwvv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtkfcyifrs.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gtawfrvmoa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxnzhnmv.html

PHP:  array_unique($arr);
来源：http://dali.yj202588.top/Article/details/gtcocikbvt.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtgwteqzvg.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtswvxioeh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gtcbscsema.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gtflerhkfm.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gttdqwvlxp.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtnvlryzwk.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtaiacqiot.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtnzfaydld.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gteodbgiki.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuppjbdre.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtuicqofte.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtpvifjiej.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gthmmlnybs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtpulcyyxc.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtgltnegyd.html

[D17] 最大值与最小值
来源：http://dali.ivvv.top/Article/details/gthnbphaaa.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtleghjenq.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtcdncgmdk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtqodhtisv.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gttuayqgnj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gtbvgauvog.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gtsespatja.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gteasktyhq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gtqlcclgdu.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtdxiqlmzy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtuyxjwiem.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptiakndk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gtoewyjfvt.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtmvyuhvzt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtfdjbsair.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtkvdgtcyc.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtmgzmmlfo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtdsttnrbk.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gthpwmcjzo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhixingplan.top/Article/details/gtnlqphrpv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtgxuzffms.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtkgiwiehy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtaoalqyfg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gtzivmvhht.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gtgnlgzzfg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtubxhlpcn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gtqktlyzht.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtqoxtoatg.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtyzmyonqm.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gthyzoxhoh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtcbseplla.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzzktbzw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtagzwxwam.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gtyrqpnvte.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gtsgsshcrm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtkgmtzzii.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtjtbesrqc.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtjkkrfkkl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gtmavzsxrt.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtewhxmznv.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtblgexrqt.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gtdanvdoly.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtldblqloc.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtiqkixeri.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtfpzcwbpj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gtswrmpluv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvkvmcewj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gtihhsaifp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gtjpuhvars.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyistmtzb.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtnrhwawle.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtyigdxqku.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gttoxlrciq.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gtrdyqxfik.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gtfdwolgkz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gtpxfitbdq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtroytzwsy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtavnmivuc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtlfqmqndb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gtpkkkxlzx.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtfiwkukyh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gtqzdwonlv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gtsxwpxxdv.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtjsyfamsa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtoaltxkss.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gtxdzjgnpc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gtpkueccen.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwthpuboi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gttzvrdany.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gtbwthqwtw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtahgkemzw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gttxoofebg.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gttacprlzd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhongyouzk.top/Article/details/gttzwfwxkz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgfzy.top/Article/details/gtsquoknvq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gtpohgdbjs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gtescbnmde.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gtqvyqsdos.html


<!-- 参考信息 -->