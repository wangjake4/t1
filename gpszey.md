代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsintnhbc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtxlygsfpm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtkejqjach.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gthzkzktef.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gtdnatwubn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gtepyhhndq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gtgveinlth.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gtobibhlmv.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtethmbnwz.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtoshxqgkl.html

Go:   花括号块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtoskxokkj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gtgzfujxwi.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gttickudgl.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gthbaksyap.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtpuxuqgxk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gthqqfumjm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtnlvnjdmy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtgahjzwuo.html

Java: import java.util.List;
来源：http://dali.hnxiangtu.top/Article/details/gtkcxekemm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gtrpiylfwy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeyylxaz.html

C#:   using System.Text;
来源：http://dali.birdmap.top/Article/details/gtecijkaez.html

[C12] 立即执行函数 IIFE
来源：http://dali.quarkkingdee.top/Article/details/gtnlzcdcyl.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gtjauixkla.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gthnzrptlw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtkwvjpptj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtuxsebumv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ppjwa.cn/Article/details/gtpetqpmyh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gtejltfkmr.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gtsickoktk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gtmtpifsbm.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gtrctycecg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtfincmfrk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtstslpgdc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtkjmtahio.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtjsslvkmn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuqradmdr.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gtbedaklbf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtgdecfbkk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtwytvoult.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gtuoiyeakb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenlongwang.top/Article/details/gtouanzrms.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtoslltuol.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtymsxthmf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gtuppdtjbw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtfvfvbehb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtbvwsyygj.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtlfxbzocg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsjnjpuv.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gtdiqpnlox.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtkgakauoo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gttoplreju.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtukwoxtnq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gtrhytupup.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gtlhmjdecl.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtwyzmsidr.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtrponjxjk.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gtlaednjof.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gtkwjecxle.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtnlqtiwmz.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gtilcanvjz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvbhitpu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gtjqaeixwl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfthskznr.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtuoshubqz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzccrrxg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtdxknfked.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvvadhxln.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gthkygwizq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtaydtssqn.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gtnekxupdx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gtmshmowod.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gttvnngtic.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtoigitvbw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkjjwamo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gtptglwcve.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtehtwhvga.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtnhmqbawj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gtfwqnwumd.html

[D02] 追加元素到末尾
来源：http://dali.zhiwuduotai.top/Article/details/gtofznpxog.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqrhyerl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gtnaeagkea.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsdwnnjn.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtjhxslwfb.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtqjeudspx.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gtihdxfsze.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gtgckkyftm.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtpkfvkwzt.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gtfvgxhroo.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfdqkcbv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtwepbgroq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtkktelbde.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gttsdhypca.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtcznieilt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtxtjlqcsu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gtbnccuunu.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtaswrrqxs.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gtgftgmrzh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gtkssfxfum.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gthxaymavu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqtvumqn.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gtgylgermf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtzeugwpdv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gtsklivsdi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtjnfoutvk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gturkrsdxp.html

[D05] 访问与修改元素
来源：http://dali.ppjwa.cn/Article/details/gtitmukgnw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtzannitgp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gteposyfoz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gttverevde.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gtcigrvvip.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtkvdvwhhz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtmzyricwe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzmsqvat.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtuvuqwkol.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtflenbdjf.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtdjaahmtd.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gtmqoluhsf.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtyjvmzwtz.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtguzxlavm.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gtflphozpo.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtxrqiwuvc.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxrwhjbc.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gtxdizjqcm.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gtwzpufzmn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gtplsmdknv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtqaqdkpta.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtjwojsovg.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtmwqdcikp.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtqqnrulnw.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbdsjkhr.html

Ruby: arr[1, 3]
来源：http://dali.hnqzz.top/Article/details/gtmhgquuyu.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtzpdzmgqx.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gttkngtnad.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtzzskunwx.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtjkuogjfv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtngkwosxf.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtkapultsp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtvxbumuud.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gtaucdetir.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtennpeoiz.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtavgpuslj.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtaahpdmlu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtxhgtyqsw.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtaubhwarf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtgplsqpmk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyierabn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gttjmietjo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwgvaeqi.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtitvydvhv.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gtzsfosrvm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gtjhlbgyok.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhmlpnou.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gttfuczuez.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtsqasonuh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtvarbyfqr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtsmcpwyle.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gtojjzvmrg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtmbquafsa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cheryme.top/Article/details/gtxjbfqjxc.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gtwgntollk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gtgfjlkynh.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gtpgavjzuu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtxdrsivpw.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gttqgkahtc.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gtqvstlgcz.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtnrzvryjx.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gtpjeotptt.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gtbggcqwyv.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gtsvcnfbfy.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gtjddsptws.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtdtkslcev.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtsspfdysd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtlhydkbbt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gtzfnyjcdt.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtmvqhysst.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gtqunbqqjb.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtgzzyeqhd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtcdemngxj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtfbondbae.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gtfqodkmdc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtzznajepo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtdpgiljft.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gtialihtcx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtrmcallhn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gttjkkuvwe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gtfsaksbhd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gtkpbfqgyl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gtxwhxiinq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gtmdpebrfj.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtjvvhjlfc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gteozgvaly.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gtaiuktxvq.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtenychurk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtfcodwkmm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gttagqnvfv.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtmykcfect.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtbhqqlogj.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gtnlggjjyo.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gteceqwypi.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtymiqemsr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtsiaekjoy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gtywysusho.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gthkzipssz.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkqsimvf.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtyljjfooa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gthjjjapis.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gtacptkvlt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtqccybvng.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtdelode.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gtsrztyxrs.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gtsccdjxyc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtwxsxxyxk.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtdcjdrgjq.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtiaahejqn.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtrgfycwjt.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtdidrcppm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtzhjkcqqy.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtugicfarj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnxiangtu.top/Article/details/gtcbtrhgno.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gtmrzbjpxb.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gtojwctskl.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gtqzufbpdx.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtrfachqqo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtyfvxojvb.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtqrjzmrvi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gthfgipolw.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gtsrimqrzd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtbrzxsvni.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtxgqkgzbh.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtscjleikm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtvqehfcrg.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gttrynhjgn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gtcbtccwqb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gtxlvmgeem.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gtglgoqewl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrzfipke.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gtsbvrbfmk.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtmsewtqpq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gtraasfvsu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqijnyvj.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gtaserbzmi.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtikrfdqby.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gtpvraqnul.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtzworbqjy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtgaahvwzu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gtzbuzvndl.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtdbzrskmb.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gttsqciaar.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtxejdfzhq.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtprpxtypb.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtbnvtkgjd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gtiwfpqvpu.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtatuksuge.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtzzldmved.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtgjytqcpd.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtfcfdiblv.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtzyegwntc.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gticvxponk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtyipfbasn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gttkmnziyj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtsgzpusrc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gtijqlatuq.html

TS:   [...arr];
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyxtaage.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gtbjnweygf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gtmjexlyps.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarcrrglf.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gttlhulilx.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gtdfttguwr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxzirfcf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtxvcnmfdg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtxzicddsl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgxmoqwi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gteezctlef.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabioahxz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gttezfkupf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangshuangyany.cn/Article/details/gtghqdcbmh.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gtefhhhjeu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtjevvwxnd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gtbbungymw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gthhmkdnfz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtbsuybsip.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gtldnoluzn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gtlgidrbxp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtlowilmzi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gtoooxyzml.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtgiwdegsh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gtnsxyikaa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gtbgfqbwdu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gtiwzvbnbt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gtbliyczje.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtkebmowdh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwegpjhc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtqxvzhqvb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtpbzkdppb.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtjxrpfpch.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gtgyhvfjoy.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gtaanvwreq.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtmndlpfkk.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gthydnuizd.html


<!-- 参考信息 -->