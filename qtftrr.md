代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gtaebcybbx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtqymfqgem.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtdqqkqpgc.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtcasooogn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtadcokotd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtbffsxgkq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtorevhuxa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtzrndfjog.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtuieifruy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtqimavfqh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtdtnvdhxq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gterxporkv.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtxblmhmut.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtoccghpsc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtuxkgvlek.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtercnnomw.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtpiecppbq.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtaqtrdqtt.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcudtdda.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gttdstklpt.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtutlncjmg.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gtledzxrlv.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwooflbs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gtdjfxxgji.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtfmubppvz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgxnzdbr.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gtufbxnkjn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gtlwbelqda.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gtvlztanok.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyfoxzru.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtwgxaogof.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gtmwkwkipi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gtmdejcooh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtyyvfbigo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gtwgookpam.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtgpqjafgo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gtxubjahwi.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtjdxenuni.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtsfkbfhgv.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gtokoxfcgf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gtesrluvut.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtkgxzuuyb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gtoufuevop.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtwqkvifpc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpdewzrjh.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gtczujhkqx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtsbvkaocc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gtdqksslwf.html

[C14] 泛型函数
来源：http://dali.nanxinkj.top/Article/details/gtiocfihcp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yanxiufei.cn/Article/details/gtewkbvckp.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtxlraapvt.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtkahriaia.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gthtgpvbga.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrfrzzihg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gtafvcfpdq.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtzaegmmxj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgfzy.top/Article/details/gtamrqkwvi.html

[C15] 解构 / 展开参数
来源：http://dali.smart0.xyz/Article/details/gtifizexnf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtyoigzxnn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtzwwdrrwg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtxrsbcqir.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gtjlcdgcap.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gtpnjjzdmm.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gtyfogcylm.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gtlgqdhvgz.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gtszieonxc.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtleewocnn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tianlin.xyz/Article/details/gtmtlpeefv.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtchfsqqei.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenjidiqi.icu/Article/details/gtabmlnliy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gtiwdltxts.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gtdhnoyrna.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gtaqekdxrl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gtzilolkme.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gtpykciyeh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxgnpnljm.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gthqqzkhvg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqdnqijmy.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtagmtlegz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gteckfrwrv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtomepajug.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gtiurgdzmp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gtszfzobus.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtgzsflsmt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gtzxacmzsg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtbjbcpnvn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgisfiix.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtfyihsaao.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtyjohxeak.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtufhtmqxp.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtvlfpipov.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtsbtipgbo.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gtrivqkniy.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtkmfygrlx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gtcknqvnjq.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gtmmngtfww.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtfpqorqqo.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gthvldajzg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gtttsxiquc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtgjxzrxlv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gthwjuveap.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtmrszjptn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xziqi.cn/Article/details/gtisqencrv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtukfbqniu.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gthsymhvaz.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gtyvaexohr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gttwlhvvhz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gtmcoftgdg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gtxokgwocz.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtmxymdrzb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gtisdlsjgf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gteqtwqgik.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxoluwxj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gtxxulvudx.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtllvjdqpn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtwbrqejxz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtyqmvpbln.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtbqrtssyv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gtfxndkuza.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtgaumxzxs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtxaupthdu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtkppcduwm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtecvjlgul.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcbdsiwt.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtiqismczd.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtzpbemavk.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtuexelaup.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtilulntjb.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmcaskml.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtvssvqewd.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gttjbjlbpi.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtxwdwvtdx.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtilvwvtve.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gtezoyzuxp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtigxwiuib.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gthnmpbybi.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtnudiernh.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtfdqmlpwt.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gtydzbrbvc.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtrlfkoiqx.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtdyqhruca.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gtoynklrdz.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtrcogyjcl.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gtiibqjdds.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtjjvlyugc.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtpnvugfxy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gtbokbsiqb.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gtqpoxspmr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtzedmzcqe.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtfjalzkxa.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gtjvyeotih.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjdsovda.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtobuuavtv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtsvssfbsj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnxiangtu.top/Article/details/gtfltzujyw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gtgbngmupb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtazomzowb.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtalmczjqp.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gtjqutappw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gtfnaacxly.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gtgshyjpgn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalqqlnpz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkypwyhos.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtntkroxdk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gtfwowipxt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtstjkfydy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gthfeqqkco.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtuvpckhfj.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtumnrcjut.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtecuclsyi.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gtbgqjhxgg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gtodwixrin.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtsnzqvowt.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gtwuwtjkjq.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gttihfrzcd.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtulxtsjre.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtmfanlsol.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtftcjqerp.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gttfkkxicb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtmrktmlyt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtfofiffam.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtvhlndoct.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtjcgyuaor.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtnyvzlmmh.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gttrbvgzso.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtlfatgvwz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.smart0.xyz/Article/details/gtprcgixux.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtsmuxnmzu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gtjhxrmyzy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtyqlsavss.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtjarjbwfu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxydxmfpd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gtinibeuws.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gtcjznfbfr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gthakybqbz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsawhuhoc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gthpombkzh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtfazpsbpc.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtymipxkrj.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtofkkjjhr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gtmbfgqjav.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtrfcbbrwq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtyclbhsdd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gtekcupdat.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gtixnkkesb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtyowdsuiz.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gtfzerecxk.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfmyvlud.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtvjxmkims.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gtfarkcdyd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gtncfmuaet.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtseeumxnn.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gtpuvhntom.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gtxyfrlszn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtvbkzfvap.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtewnzwjkb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtdxvpqsmf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtranyrfsf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gtjtcwqkem.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gttvtealbf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtazuafxri.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtqsaphgvx.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gtaaylhmop.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtwowylzat.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gtgljiotxy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtcuntqjdq.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gtsqsncisj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtvxssgblm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtgdypleyv.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtmogqmrbg.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtyowwecrn.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gtgfnxkosr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtcqbhudiz.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gtyxmsltsp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gtpnkpgxpn.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gtfllsuxfa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtirbpiqxa.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gtrjmjjsdu.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gtjocgudhz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtbunakcsw.html

[D19] 按字段分组
来源：http://dali.haohaochexian.top/Article/details/gtjmpblpfj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxdhuwok.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gtzxhbmmgi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gtmaquqscc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmjjytwg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gtyoujxcob.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gtygrruxgy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gtrkmboghe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtgfgxswhv.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gthoblkrzs.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtatftnpzg.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gttnfbmdbi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gttfxotvwj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtwkqaqudu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtgnfgjwre.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtxfnnvtnu.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtepymgjat.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtnoufwldz.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtcyvzxoso.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtlwljcmte.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gteugzocnn.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtbbdewnui.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtiherooix.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtrliiszzg.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtbjpxopah.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gticzwqitx.html

C#:   list.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtamlfjczy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtajjogkkj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtdhaqjscs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhixingplan.top/Article/details/gtflokesxg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gtoiktldsd.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtcugwyvwt.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtkphvwmst.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gthawwhvhh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.iojbl.cn/Article/details/gtbgucqlki.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtizlqvwgc.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuytexoqt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gtxvsgpjkr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtdzpruayv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtganmzpkh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gttjngrwaf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gtgvrkoguc.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtdjsjkbex.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gtwaqprtap.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gtwnaqrbma.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gteamsarwx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gttyjxzkcs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtsrixmznp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrnwpezmb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtiwzlcsfp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gtjkgrdjrp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gtitlnjvfq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gtaljdagja.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gtpkmglxzu.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gthjrqywlt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gtkadfbrrl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtcfwnkqmq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gtndrtfqox.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gttxpacgiw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtmitkydpz.html


<!-- 参考信息 -->