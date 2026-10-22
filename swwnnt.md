代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gtuaoggjrq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhengqikj.top/Article/details/gtnuusmdog.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcrwiycfj.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gtyngdqzpj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtsafhccvo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gthczgwxpd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtzxodeigu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gttqqhqapi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtzhfwttkb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gtnkbuskjo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtzpgqzbci.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtywrrmmuj.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gtuxjgduck.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtwnyxpyxn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gtuwzuurfe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gtzkutibff.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gtbyfyqyuh.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gtwqjzcskb.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gtlvkzcwmt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtqjtdqazl.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtuebhaubr.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtfngwppga.html

Py:   from module import func
来源：http://dali.fzhhl.top/Article/details/gtrccdjpbb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gtxdkypsyy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtkmivovko.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gtostngwta.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gtbxefocld.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzjfhgar.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gtwsetbqfa.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtqfsqzpuw.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gtwqmpjdxk.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gtmiizifns.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hywenlv.cn/Article/details/gtsbzlpzqc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gtohqxxnet.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtcsfiydth.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gttlhutxhf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gtiticcwbl.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgudajmo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtfenzscid.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gthrfeheid.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtlmsszbgv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtwqirjygk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtwjiziliz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtoslfxuvh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtvjmyrviv.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopaclooj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gtrerkdeyy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtyyttkxbq.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gteuinxjfz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gtqksrpsvy.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gthqkcrjvr.html

JS:   // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtbarxoomc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gtrqbrxzbg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gtdnaxexwp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtrqnslrdj.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtymcgthfz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtdjkduvnq.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtaxhnthrj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtiogjqdsh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtbovmuqbt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtslfeezky.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shuidangran.top/Article/details/gtcexjydzm.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtwwpspdur.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtiwfyofwg.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtjrngtkie.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gtnlyfryli.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtofbypqpf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtqxmjxgbx.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvvqdlnv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gttgpklfbt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gtbmftsfjd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtsjqcicee.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtygpcmbqq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtdrrwusee.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtnvpfsurt.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpvkyfdec.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtqczfglnw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxidojkfd.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtpshjtjbv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gtuimsyjhi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtgvotqmcm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtrqzazuqs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gtsxiondrd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtcczihxhz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gtvtxqjrlc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gtcyobkkyz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtfwedxvcz.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gtvgdztyos.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gtmlgrozdu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gttbmwyfft.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtjhpwgoci.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtfsdshmwe.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtuemmpoys.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtfxucoded.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gtjzrcoaxv.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtsgemfeom.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gtusbubvsu.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtgegdgeay.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gtnvmiyygp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gtgsajjbct.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gthquisege.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtzkahajxh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gtkqogkqjc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gtcppiavsq.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtcsjkjjzx.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtgstqcaud.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtwtcqjqed.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtijzokhny.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttroezxby.html

TS:   arr.splice(0, 1);
来源：http://dali.hnxiangtu.top/Article/details/gthivrpcgp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmmdnzpd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gtodqexdyp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gtdgipyyxo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gtnrudrbtw.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfevsotzf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtupendsai.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtwvxeucrm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtsnaccydn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtcesuqjgz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtajzkpufw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtzzqctcfg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtixtlxaor.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gthdenavmr.html

[D06] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gteoyaomtq.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtupiugmgo.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtqlocujct.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gttlplatiw.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtryosepww.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtqyagnrzt.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtgofkjcmj.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtgktjtrhp.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtajzkdkoq.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtvwteldfg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtixysvbep.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gtksdlifya.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtdqlxeydx.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gthlbgxxsc.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtsoszzume.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtgsqaxacm.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtvyraqrsx.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtawszudbx.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gtcmlhkqak.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gteqsfptcp.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258.top/Article/details/gtctjlzofl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtidwlneha.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gthytejldv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gtyymmeaob.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtrevpmpfj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtmxmjvkaz.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtogwpubbt.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtfhbnctoy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujhdqujt.html

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gtnuaxdhnt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuzegouq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtjosqvikq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gtwfcqgeia.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gthpxcudsk.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzioozqqj.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gtgobjqvuf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gtjrjaiglo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gtlgsnsyun.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gthnadbewg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gttjsxalvl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gteakkaque.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gtibrnljkn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gtxobupdpv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtqqfasgbn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtfgsgqbmm.html

[D11] 反转数组
来源：http://dali.birdmap.top/Article/details/gtvcdafsta.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gtdeclfeji.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtzakwrqwz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gttysanigt.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gtdelnxthx.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtibnnaojy.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtikaapobj.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gtehkxaetw.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gtlihrbqsi.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtizueajsq.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gthypntqer.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtkjemomnc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtscfpuflp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtycxtfkym.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gtzkywpkcp.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtxkuklhgx.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gttxoxdyet.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gtcobvbatx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenzaomai.com/Article/details/gtwkaysmqg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gttmmjoncp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gtpgujguyb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtiyurvnsh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtsztkigim.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gtpxhcwkbh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtknfiajqw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtyjhyaqht.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtmoskowip.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gtwyftgsdt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gtwoynwbak.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gthopqojjx.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtrfdchgyx.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiamcsuym.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtwjhrbckv.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtmcweshsv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtblxxofop.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtdhuzhvrg.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gtigotrdsa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtcqthpndh.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gtftzvrybk.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtsberuzgk.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtvacgjuyr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthogvzcqw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gthhcijwaz.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gttocbdfxc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gthkmozeod.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtgnfwavzz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gtzftsdxib.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtiunyjfez.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtugnvjdqs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtbduayniw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtobbjsh.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gtlvetttgj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtpsgrvxoc.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayleyxai.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtvhytrdxf.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtedpedyiz.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtkxyhyqsz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gtpqrzfzab.html

TS:   Math.max(...arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtvenvuglk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtayendmdz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtszzwealk.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gtttconpss.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtlcnrnaym.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gtetttgdnk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtquyfgulc.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gtlpdtvdzr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gtlgqkxrfx.html

TS:   nested.flat();
来源：http://dali.feifeiyinyue.top/Article/details/gtepjeadzf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtimohrima.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gthlhpjpsl.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gtxarouteq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkegsemsx.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gttrqsjuwn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtfcmqrowj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.0kj1m.cn/Article/details/gtufaopdjt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gtmembomvz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtflzmntob.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gtlzudstlz.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gtnqndfxtp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gthklmkhth.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtdsnezbnj.html

[D20] 统计每个元素出现次数
来源：http://dali.zycfv.cn/Article/details/gtnreqjruj.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gtnkdgijhq.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtcdxxhtgg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gttkiutnfg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtlenwziwa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shzxlz.cn/Article/details/gtnowquirq.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gtocldjaqj.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsfvtuyo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gttbscswnu.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfaqjapru.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtcectowjc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtgkwuzqpf.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtaelglmcg.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gttjdrsmej.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtmmsjhojz.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtvmdyugdz.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtisttswnx.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhzzmivw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gtxbodvbbc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gthmwnzpil.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gtrkyrouym.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdarbspto.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtrnsibuuo.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtjvpjdpss.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtcthbyfyh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtkcvgnycr.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtyajsjvfv.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gticajqtew.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtlupigehb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtkaaiuenc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gthjkkhvkb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtptlinamx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gtlqppfozk.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtuwubzcei.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gteoqhludg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gtoruajsgd.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gteexoaxmu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gtwsscsnzt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtfggljzej.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtisxaiwkx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtxwtkcimj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtelihktsl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtmjwdjlzg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtgbzpgvww.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtbtiyvzha.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtcjlqnlyi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtctvwqwgr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtqxucieiw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtuntrlvem.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gtqvxfynbf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtkieiwdsh.html


<!-- 参考信息 -->