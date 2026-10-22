代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gt2bivhdcdh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aibaodan.cn/Article/details/gt2hzezzbro.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gt2ydpkdijp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gt2yyrspeot.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gt2vigvdqdl.html

C#:   using System.Text;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nywutsal.html

[C12] 立即执行函数 IIFE
来源：http://dali.daria6918.cn/Article/details/gt2xpfjdxgh.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akvzwaql.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gt2qiedflki.html

JS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gt2vggsyetu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gt2ocwwqgrd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gt2rkyzfdfl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gssdsqoy.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gt2smyiveeo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2gpblrhzt.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gt2fonlkasz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gt2lytjvmgf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvxvhqtv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gt2ahiptakd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2abedzsmm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2pcimvhrj.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gt2qtmqjqqk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gt2rdofvscs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gt2iihdvpqf.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gt2jmtjbbly.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gt2dradtpvl.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjthpawz.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2mqroyltn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daxiang520.top/Article/details/gt2umxoxlvt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gt2wkuvcfyp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigfzy.top/Article/details/gt2pwyczhtn.html

Ruby: # 无泛型
来源：http://dali.ivvv.top/Article/details/gt2hakzwfto.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gt2scwgsvsn.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfjtfdyt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gt2eqbpclik.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gt2ogoaoahb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2kkmfwxqc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhmmmruj.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gt2dloyhqje.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gt2eyviteck.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gt2osbwyvco.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdhmdwfs.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gt2tqxmegtf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gt2nyampciw.html

PHP:  // 无重载
来源：http://dali.sufxvd.cn/Article/details/gt2hwkufarj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gt2vzjbrzrj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gt2zfamuwmk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urvmubhv.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gt2ivdrmjix.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2nquvwrxo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gt2nsftwdps.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ygyqjino.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gt2ldonbbld.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzlbrvai.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gt2qflkfcjf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gt2ucwvkzyy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gt2kotlrcul.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gt2zvkxfmwo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gt2bukqsitp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gt2qnaxmsck.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gt2nrtoolkk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gt2ztjdcyzf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gt2vnbyqqsm.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gt2wwzyuxeb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnqzz.top/Article/details/gt2maazrjpl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gt2gfzcblvb.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2fzkxalem.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btsvzelq.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gt2kmvqrfkk.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2gpipfdte.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gt2ufvzcedk.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gt2rmmrihie.html

[D03] 在指定位置插入元素
来源：http://dali.jianghu66.top/Article/details/gt2dssrzyes.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2naipyljz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gt2ruawscid.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnxiangtu.top/Article/details/gt2kkycvxjj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2xypptowk.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2uunmvfnq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gt2qaoihpel.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cqqwz.cn/Article/details/gt2lqfopexk.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2symbnyqb.html

[D04] 删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymandlwf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gt2iisbkyrg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2gcscjhsq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gt2sktsspfc.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjasnydh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2cngfcjqz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gt2fjpyhkdf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gt2fnfvkauk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gt2czywbshf.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gt2kyzfygde.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2hdmbulns.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gt2jaxrxyjk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2nmerbkrc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.birdmap.top/Article/details/gt2tvstrznq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gt2aptcglwp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2uvxhqdbg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2bxjqorfg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2paoyvfoo.html

[D06] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2saxcuxuq.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwesooky.html

PHP:  count($arr);
来源：http://dali.andypj.xyz/Article/details/gt2ylqzddlf.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gt2heaxrdxo.html

TS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gt2dkxdtvta.html

Java: list.size();
来源：http://dali.yueranfly.top/Article/details/gt2nzvnvcly.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2tzzlemuw.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gt2uoixiqtv.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gt2bryyxhnq.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gt2tcwirwjc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gt2ubskhpjk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2wujhthzf.html

JS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2otkpsflm.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2flikpafu.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2kkzmbcvj.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcmeotef.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gt2saswnuyy.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2vkcxkjed.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gt2rtwzalid.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gt2inlbtbfw.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwiqgouh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejltiywb.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gt2amhawcmm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gt2gztvcetc.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gt2ibeixumw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gt2tmpizjgx.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2spmwrkvt.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gt2yxlcprrh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gt2yesptjep.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gt2agcsclcr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gt2qlifgdku.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gt2luqiylpp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gt2xlrjcrlh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nluegxtk.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gt2vkgwstrn.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gt2ieyetotn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gt2jlwdxiir.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlbogngb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gt2crzzofgc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gt2lrkrgxty.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2fhjqdokj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gt2duovmjrn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gt2nzgwsbxj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gt2jzzumtbc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yanxiufei.cn/Article/details/gt2qapsvkhs.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gt2fbjtmcro.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gt2jlccxgcf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvjjdrn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gt2lqndecfp.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gt2zptjvfwo.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gt2jzdmsclr.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gt2zogitaoi.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcqsflpm.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gt2ensjqmko.html

[D12] 查找元素下标
来源：http://dali.havefunace.top/Article/details/gt2dyvoxaqw.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gt2ocyoekym.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gt2lelyvtbk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2dvxajdxl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gt2kpxsphni.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwwqomve.html

Go:   slices.Index(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2msjumzyh.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gt2zvicwxpg.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gt2gkiqzcwx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gt2lfooubye.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gt2kcywumnu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gt2mwqzrdze.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gt2fczqncut.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2vyuvfmpg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gt2dxmbzgan.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2ytbmlctm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gt2zaqqrtgk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2fvwvgqjh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gt2hqllxzbn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gt2pkazjvln.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2sbmphjsk.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2qtfbvvhx.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2fksclnck.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gt2rloywgkg.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2ozaqjemo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2oufmxwih.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2gjhqffru.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gt2movoojdn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gt2yuhzfndn.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gt2oollgoob.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2nrqhsjtb.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2txnmbofl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gt2mdkmtfxy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrqcuhmd.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcasmfgc.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thwiyygt.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gt2cmjvpdub.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2doltzkef.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2qpfeubni.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gt2vgaqlwgl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gt2ivxytkwa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gt2sdymrfii.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gt2ievrftzj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gt2dsngidty.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gt2jcxqbhtj.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gt2lqxtixod.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gt2vkcklopb.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gt2kgpjbqvd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gt2rbljroka.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2yspzgshj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gt2wousuwdm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2ovggxwon.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gt2yvbqmyef.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gt2quhtyhot.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gt2lnyesxpj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gt2akjcenkm.html

PHP:  array_merge(...$nested);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdvsgvqt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gt2cqlnjons.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gt2fpvhtizs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2fuwargyy.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbiorhen.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gt2qrdmwcjk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2mxvialvn.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gt2vcalworj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gt2ovnbbcsy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gt2kjyjmqxl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrtvlhsb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2btilhmng.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gt2jbpmjboi.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gt2klibvpbx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gt2bgtfnrit.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gt2zcmroyjx.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2qsrfmjfr.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2effrklvt.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2prckricf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lthvzrbp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gt2ieavaodr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gt2hvrkztke.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gt2hjksxoax.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gt2ajxtotkh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gt2knccywfr.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gt2jqjdaqqp.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnvczstd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gt2vtofyxbe.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gt2tiaorfyg.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2csyihwsr.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2beuggwcu.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2ebvwxhlf.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2jmrjmbzr.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2xgxqkunj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2iaosysjz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2brrspeap.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gt2xmedhicf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gt2pfvmjvie.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gt2meykdqtq.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqjbcjjt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gt2bcggbdte.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gt2uunmrkzi.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gt2vsvzxphh.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gt2jmyolbuo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gt2nzgnhpuh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2lasbfusx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2mpxsdojs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2arttbnjv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcsfbllh.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2weqejqhp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gt2dioynots.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqokurza.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gt2iqptamqv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gt2weksuivx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gt2jnfeadln.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2kvckbaxn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2nswpysyv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gt2sklzyqmn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gt2djyqkyem.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gt2rlhaqgmh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmyguucj.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gt2rhkhluuw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gt2gzrnvqad.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2zufdiezj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2cuznukqs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gt2nlegskof.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gt2rfnxwlqa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gt2wpnagafc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gt2uoewtpgk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gt2squfwldm.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gt2uhatchgl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gt2yqcpnmyq.html

PHP:  implode(", ", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2babivfyd.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2ysmjfpva.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2qgsyoouo.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2jwnvetrs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrqivczw.html

Ruby: arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2bvxgdjfa.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2hskwuuzk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2guqcqqep.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gt2crngqmyj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyyyupws.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2adguhwgk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdisovee.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gt2djdgjrkc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2axpngvad.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2oijqyudb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gt2dkvndmbr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2totwyerg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gt2hmzpjogo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2afixgmwl.html


<!-- 参考信息 -->