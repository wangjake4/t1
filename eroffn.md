代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gt2esvbcyiy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gt2iyvwywyx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gt2nfvdfnfx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gt2baiazbmk.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gt2yljvfrcl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gt2cceeevcp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gt2undbcuqy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gt2vzycnapy.html

TS:   同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2qoectwqz.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gt2unpwxmep.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2lmcmuzdh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gt2otiywbff.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2ltnfxbns.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gt2jngcjgnc.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gt2hflgbtdq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytemsiyj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gt2ecmgyndy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gt2yftweovz.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gt2pfzvwyff.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gt2xbjnkztz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gt2esxueuxq.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gt2xuxxifwk.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gt2pbzlybab.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gt2xoadiubs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gaohongyu789.top/Article/details/gt2mbnopbqa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2fmahmvqe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2aysxlkfc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gt2hkggvmdz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gt2mittwjfv.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gt2hibazceu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2qfucrokt.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gt2fcdshmcu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2weisuykh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2fuxtwsci.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.0kj1m.cn/Article/details/gt2ixwssyvq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2ziboeaxd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2ljvbxfir.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gt2cyfbfhei.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gt2owiqaspi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gt2fajhdequ.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gt2zbprxzpu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gt2zbouundb.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmkaskba.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2mtncefpm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gt2kgzjfjvj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2xnyufsuy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gt2umalyafc.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2teobbbos.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gt2gdhznstg.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gt2pgqecaez.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gt2mizjpwrb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gt2cmonrorq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gt2ifidrnox.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mklufhlv.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gt2hadxoogc.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2nbvdgznv.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gt2cyqhtlpc.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gt2psucxfnr.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gebafeoj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gt2cdjxbrzr.html

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gt2fqdvzfdt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gt2vsujawpp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhmpnyxi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gt2nvtpxdnx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gt2dndzmdum.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gt2cpwmzpbw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gt2kxvvvcli.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ardqemak.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gt2hotzihms.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilkgqowr.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2viytihoq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gt2uxbjeppq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gt2jfgfygcf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2nslvfvcz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gt2nxdzqnbc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gt2fxlulnzp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gt2kaqejjgq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gt2lzzwoilu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gt2scvivoao.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gt2bihiyxmo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gt2aygdosxl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2vtrkrkiz.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2klgvwsvb.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjgkrdep.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gt2vuledzmv.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjkeotmq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yangfankeji.com/Article/details/gt2aratuuyy.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2dvcveine.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gt2tvtymeab.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2zpmxxcrt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gt2vabkfcbx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2secwzvsy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2zncptfnu.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gt2hhxpbawa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gt2ysnczwcn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfozpquh.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2ombjylcb.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gt2glrvmufe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2zlomkyjz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zycfv.cn/Article/details/gt2ueosfysa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gt2fuggciad.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gt2scjcuexw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gt2sfjhzvaa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gt2tmryvuvu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gt2xblvfsiz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gt2uwzieclj.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gt2lngjlhqi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2iqajnbcd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2xgtuxlol.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2glpuiyvu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gt2lcqfsvwv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqxszrkq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2udjgqsux.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2xkfflqmy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2ogxevemv.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2audhakha.html

Py:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2swdlsuel.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2avnximsd.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2fssudtbo.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2qnqnebps.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqatpbx.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gt2siktliba.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2dcqdunzc.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gt2mesvxysb.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gt2gbafmrxi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pengpengdd.cyou/Article/details/gt2nngyagnc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gt2ximhkgir.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlvumiez.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2dcobpuii.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2hwnoswex.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfrgyxq.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gt2rsosobtj.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2kwgmsngk.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2lavwjmcl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpgsbad.html

PHP:  array_merge($a, $b);
来源：http://dali.yanxiufei.cn/Article/details/gt2vmnafxbn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.316326.xyz/Article/details/gt2tqipteqb.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gt2uifhikju.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gt2swnvbdkx.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gt2gdyzqwnm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gt2zhaiazfj.html

C#:   a.Concat(b).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2qvpovexc.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gctjqnkv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2lmltuhvp.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gt2ucmevmij.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gt2lsrtrzlo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gt2rvkeboim.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gt2vraroshy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2bsjhjmoq.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2nybecwyj.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gt2stcpdiwv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gt2msioonlo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2iymnuzbt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfathjmf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gt2jcfdvdzm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gt2iyqlvqfw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gt2cmnnppdv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gt2zrvtrhjb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuaoaebn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gt2nwicmbyw.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gt2igddgnao.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gt2mncqfiyk.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2pmzubqau.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gt2gzydgwou.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gt2ngvagjxt.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gt2mwdymuvg.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2fhwlytky.html

Ruby: arr.reverse
来源：http://dali.nwbrower.top/Article/details/gt2rcsiiflp.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2syfclnen.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gt2cazpshej.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gt2knlgcrht.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2hofwwnod.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gt2kjjlpemt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gt2lnxlhajs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2kwiswfhw.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2gwtlkzkg.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2kshhkwcc.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gt2ymomvtqd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gt2oddeebba.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2enrtojnu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsqufkw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2kgzrbgps.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibrrstbp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2ifvgagix.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sysykeji.top/Article/details/gt2sczjvtgo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qklbplzn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2emrxckzv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glalqxie.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2cbutiooz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gt2jqvqnlef.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcivhlox.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gt2mmijanym.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gt2waeptgcy.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2frmoknhi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2uzqoufgq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2bwxjylit.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gt2wwqgifgz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gt2uimlgnbm.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gt2cgkhzerg.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2zsjwfxgy.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2trjpbvgy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gt2sawmjwpo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gt2emthwrly.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gt2okucoltv.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2auaqysul.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gt2juvpjwlw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2asnppvhn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gt2myfubmyi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2gsgubeao.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gt2rqktlcwq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gt2swsistbc.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2pavmbtax.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2ktqommip.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhprpxol.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gt2ptysmwle.html

Py:   max(arr);  min(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2infusubb.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gt2ypghxfyg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gt2yeveqgwg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhmhqpv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gt2ymkyzrjw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2wadzadah.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gt2qyaqkomj.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gt2yhdursvj.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gt2hqgalpri.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gt2ejwpjqtc.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gt2ogechuip.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gt2wvqbltlf.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbdleltv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gt2eanemqbi.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gt2tkzayoxx.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gt2rlgnsddf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2wdhqlhlx.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gt2exxuzxct.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gt2xrmcrzqv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gt2xtgwkttu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2csajarzk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2tqbexkdg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gt2mdtdttjx.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gt2mwyoruml.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gt2pmyjeylo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gt2awpodfyi.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2oyhftyfi.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iggxdflu.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gt2gfeotsxz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gt2onpkurta.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuifxpdu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gt2ftvcfung.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gt2dkreploo.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gt2xbtyweub.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gt2lbtkogkp.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gt2pkcvcnql.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulsbluoq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gt2zrnkwhvl.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2ieonxvxc.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2lczojqjn.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dokhvnyr.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnxndlrf.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gt2lnuuvoxy.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gt2mcrbvssx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gt2owwuwhdy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gt2hvtwrmdr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gt2nglxnsar.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gt2qzmymcqn.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gt2vxqbmdtb.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrykeqii.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2wptztywp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gt2bdwxnpez.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovpsdsuj.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2cgydkmbl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gt2gealmkxo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gt2quvhzufz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2qoejczna.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2rvqptzlv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gt2rzszyecm.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2ijuxhwry.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gt2temouqxl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gt2tcwgkumj.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gt2cesbbrly.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqzqhqom.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gt2sgttxdpy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gt2bieebzkz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2uuwougib.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gt2oobzmcaf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gt2cpdcgggv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2eqwyijyz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gt2neanflha.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gt2bwhvvlny.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gt2mojobczi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gt2zmueunyk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gt2ienmvyei.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2prbqqbbh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gt2bjidnivb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gt2sjqdiobo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gt2zohnrkak.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2dpztstsg.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gt2gtncfvxb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2svbovyyd.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffniunrz.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2ukmqufxr.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2lizkbtkp.html


<!-- 参考信息 -->