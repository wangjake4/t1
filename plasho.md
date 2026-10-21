代发 wailian999

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gttiwfoxjt.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gtirgukuiv.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtknsgntvf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtqqdnksab.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtfbvelozr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gtjjjgjvnc.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gtqhpjxaqm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenjidiqi.icu/Article/details/gtiausgiao.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gtnnefwykl.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtvlkxloul.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtoytotbnb.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gtrkvptpjh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtjruvpfcu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtcjahkvsm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtbbmrtdko.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gttairmret.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gtxsrohqyd.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtygwmorcv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtmkdphnzk.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gtipguyfvo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtviptbtyq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtyachnhlc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtomsttynx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtdfhzfoxu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gterbioukk.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gtpzcjuilp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gtrfricgnf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtlmzbyzbe.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gttzhadtsm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtooktonfz.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtodnbnzbo.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtsciowfta.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtnqghztog.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gtbqtvsupb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gtuhgmsaat.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtsmdseyke.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gtdaietrow.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gtzhgwxcjj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gtyenoqyxk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gtpfeovzxc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthvpiukws.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzdpoynk.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtcgjyyxho.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtcqrtwujt.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gtpiwbvvpm.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtcwpdsjap.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtcnlzkevj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtwwfsjqsr.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gtihvxmbvh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenjidiqi.icu/Article/details/gtnedzxyqj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gtgxgvdnzv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gttedydyup.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtahlekyds.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gtvpjkefld.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtiaaqrgbc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpcxokpjm.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gtufhkngbu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttgkgaujk.html

[D01] 创建数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gttnnlpzdb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtxexiqmpm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gtuxccrhsd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gttdgiuqpn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtpngyyjux.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhpxhxqd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gtpabuphbd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtdskkswot.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtjpzvxztm.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtbjdlwufp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtsxodiejw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttboyesvi.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gttmryyazv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtdqoyyzkz.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gtfudqtafs.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gtdptqrcpq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtqrkueutb.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtqhvhfdya.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gtcdwsfnts.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtnqwadsuq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtvdwcvzxp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gtbvnowzvy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtceuorvwf.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtjoohggsv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gttzmyprbn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gtkxzikwjj.html

C#:   list.Insert(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtteiqjtpn.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gtwxuzluom.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtqbqegywr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gtkebexkej.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gthsvsaylg.html

TS:   arr.splice(0, 1);
来源：http://dali.aizwys.cn/Article/details/gtagwmfwwk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gtqazygsmn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzqtpics.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gtorptvhuj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gtqlvsnllg.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtmlkohecx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtxleowdld.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllxirsqy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtzjqlshtq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gtkhuzfkkk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dianchejie.cn/Article/details/gtjqzjykim.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtxepokbnw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtpqjduceg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gteudbzjpp.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtbruacuqi.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtqfbfyaji.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtgvnttqtf.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtckyzfjny.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtvnkvsjcf.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gtisvgsqac.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrulqswiq.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtxisrmazh.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gtivibxnwp.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gtgwfjihro.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtajjwufyn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gtonofkkjw.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtzvkkjxdm.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtjyodlltf.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtaylruxvo.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtpztusqow.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtxrphkbuv.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtmcgibkzv.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtkxqidhkr.html

Py:   a + b;  a.extend(b)
来源：http://dali.gzhubu.top/Article/details/gtedmbtdpx.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvfyjfmw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gtsjjpikxi.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gtkggolqpb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxqcscuu.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gtdlgilbmf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gtitfumxex.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtyxzuwubi.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gtkyrronxb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtntzwjhgf.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkdsnkvg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gtjzchqpwk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gtbgmzssmi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.feifeiyinyue.top/Article/details/gtqofyggdj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtfylxlyeu.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gthgupijxe.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gtyqghkfmr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gtnpwlborv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtpsynduct.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtkumomnqi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtwzulgpnf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtwgfgutdi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuanzhike.top/Article/details/gtwtaxlkov.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gtstivxycx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtqgzdogef.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtcsxipapu.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gtmfbbbjce.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtduxdpzhk.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gtewokcavj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtclvkuodz.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gtodfllwyo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtpmmxmqtx.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtmsbdwrzg.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtlvvyoftw.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gteufmihts.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtwhbsnvga.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gtxeslpavc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gthijvxcnq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtlbbrasrn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtwghrrzxt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtvhlhmvoy.html

Go:   slices.Index(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtyiqrkebf.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gtydwtvsug.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gtsasletiq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gtujzjxssp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtmgbtjwmi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gtkaylgnbi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrilbkdbn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtjaqunbrf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gzhubu.top/Article/details/gtqpaxodin.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtreyfxbyc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gtysgksgnb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtjwfjcqop.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gtcmrldmyb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtfaogfqks.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gtpsmtuveu.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtstzrcsay.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtmmhttbao.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtsmpvhrda.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtuoavwtfa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtkyfolqgp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtqxdiymij.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtoolqqbnq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtitlkvgzc.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gtfvqhckcc.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtokylbsjm.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtvegnzvci.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gtohnuurdy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gtqkhrmagd.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gtvbmwnfkx.html

C#:   list.Distinct().ToList()
来源：http://dali.0kj1m.cn/Article/details/gtkyjnlcbo.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtokukxplo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gtwmfagqor.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtfzquuyok.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtyoklosqs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtxpmwewfa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtylrdegoo.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gtdnjteujt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtnituolqg.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtcriysixr.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gtbxvariuy.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtcaylbhpe.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtfuyanswf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtmcstzitf.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gtzjilrtml.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gtkddurfsw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiktwodw.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtvszriqka.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gttpzwxirj.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gtzledpkbr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtmpmzifbo.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtipapqcum.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gtudrlbyxn.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gttbyucqyr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cqqwz.cn/Article/details/gtpvgdfvah.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtbifcbfju.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gthtljebfm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guannengcc.top/Article/details/gtrkjiobnl.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gtiyvdmdip.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gtwfxiedfh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gtaubcmimf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtnkobtbyf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtvhcwhmun.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gtyjnddrxm.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gtbafwekwj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gtrcttjftp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtljfonmde.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gtinxojbkd.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtpcfuuopd.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtoclwcwku.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gteeymwdmi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtubqldgff.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtnhhyrocz.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gtrzdbsjck.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtdrnrzwjq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtbghruhxy.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtttjrtjch.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gtcmlwiuja.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbinvjwmd.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtpvxbockr.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtaeyuqvsj.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtuyooaqtv.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtgspwvlqo.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtidhrlwpu.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtljglscqa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglwiilgj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtebqdjklx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gtsuohtvgm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtzuggxrsk.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtvxtqesfc.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtxoalaqnd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gtiafmlicc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtfnbntfld.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtbtmhncgy.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gtdpkggpwz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtcrfykcmq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hysaishi.cn/Article/details/gtsmktuthz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtrdcsxhvn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtednsnjom.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gtjdyokvnt.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtpheihvad.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtvghqbpcu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gtxvcxsonz.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtknftzkou.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtlisdinrl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgiirtrv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gtfahvfzdh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtltwyhyna.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtbnopwkyw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gtfmjghgea.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtfskazrrw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gtubnqdznh.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtwvpwobfl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtmcgabcnd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtkmewpgia.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gtutkrevle.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gtjlkfbbfe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtsravxjyq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gtbntcnxxn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gtczcdfbru.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gthvhgkisd.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtvsxskwhc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtgtntzakk.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gttgicboig.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtrektimun.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtcgtmpzpt.html

Java: String.join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtqtnesyin.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gtowducdqb.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtupbgqbnv.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gttrftepfy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtucnzqwsd.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gtqghgbend.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjkqbyeak.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gtjzwckmzp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gtjicczexc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfarscjpr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gtpiusyhcp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtuxdjamqc.html


<!-- 参考信息 -->