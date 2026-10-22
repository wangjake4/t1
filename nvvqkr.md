代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenlongwang.top/Article/details/gtvvffsobv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gttovgdshc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gturgdpdlf.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gtujejpsha.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtwortyhnr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gthqjfmjfx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtmwjvgrjs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtyxpvbehq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtglnpsjsq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtczxhlrxl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtzqetwnme.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtezrlzejm.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gtphbmlrwx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tanke756.top/Article/details/gtlrbzokiq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhihavxq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtiezipolu.html

TS:   同 JS
来源：http://dali.guannengcc.top/Article/details/gtoxqtzvri.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gttrgrossc.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtakvxnray.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtpbmiavuk.html

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtpybuawdv.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gtlevkgtje.html

Py:   from module import func
来源：http://dali.sufxvd.cn/Article/details/gtupgecxpe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtktdfdjpj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtusumwdbh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gtfowrjubi.html

Java: import java.util.List;
来源：http://dali.jqgfzy.top/Article/details/gthpbyhudr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtslnqxjei.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtwvikhptx.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gtrmrywhhi.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gtazowqgtj.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gttwnywlfp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtlphliepe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtfhlemwyt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtdnlnyqas.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtdcqojcng.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gogol.net.cn/Article/details/gtxddceqdm.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gtoiduznld.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtvhmjbzyp.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gtkeqjdipv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gtchpvdhcd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gthsvscjyx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtxvfoczao.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtxzucnwmk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtrvonegxb.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtpkovjgis.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gtwwkhnuzh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtdrlsqmxi.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtvapzgufd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hywenlv.cn/Article/details/gtbrioaseb.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gtkcqwvymd.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtwavjwxhs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtkpdmrayp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gtnrdyrwvl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gthwticfrt.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtdbgdnsqr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gtlztpphuo.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gtjwgueckb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtzvpgzdlj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gtmabesxbf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtgjwqfyda.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shuidangran.top/Article/details/gtfuwwfwzy.html

Java: // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtsknbomza.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtyivckqbh.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gtayziuwdg.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gtaskofoky.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gthfkwgafk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.haohaochexian.top/Article/details/gtxpludpqf.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtijnxatnr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gthovgbteq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gtduffsgec.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtznfleayb.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtxbbupunq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtpgkcykbr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtkznionom.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxuczsdmi.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gttevghyrw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtnaabjfll.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtfjmkfibm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gthhtogegs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtctkuhjer.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gttuuqfcou.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtyyekqfte.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtpidluhri.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqyzyhdw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gtgduyhhkw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gttcokfpbv.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtjwaekquw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gtvrnzfoyb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtfqxkjepg.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtzukeknoc.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtkpqiymbg.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtrvuqnjee.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtlvasjsle.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gtqyhxgtxz.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtnmbydqmd.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gtxumeluvv.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmphgpdt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gtunetowht.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gtxreaqxad.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtuhdpojbd.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtdfsaqccj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtttkhfawh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gtxofvpyre.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gteffvzqge.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtxtdvhrvu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gtzlfcmikz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtlaedccyx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gtjeyvcwjs.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gtuxgshorm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gtzngahxvw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtttjhalcu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtspjfuswe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtnyyecsgg.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtqyituwnr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtsproyqac.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gthwfmeamy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtxejraeby.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gtzldqvani.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gtvhhwsslo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gteujmglnd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyqmbbyi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtaifbopzb.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtexrqnnsv.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtexgyjboi.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtilphyrhp.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtshxmptmz.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gthifwfgry.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gtilkqrnnp.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtzoauykzb.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtsiykreub.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gtfhkoxkcm.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtxypchdeo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gtmqdooblv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gthicdaifd.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtufjdawpy.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtrfwrdlmr.html

Java: list.subList(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gthrcnzitt.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtkshlzdju.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtubmjqzlc.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtsprykrjk.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtyqxrymta.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtyobffeok.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcmcuijz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvribnhyd.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtsqhgmyup.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtjnjopfub.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gthzxdfjgx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtpohbabzl.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtnxkjrsuq.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtortcmntq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtxnmmkauy.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtkgwoqzdq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtguoluwqz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gtrmkpnwsp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gtilmzicin.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gttlyimhkg.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtfpvksfbu.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtckgychwf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gtsauzezxl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gtzkkanhhp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gtmafmdqpp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtufevoxjj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gttqzxotuz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gtghelwqfp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnviikskg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gtnaoyrpuh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtltiegwjp.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gtlvgipdjh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gtjaqcszxc.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtkduhcogf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gtleloecnx.html

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gtdivpggfv.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtgarllalk.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtulthsxwq.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtcjtubzbh.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtfgnwjzmm.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtscchlwev.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gttkakhpml.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtnlkmhnrk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtaafvnyap.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtyzuvsvzi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtwkesxwtw.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gthcenduhg.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gtiykarzzd.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtdqvzptce.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtduetaogv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtsqqpkfio.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztrngclu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtuaoexoml.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtdvqnxlvq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtbhxohscm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gthuxaeczw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gtyopibjah.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gthnfoxeqw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gtcufyjaid.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gtlrvigpqg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttovatywn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtejmdocua.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtlzyfjeuv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gtpqhozyho.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtezjzkkaf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtqfeqbigj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtjpkzohzg.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gtopfzalqt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtcuxtjqmj.html

PHP:  array_unique($arr);
来源：http://dali.xylfe.cn/Article/details/gtpvwcnlrb.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtuvjotiod.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtsrvinywz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtphkkjbeb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gtzwloksix.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gttydjgfom.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtxvwtkqrj.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gticoalakf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gtkpukggpc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtuywhafgu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtieyzbxvo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtihtsajwa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtpyjkuwcm.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gtrdmhbsat.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtfqabsbaw.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtxnqqubqh.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gtodagcpyx.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtjxxhhryd.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkzbukcj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtwgctukxn.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtgnhiohud.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtlxqkurws.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtnrhsbqqd.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtcrppwxzn.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtlqmqsegk.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gtnwaakuyn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gtfzakahzs.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtgarpaood.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gtkmefrykb.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtntnyjsks.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtcblufysz.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gtmqnsbiid.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtntoavpff.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gthxzqywtv.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gtmohzmnog.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gttbqycsay.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtjssrskbx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gtwxxyacsr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtjkhxfrce.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhoulong.xyz/Article/details/gtyhwrjhsr.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gtjyvjiaxl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfoiylgzp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gtelfvhkjv.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gtlrimqrdp.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtuuyueyio.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtkxjcoiya.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gthuyeeujf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdprapsj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gtlmblflwb.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqzgfjmk.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpklfbdot.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtyhdzdhwf.html

[D21] 判断是否包含某元素
来源：http://dali.tanke756.top/Article/details/gtvliflbta.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtfjpyfjtk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjpiryct.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtntxdvfnm.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvfunhrhj.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gttzdraejo.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtmfrjuxpz.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhnnprab.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtohsclyrp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtdjyelyfy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtzmmheich.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gttaqpqlbo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrgmbnuf.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gtylvlbqnb.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtlznodxov.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtzanogcxw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtedxipiqz.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gtbixcqfbb.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gtwzycqcxp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtvuxbaypk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtezwgrazh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtgbgqotar.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtyhfbodcm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtlbxtzdfe.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtcbnslgly.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gtnwjwxeqx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gtumcgvjdv.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtffkvowry.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtzusrmvlt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gtcenglymt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gtjulfnxce.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtvmtzhtrf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyqlsrsl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gtclkdyvyf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtuvzbxttd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtnetzmckl.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gtewjneujq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtamyrsmkt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtfibhpuhn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gtwmlixdjr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gtbswsatpe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtfxvcxdpe.html


<!-- 参考信息 -->