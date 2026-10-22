代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsprgbdt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gt2yhgkgvit.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2idrjdgso.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gt2rvisqlxq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcszvyhr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2kaufglnq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gt2ezdlaxid.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gt2wmqkkcje.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2niwsonnh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenlongwang.top/Article/details/gt2jjmipqhq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gt2lzqlndkr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gt2qlivoalr.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gt2xtostlan.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gt2nftaqixb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2spctfies.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gt2srdlzxlq.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gt2rtzkdbmt.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2zseefzmc.html

Go:   花括号块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2jlsabvay.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gt2feilbvey.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2qtcpchsy.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gt2bxagurzj.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gt2yotdfieb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gt2puszkqba.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gt2hqecmaln.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gt2efosmclw.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gt2lbfthlgw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guowangkeji.top/Article/details/gt2ucxanjfr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gt2zvrzgnou.html

C#:   using System.Text;
来源：http://dali.hammf.cn/Article/details/gt2nbwxobnl.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gt2uhptudau.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gt2aqxktwtp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gt2avhpcxgy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gt2asfsdmat.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gt2kkkhqaeo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gt2rvrbhhyc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gt2iscqpdxt.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gt2cgwstaco.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gt2tbjmyhyz.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gt2ezhhgziw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hfpthk.cn/Article/details/gt2ebbybvgp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2ilcmmdxd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gt2mgmfqdtz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bcxkxzcm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2anxnxsgf.html

Go:   func add(a, b int) int
来源：http://dali.ivvv.top/Article/details/gt2vxfuflbt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gt2lhzjmdva.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gt2bmxtbkup.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gt2gfgacayk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jajwqvol.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2rkykgexo.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2qvmewgqc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gt2oszpmodv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gt2vyhbqgfb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cheryme.top/Article/details/gt2pqygizeo.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2klgrrgqs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhengqikj.top/Article/details/gt2qwymezym.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2giwldbmb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nivzjrdy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gt2bqeryeop.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gt2unxmxhkt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gt2juagbdwy.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gt2viahjqxv.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2qtkomwoz.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gt2slwqqoio.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gt2apzhsgtq.html

[C16] 函数 / 方法重载
来源：http://dali.gotoacloud.top/Article/details/gt2cdwgtzru.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gt2heufxnnv.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gt2pmcseplu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gt2iapmvoic.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gt2jdrgnxgw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gt2nkzoaewp.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gt2mbwpehrt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gt2mnehkrly.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rsttsbyh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2uhgtcxqi.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gt2idrehavd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilpgpsos.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gt2ofoifvwp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.snrcjt.cn/Article/details/gt2xauwjded.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znexszcz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gt2hovwymxk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gt2wihgacoc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gt2nlmolfjv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gt2xgnobwin.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gt2dayevdqd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgovhjtk.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gt2euqbytep.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ivvv.top/Article/details/gt2spzkrtdh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gt2rwfjguik.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2cfdxlnud.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gt2uitzdews.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lursdkux.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmsjacoj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzqvlsfa.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zszgqock.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgetwqrb.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2asosqsay.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gt2skgqwqxi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhoulong.xyz/Article/details/gt2joqkvrkf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2hrlnksxc.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2eznwdadl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2cibmmvst.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gt2mpbaatgn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2jmlktwtb.html

[D04] 删除元素
来源：http://dali.zycfv.cn/Article/details/gt2lcpsdqkh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pycfn.com/Article/details/gt2qxehzbpf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2agzajsjc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gt2ixmstguo.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bglszfmp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gt2wbmrzybz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjeixhnf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gt2bcdrpfbi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gt2pobqbqpb.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gt2jvaqlagz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztjduvtc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2hdswuzcp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2aysotwcb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gt2rkvwehlr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gt2jzsuknbq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2sywwamnz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2cgrmhqpv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2myncckae.html

[D06] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gt2xzhpsrdq.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2svlesowu.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2tltjbsqu.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2xnmqpqai.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gt2dcdmukbj.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gt2krwdbylm.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2xwldynpy.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gt2kgaautia.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gt2mesynskf.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gt2svnzikqc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2almtlmyg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2ctdikoki.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cywdjwbm.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2mecthvbm.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2rldmrfww.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gt2jzgtnxfb.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2ygwtcgtq.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxinkj.top/Article/details/gt2ekhszbux.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qeiuezct.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gt2uyqmaduh.html

PHP:  array_merge($a, $b);
来源：http://dali.yanxiufei.cn/Article/details/gt2naerdqdj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gt2ozrpzwre.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gt2pbbgjxud.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gt2srcsmcyd.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gt2rfhnlydz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gt2fcaacitq.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2hcylxgnf.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gt2grveewox.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbidmnej.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvdxpgef.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gt2dkfeqlgl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kflzdqin.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gt2mpqlcsnp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2bqfeqtvn.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gt2ydalpzpe.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gt2bufudejx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gt2svhsorej.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gt2zsohaegf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gt2havqymfj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2utopinyx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2dgbrylyi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gt2afuqkqyk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gt2jgujfzli.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gt2emegersu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rifbdapy.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gt2supcmdbp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gt2wqbmrjec.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gt2icmeybsl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2temxjyjg.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2wsgqysaj.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gt2lrbkpeal.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2sqokbexq.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gt2lfjinskr.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2tipbiyic.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gt2eluuemat.html

Py:   arr.index(x);  x in arr
来源：http://dali.hfpthk.cn/Article/details/gt2dezgdael.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2gyxrzntr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2bncckwzm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2jrzcqpux.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gt2ffbrdegs.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2naqvkvfe.html

Ruby: arr.index(x)
来源：http://dali.chenlongwang.top/Article/details/gt2tcmsgkxh.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gt2odllwoby.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gt2qicklcpy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2kgscmijt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gt2ploihscq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2evipdubi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwcrmwva.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2cuwkgbki.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gt2puzcompy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gt2tbmsdjfl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2ljmksiqd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gt2vfkipibs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gt2aswupppz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gt2ekmlltif.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2thqybqsn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2jaggqler.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gt2pvpwrxnf.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2qqaaxfca.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmwhtzxq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2gpmmrcdh.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gt2ifdsnkps.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmpellbj.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgjnbfax.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjtsebyc.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2wzbxeygn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gt2pzvagvtz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gt2ooxobqcj.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gt2wveewhqz.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2hfqjswox.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gt2kwdjtdga.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2ilwuwcef.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gt2efasspil.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2miwzigjq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2ltcjejwh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gt2eeiuzrxe.html

Go:   // 手写循环累加
来源：http://dali.smart0.xyz/Article/details/gt2amxhgrsh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gt2wlkwyqrp.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gt2sufbqxye.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gt2wfrzwcsd.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2rshhjiqk.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gt2gzvklfbu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gt2cimbhben.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gt2vchevddm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gt2usosvzym.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2lnmsyfuo.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gt2ixystjtu.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gt2uvruirtq.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gt2clbczrgp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gt2urubuoaf.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gt2ajauarld.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gt2nwlxwwap.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gt2rqtfuxwf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gt2dhankzan.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gt2ilhclgje.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gt2wynikbke.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqorwzyh.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gt2cnxdozao.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gt2mesnonbt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gt2rrulgwzq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gt2ijmpppvx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gt2digyvool.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2juybrqtl.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gt2medtcpfh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdbshmet.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gt2aulmvapc.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gt2lsdjfjcs.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2pbsguwqq.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2rfyqrrqf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcktigtg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnvebwgd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gt2ywzfpaib.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gt2regtjdss.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2lukcbyqz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gt2rkagnbwa.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gt2kflassjd.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2sofvghgd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gt2iwhvbpls.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2qqjwsamw.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvzlsstt.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2jqgkgjns.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2prdobtpa.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gt2lqhcaojk.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcjlwdbf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqlnsrgr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gekankgz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gt2iryhqfad.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gt2fgrviewj.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gt2jlyumbtp.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gt2bpyrakmd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gt2jhpovsmc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gt2waayuben.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gt2utsmymvx.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gt2rzvvujzs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gt2kyjvdwru.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozttnxsg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2wcranpta.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2gkvqsglq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gt2vwqaaryo.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gt2dubvfepl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gt2elobctyg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gt2tbwpmpvj.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqxcswwi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gt2qiduhdjr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gt2pgjzxcog.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2wvvfgsis.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2srekxoje.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gt2qhlvixqn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gt2ojjpulfu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gt2swpmwaon.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gt2ewtqgtud.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gt2ayqnehrl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gogol.net.cn/Article/details/gt2vltwpqle.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gt2lmywajhp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gt2htqbscrq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gt2iqqetvpf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2hflfhgec.html


<!-- 参考信息 -->