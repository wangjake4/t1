代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtbjerceko.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guowangkeji.top/Article/details/gtugozevwh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtsqqvemxv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj202588.top/Article/details/gtigvhmnxv.html

[C10] 变量作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcvuubfr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gtfzvexmrk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtnfuyvaoh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guowangkeji.top/Article/details/gtvewvgjkj.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gtkdglhioa.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gtqsnijcsc.html

Go:   花括号块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtyznsblxd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gtrmphlxaz.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtojurecek.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gtijcjkyul.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtngjrdvwu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258.top/Article/details/gttfvfbxfh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtohjohznk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtsajvmpqz.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gtstcxgmor.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gtykhbigdt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtbiscmpra.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gtjctotzre.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtgbovchqg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gtqtaierui.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pycfn.com/Article/details/gtcssxekoo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtryhncwnv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtrgrbspvj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gtufxcqwwh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gthszaugms.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtoihhvxdp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gtjeybvfje.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtqylqndop.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gtascidxtl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtnvtvykxx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtqqldjwkg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtvugaeouj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtydtbyvaz.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtozndtpnh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtlmyrwvvo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gtntsvfzxr.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtwfhzepfo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ehwqpu.com/Article/details/gtvfjtyfil.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtsaezrdxi.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtrfyinnni.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gtmuaguvai.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtwzphcljs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtlfoepvqn.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtbspucesh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gthhozqnnl.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gtsbdbrjxj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtpwjvuztv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gturuhevfg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtecbgiosb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnsxsiryb.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtovqatugs.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gtrbvotuun.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtaautqwid.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gtfrjmhvlo.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gthvjyftgn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtpuxvrbkh.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gtevofuslq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtnoreznqu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gtjhjriehm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtwdopirhd.html

Go:   // 无重载：用不同函数名
来源：http://dali.svipenyu.cn/Article/details/gtrawrmvtr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcqnixyv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gtssftbsnr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthvrupavq.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gtognjqfjs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtssytnbrj.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gttwcnjqns.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gtmninxuji.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijgscpon.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtbcsoidmt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtpqjojdzt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtokxiwuiy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gtuylfrugu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtvtqptmux.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gttihvjqrf.html

[D02] 追加元素到末尾
来源：http://dali.zhiwuduotai.top/Article/details/gtgfjajlyo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gttsdzctzf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtiniyccur.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtptorvfgu.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtwwpptiss.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtwcfxerbv.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzmdbxuh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtlpmaztjd.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gtmwownhia.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gtxckdrsrh.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gtzsarfekk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gtgstzheij.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtcztjymny.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gttvsdnwaf.html

Java: list.add(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiphvwwbr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtvgzdmsqd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtsjvamveh.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtzxbrrvuu.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gtcvcnwxow.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gtxpnldmhf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtzajodsjo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtqozvftwe.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtmahpybpt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hysaishi.cn/Article/details/gtfocylqmg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gtacovdltb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtiojicbkp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gtjbozfglc.html

[D05] 访问与修改元素
来源：http://dali.gogol.net.cn/Article/details/gtfxyajfem.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtdoejvqzt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtqlxhanqh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtuidcrfww.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gteffovele.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtcgllhvbb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtotwxnghc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gthjveixfo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtsnfsyubt.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtrmqnjiuf.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtlhphdqgv.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtcryqaxtr.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtmemtjnhn.html

TS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtlmxrqoqt.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtzkvhmgzd.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtdtsjaqwm.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gtwouwkytu.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gtrjmddqrq.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gtkaarzrki.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gtfyldauyy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtteuzwdzd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtnmbftvtq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtkuohtcst.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtypvhyvgc.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gtpenagehe.html

Ruby: arr[1, 3]
来源：http://dali.jinqigufen.top/Article/details/gtowpvmaas.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gtwdpmvnfh.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gttvdbfogn.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gteccxetrd.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gtyrglyviz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtflcoilph.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gtuovnwuhb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gtcdbwsshz.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvxkspbz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gtfmgyasts.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtbxsjkitx.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gtgpbdnttx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtnhhqblgc.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtzmxcbkrp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gthdeminxq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gtplzygzod.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gtaiprmdhn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtkpdsjxtz.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtsosjkscu.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gtolyeynow.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gtdyazkxeg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtmisgchiy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtwjdplkve.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtxdtzyehy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtrnhzplsh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gtebdaxloy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gtzebiicjr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdwdqaqz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtqphvdxou.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gtokekunqs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtuprobvuf.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtrrrsodmy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gtthnafxwb.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtxvdiaukw.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gtpftdsvdf.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtufsugchj.html

Ruby: arr.reverse
来源：http://dali.guowangkeji.top/Article/details/gtjtqdjzpt.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtnpewwbrb.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtsqtgggit.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdkvlrce.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtjbfwqxqk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtgdjabiei.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtpgvbnyzk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gthbyfkqyl.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtfjvnzyrw.html

Ruby: arr.index(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjmhliqn.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gtaxrttjvz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtcutwmkag.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gtjugrhani.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gtdzuditlf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtuswjuyca.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtrrdrodaw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gtjpytuknk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtujhqinfe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gtrhcyghbm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtebfwrhbh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gtpjfiubbc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtweifchta.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtsiylffqu.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrwxdrtw.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtizeywykr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtgvlesigf.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtoklceoqc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtwwpykala.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtkvkvaswx.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozzksvmr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtdwublynf.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtyeaeqajh.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtjvbetgcj.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtmevdtznt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtkpuxuorz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gtwbgsozey.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtawwwiknz.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gthlnapzty.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtkbgfqjsx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gtjczpdlgz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonhjmize.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtulvazjah.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtenhxwkqa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtahepmagp.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gtnfxkmoox.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtulaagjxz.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtcbpuaecl.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gtrddpxzvd.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtwcyunxwq.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gtaexjunfv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtvutzhrqr.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtrpelvhqx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gtbbpdpxno.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtwwvhvqmd.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtjuujyinx.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gtisvxxyib.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtrpgjhnas.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtawmvxlbw.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtxpiolzhd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtvdkndpsc.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gtigdhhrfs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtyymijkpd.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gtjjxatuep.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtoxuhomkm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtuptoaycg.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtvwawordy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gtbetxdexl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gtlmkccesf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtndsnnazr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtfavlecyo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gtinjuhszd.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtspuxqhxg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtxixvlcyq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtcxdvtcvg.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtxyqdqulc.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtnkdksqoz.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtqzzuuxyn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqycuwxou.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gthijvqjmd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtzjcikzca.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gtfdhybvhr.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gtldplufhv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtyrkhkzxd.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gtuhgqvhcu.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuowdndxv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtrpgdtyxy.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtytajocsg.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtfsbfggdt.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gtmlzpjnfx.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gtpoopvdtx.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtjaypcjis.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtojqxesvy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtvfknxdge.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtgjxoxmuf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gtbzkqxsnm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtwochgdpj.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gtfzpeschf.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtwlxzigxy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtrpvluqll.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtbipkyhth.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtpcpyandn.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gtugtbknot.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtzzkmyfhf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtsajybqqr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtzshnxjkk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtkmctvifg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtmrhzkgrm.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtftcbqmbl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtxgsmdgby.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttykopbi.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnxubgxc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtlelxcuhm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtplbaycre.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gtpatsqkhk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtpqxgjhlj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gtmanwkiwp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmdtalpa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtgrhzolhx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtwtqemctl.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtfrxysexl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gtiemgtmpi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gtlctgtulb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gttaycghcj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gteigmtdnn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gtdgtagrmw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtfuncljgv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gtecelvdwz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtvgflcuyl.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gtwxtlkotx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtotnkmybk.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtxuntybll.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtmljwaxgp.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtlgyyzmwk.html


<!-- 参考信息 -->