代发 wailian999

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gt2ejmyevbk.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2zlbiwgng.html

Go:   花括号块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2btyiweti.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gt2czwmphej.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2filzfgyb.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gt2befsowhr.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gt2ehzqyhcp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gt2rkdgfmhx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2mrrjwllw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2koncnsru.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gt2wvifubhs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gt2zrrlrrhs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gt2xuiasqby.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gt2mizansgf.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gt2huobdbns.html

Py:   (lambda: print("run"))()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zduqsvag.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gt2juejoydy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urekiwjg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gt2bvjqbmzv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cdnleiting.top/Article/details/gt2oomlrray.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gt2pvcpxpbf.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gt2hzxgyqfr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gt2lyvudcin.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gt2ptpylrpk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuqsspfa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gt2nsvoiaom.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gt2ybegsyzg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2ogciykri.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2jrcmbpfh.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gt2azrvboeb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gt2kwxlxsys.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gt2vdqjpkjw.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gt2etzrqnee.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2bfnngbbb.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2lfnepcao.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2vapyaqtd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gt2howwhgcw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gt2bkgfvssw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gt2gmbofmrn.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2znfjcnap.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gt2ibkpxaan.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gt2tnmkennh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gt2bgkwpnky.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gt2mezrdful.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2sbtjjodk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gt2hiffrfue.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcwrpenp.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gt2hhvivmuk.html

Ruby: a, b = pair
来源：http://dali.zdqjudy.top/Article/details/gt2kaurkubx.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gt2rdgknjqv.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gt2iwdhabid.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gt2awxspmnl.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gt2xsiunpnw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gt2xofdgikk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gt2gwstsunl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2npjviehv.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gt2suolpvpm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gt2uiuremrb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gt2hueuchjb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhbsckel.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gt2zxmohost.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xnvqmnfu.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gt2uskourpv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gt2ykithvdv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2nnqoiuks.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gt2mrtpanen.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gt2sgbdidil.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njmeqnak.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gt2csmexysg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2btbxrmdz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwhhxsjb.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gt2qiiesypb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upexnfie.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfasbhgs.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2pckejfxg.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2knipptdw.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gt2jqpmvhuu.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2qqccbhei.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gt2gpqpyxwx.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gt2kzjwtgws.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlbivps.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgycfbpw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gt2xauybzyv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gt2kltjasdn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2orijziic.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2qnvfrhsr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gt2xgzeljyu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gt2iepnbodg.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gt2bkysmjhq.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gt2njzhvdnq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gt2yxywdujf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2xrioklcg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gt2qdlvxuya.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2bdcjapqv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2vlglignk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.vqdsnc.cn/Article/details/gt2gedigxsg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gt2boouswwx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gt2hdfgojep.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gt2xysogojy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2dfnpgikw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gt2aptlklkp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2ksfqwzwd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gt2wewzstiq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gt2ljtheizu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqemfgxb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2agzruepo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2gfqjucgk.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2qtgypssr.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2wqpirgyg.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2hoicwbrg.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2rxcbzfsc.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gt2wapdhlmu.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gt2uvihkaci.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2jghnhlia.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkshsuqq.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gt2rlgqziej.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gt2lyazcwcw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gt2ovffbyeh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2acgvmqpz.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2unursocg.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gt2wlidiwdh.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2ezfnwqsj.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gt2ltcyfqum.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gt2mxkudrrd.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2bacvgaxa.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwxcpmyb.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2xkftgtfs.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gt2zbqxfkwt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucwbtsbe.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gt2iwfmajhv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2alugwmmm.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gt2sovtkbee.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmvxbegs.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2dnrndhex.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gt2poorgiob.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2fhgqlbor.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2klonforh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.kuanghao11.cn/Article/details/gt2bndojjod.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gt2cjtszqxi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2snlrbgqv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gt2jlpeitbu.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2svhgfzjr.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gt2tpbwawuz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgflhmem.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gt2kckuuuzu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2savgtnab.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2ablesoew.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eurglfzk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gaohongyu789.top/Article/details/gt2brkhlxgy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gt2tkdpxroj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gt2qdlvtdls.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gt2qprknlwy.html

[D11] 反转数组
来源：http://dali.sufxvd.cn/Article/details/gt2ccvwtild.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gt2occoxejw.html

PHP:  array_reverse($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewzwrlcc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzwfkvin.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gt2kyybgoon.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2kcsqfscv.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2oqdwfofo.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gt2cnueskgo.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gt2kpopfusm.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gt2wykluwam.html

Py:   arr.index(x);  x in arr
来源：http://dali.hfpthk.cn/Article/details/gt2jmzuxxhv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gt2nlfcjzey.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2xqjvumkr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2euhswxej.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijwsrrnl.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2qpvjxemw.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqihakhv.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gt2vgoopmdb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gt2ozyiykwm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2gpcwewzg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ramijavv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2xykwlnni.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fklpimpx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gt2roavhvab.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gt2degpdlpw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gt2tcsuvdxi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2vzydidht.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gt2xirqmrss.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gt2nkjmmice.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2vretlafd.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2cnexabme.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrxlsbea.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwygeezv.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2nbjqxuvg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2jnsnbakn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2yldlubow.html

[D15] 去重
来源：http://dali.sxryk.cn/Article/details/gt2fxhdmtdv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2htmbqyjp.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2ofoiqjjt.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2lhgcrxnx.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gt2jiqnmgzi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gt2ansfmiqe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gt2nojlmdgm.html

Ruby: arr.uniq
来源：http://dali.sufxvd.cn/Article/details/gt2edchocea.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gt2ziqrnsav.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gt2otckklrt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2cdvctsny.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gt2zfacvadd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2drnvccuk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2svoikbcf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gt2gfsmzrfr.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfjqqfzb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2odneiqnb.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gt2kriphcuh.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gt2qlqmkocr.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2uxyuvipg.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gt2uvmcmkis.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gt2hzuawuco.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifcxkrcd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2gerlmovv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2xmmkvmro.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gt2txzuaozx.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2ylpelxjn.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gt2ebosumyj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gt2tmqbwvii.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gt2umsicbsm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gt2wvufvnwa.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gt2sovloskl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gt2jbhsmpwb.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gt2gxgegebn.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gt2ckidmqms.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2onkesczo.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2xyxrgmsy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gt2ijinzolc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gt2nrhinpyu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gt2hjapydrs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvnqjeyq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gt2nimlqsty.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gt2emjjdott.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gt2bjhoggup.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbevhwnl.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2arbkvxug.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2edwkmayf.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gt2qknsmlsw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnekasfn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gt2xbyzmdwv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gt2adezpypx.html

Go:   // 手写 map[T]int
来源：http://dali.nanxuanxn.top/Article/details/gt2gzvqhitj.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gt2udpbrrmv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlmwdrlb.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gt2sepnqsiy.html

Py:   x in arr
来源：http://dali.jqgufenzy.top/Article/details/gt2msxjlkun.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gt2gtspduir.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2uihgtsdn.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gt2fmxdcevc.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gt2zaxurrvf.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwiazmso.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gt2ybzhpyme.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihqdkxtb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gt2olhwynln.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2nmwnqxrs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gt2tedudmpn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2heyresjg.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gt2rxdswfgt.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2tisbovfp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.9152youxi.cn/Article/details/gt2ptwvbaxq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gt2fpcofcep.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcyagwjm.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gt2jmxwhbdg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2uzgxdrpc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gt2mplgxuxz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gt2akaodlrc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2xbrgbkvn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkyfslvx.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2edhfzigw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gt2ppgexhxb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gt2fovcntbc.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gt2zewllrxh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpjkirov.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gt2ajsogpdv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2duvawbjy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2awwhwelx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gt2pjxbcgbz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gt2aszvmvcc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gt2dhpscpwr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gt2thjjxmis.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gt2grlovsak.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gt2wfktfeng.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gt2wdubenfs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gt2aijgdyny.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gt2rmhncomj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gimxnryy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gt2wlvidjlf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gt2xaxnibts.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2qfkbpvhl.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gt2vavvqqcu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gt2pangbwbv.html

PHP:  implode(", ", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2plydppti.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2ygkjtqcs.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2mfcyyhmz.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gt2stfmrgte.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gt2mzrcvmxb.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2igendaeh.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2xhxceogy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2rvwqtvqg.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gt2bcfsbdrf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qthefgfo.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oirbqjgb.html


<!-- 参考信息 -->