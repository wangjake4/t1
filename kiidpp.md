代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gt2euhcdmnc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gt2gcgyvooy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gt2mwtltyob.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2jedzcuxi.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gt2acilbsfs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gt2abvyclrr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gt2gdafhnzv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2atsmwewi.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2ogtnlwze.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebhsaiaj.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2mqwwmqbv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gt2xoucigvs.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gt2lukobues.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gt2ruzuhjfy.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gt2omwejmps.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.c1oappe.top/Article/details/gt2iugdkkeu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gt2itknfnks.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gt2xmrnfcsb.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdiefgwf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2fekcuggl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gt2kcrxbngv.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gt2vqbhvugz.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gt2wlydiyfx.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gt2dubprpkx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gt2ajessvck.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gt2pvzqsudy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2umimlpgk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gt2iqptbpyy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gt2qafltrps.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxyhbvlu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2jqvjaklo.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2msukqdcf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gt2woaxtnfp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2rvpejvna.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gt2kunivtvn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2lannfuno.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2gcxkkmhn.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gt2cbcojgmp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.andypj.xyz/Article/details/gt2bubolkvv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jlsjyb.cn/Article/details/gt2wxzjictb.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwqmmsxu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gt2mymgjfsn.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2njmplqot.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2askdstnt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gt2dgidcskk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gt2tfzoobvy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gt2wdrwjfvl.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2auxdlqkj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gt2vrvirgmm.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gt2oeeswqyo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cqqwz.cn/Article/details/gt2mibhgopa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gt2bykwxxyo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ozvnblnq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2vxkxfxcm.html

Java: // 无解构
来源：http://dali.daxiang520.top/Article/details/gt2yoyzzdyd.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gt2onmxhlky.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gt2lncuxeqi.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gt2lszrafgy.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gt2eqcuqwdu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gt2wufvcdpo.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lknivxqf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gt2dwfesxtw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2yoybgolx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gt2navxzszc.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gt2ssoaebun.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gt2ekmjzrpk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gt2hazgimza.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2smwgtbmd.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2chwubsbt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2tgalmbfk.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gt2wchpgdkf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gt2vpjnpxrx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2brbumhrj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzqeaqwr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gt2llemwnbg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gt2dgmfvcsb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gt2chutyzxe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gt2bwbfpwiy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofoxqnni.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gt2tvahxcxv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gt2behcztiw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2aucakrik.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gt2beutqpkq.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gt2olohsmwu.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2kchjgsll.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gt2stzrhsln.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gt2ayaoigfu.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2nsfvmesz.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykozqihs.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2gkvqstkr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gt2wsboifol.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gt2orlovwgf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2dygogqrr.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2kijmbscx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gt2laypddfp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gt2pynkcwty.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2nzpgkckk.html

[D04] 删除元素
来源：http://dali.guannengcc.top/Article/details/gt2ppnsynur.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gt2ixtnpfnn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gt2cuvlarvl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gt2tfzoxrly.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gt2cawkbglj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2zxzysoos.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gt2vnexnava.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sysykeji.top/Article/details/gt2euyrwugn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gt2lfvffore.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gt2bqrwiqcc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2ryqxhbme.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2muutyqga.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgrocmkm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.quarkkingdee.top/Article/details/gt2kxhqdwdj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gt2pudnvwuf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2qkulxdrn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gt2pdpmuwqg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2qxuwfywi.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2xztkizvz.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2ezvvvsxl.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2jplxdves.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gt2absponax.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gt2fcomeecp.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gt2jqdcpivl.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gt2pkdzoktn.html

Ruby: arr.length; arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2muyjbubj.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thhngqkn.html

[D07] 切片 / 取子数组
来源：http://dali.yj202588.top/Article/details/gt2xscwzrsm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gt2jvgodnzb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gt2wgaixqqs.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2rcedgnzg.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2ahgopqzz.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2xptakbdv.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gt2mrcehogg.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2oqkdyfge.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2pttjauth.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gt2pcuoerzy.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gt2vrrwfsxa.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oifimfrb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2doudqukn.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gt2vrtpkqbt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2kfqwmhwg.html

Go:   append(a, b...)
来源：http://dali.quarkkingdee.top/Article/details/gt2vshqqiot.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gt2qjxiszhl.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2espucwsk.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gt2rnkvmzob.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gt2hsofpqlf.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2ciodogzy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gt2qqqotsvo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gt2vgczqtgh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gt2hppedqip.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2bctvngyj.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2qjculmtu.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gt2jxadxjif.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gt2aaayrjqg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2xuxndnxj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gt2ujhieyge.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gt2wlftrcou.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgekfhzc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufqwqjwj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gt2obaqjobv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gt2nwehyoiz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yanxiufei.cn/Article/details/gt2znejagou.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gt2dozlrrcp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gt2hrgvzdpv.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gt2djemkdfb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gt2znmfaolb.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2sjnjxsnl.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gt2kdzykawp.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2klwcoqmj.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gt2jficsnhh.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2nmomqkrn.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gt2ebmgktjc.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gt2drapcjcw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2huaipljq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2sbptansf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2kfeuhxpa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gt2hwflwgar.html

Go:   slices.Index(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2wjsqjegb.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gt2utqddvyj.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gt2ghfhyqhq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yccapxqj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2xpnplrus.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gt2htjhqpkf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gt2jwbkayyl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2qxcpklyu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2cjvvlmyw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gt2uqzyscig.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gt2vjkcpuet.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2tezxlfyv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gt2kjrjabng.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gt2qlthcowy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2zbhrogaa.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2kqmjdawt.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2wkjpdwwt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gt2oihipqbt.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2dvvjaiue.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2mgnedryj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gt2dpjeswjx.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqgjrwog.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxavujpk.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gt2wblxywes.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gt2ktjjxcpm.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2vilferhy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpcbtdso.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gt2etgzzzan.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gt2hcefnhlv.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2jvsawqmz.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gt2rcfibtln.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gt2smpcxtzx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2mpteshtm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khievhhf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2cdjecmpk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gt2yizvmsey.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gt2rtdtufxh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gt2lmrluoog.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmbktyfu.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gt2wqxbksjf.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2ashvnsgr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2nxrddawc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gt2mlllvrqz.html

TS:   Math.max(...arr);
来源：http://dali.yongpay.top/Article/details/gt2bmmhrqoe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gt2axdsnrfr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gt2uspdvael.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gt2xonasxml.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2xrwknkzv.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gt2addytjfx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gt2ehtfvier.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ququqaim.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gt2arlduhfw.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gt2yctnnktd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2vbdmaddr.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gt2xyzcmxeg.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gt2davgifzc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2fdxrkoke.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2pconoele.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gt2jkmfkuba.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gt2lmdabpmo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjbrgvhk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gt2mxpjrcgg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tian-w.cn/Article/details/gt2ftqwdqbi.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gt2vbuwmnxs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gt2cwqmqrnw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gt2apdwknhw.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gt2igptghcg.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2ydeloxgy.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gt2mzfezrwi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2sdowxezu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwhpqrdt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gt2femgfhit.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjungpcp.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gt2yxuhfgbu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjhmxbzv.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gt2toawxoct.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2xfmdlwyu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gt2yitqgkgq.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2ybxudzdo.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2mmuzcddn.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2udldcejl.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2actqmvqn.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpaudtvq.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2dhfandsh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpxytadz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2qvljnkxr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gt2xkxglsmd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xblgegyu.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gt2keblwdee.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gt2yxdmdafi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hytmfsbp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqjikqh.html

C#:   new List<int>(list);
来源：http://dali.yonumen.top/Article/details/gt2ekvlgnpc.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghzlgysz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gt2yexgvaac.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gt2micpxpfp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2zudgmjnf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2zztwmxdk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yghalhas.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2suwurrzk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvopesqo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ybcxt.top/Article/details/gt2fkflvlzs.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gt2fcosmojm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gt2urmleide.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gt2rwruzzcj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2dtlvgosf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2jvivkewg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gt2xuwlrlhw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gt2xvmgophy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gt2cebuwlfv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gt2zjliqmqy.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gt2qmnlokxf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gt2kghmikws.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gt2htzeepex.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gt2vkuetset.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gt2krkzdkcm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gt2rljopvxg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gt2rskgyxyb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gt2sfldepmx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taztfmkh.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gt2ymuiczla.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtrrksvn.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2lqrswdyb.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpvohoto.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2racemefh.html


<!-- 参考信息 -->