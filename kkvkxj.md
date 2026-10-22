代发 wailian999

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2hnxaxckn.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gt2zjsgsvuh.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gt2fawtpygd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gt2glipuimv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gt2dhixwiqp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gt2cfgcmmsm.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifrzadck.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gt2xfinzysy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gt2soixmmbg.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydxulzvy.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gt2vjcewnss.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izolivom.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gt2sepejdxl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gt2uoikjnwa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gt2cfsokqgt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2dhahwexb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gt2aoddxnfm.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gt2uoplaxwq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gt2kmrsfggy.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcjbmmgm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2ahurvndd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2mcjoubwy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gt2qksqbzlz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2rzogfnbr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2mielwqqn.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gt2mmtczziw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gt2hosaxlvb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azysdidc.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbrywpho.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gt2bppkmtco.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebpqocqu.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2xvgrlktx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gt2iqagqepe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gt2tthqtcbz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gt2cdsqgucs.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2zhmvditf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrwavtmd.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gt2hwreakub.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gt2lagtfaxe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzdtagfm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gt2wbaadmlp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwhkpxma.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gt2iivlzzel.html

Go:   // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gt2zphyoaba.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gt2vwhzfqef.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gt2ibwlgobh.html

[C16] 函数 / 方法重载
来源：http://dali.pengpengdd.cyou/Article/details/gt2enhuteua.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gt2rzokvcyw.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gt2quplglok.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gt2rnfvuhrh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gt2dvjtgrvy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqbeqnsu.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gt2ppgmgolv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gt2rrhpiuui.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gt2tiyzwtjc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2mozwhrth.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gt2oouarmdp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybxivosa.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gt2inxsgrmh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gt2thypissg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gt2ekpevoxv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gt2cfcdqhtm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzkhoibi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gt2iffdqjzp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gt2kjhqkppf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gt2iiiuwgef.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gt2pkedsidr.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gt2shvhaoas.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gt2rmqfkwnr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gt2lpoqbzoh.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2fcrlgwzj.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2wbewdkqs.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2hfgpfuiu.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2pwpyvzze.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gt2dulgiwjd.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gt2oawnicdh.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gt2jxcpxtci.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2gylxvyzb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gt2covhkeec.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gt2akjebdsf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2hqhvwtjq.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2dvgspylp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gt2lmxgxbpq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gt2lhzpcvtj.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2fampmqlu.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gt2rctczpjg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gt2devxynao.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuanzx.com/Article/details/gt2gdkksctn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gt2anaaebjl.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gt2epgtyjpc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gt2gjzbppha.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gt2mduwrrrs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gt2ynxaammc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gotoacloud.top/Article/details/gt2qeblfelo.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gt2gnvmkwyv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2mcfkvymy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2rtujihjq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2odithiob.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gt2brynedcf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gt2nosilvoi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2ibzmjoue.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2mazugliy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2swivnrbe.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gt2ceqkpqzi.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2ahribmto.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2zyvxurrx.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2hddxitpi.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2muvxiopa.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gt2apwwobhc.html

Go:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2wydqpklq.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2tlcpthhc.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gt2aldivmid.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gt2meqreozy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2jdkderea.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2hjietbnd.html

JS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdimwiib.html

TS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gt2obudyxjn.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2nktvhwok.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gt2ysndvlhm.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gt2kdwjfzzr.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gt2plwlqtkd.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gt2azjcgvpr.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gt2oryjiblr.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gt2tkvnlkwq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gt2dalzanej.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gt2fyvdksfx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2cprfzuxh.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gt2nhpllmyu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gt2ilvvhkcf.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2hmbhrvgx.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gt2lzmigryl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2titskowb.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2pmpwtttu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258.top/Article/details/gt2eoevswwg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gt2qegbqlob.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gt2yoluvcwr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2negrnumm.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gt2ebgtdksg.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddadmlpn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynlaykjo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gt2alggqfsv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwcmyxum.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvvcqrvc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gt2xkrfvugm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daxiang520.top/Article/details/gt2aokoevwi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gt2ueoduzkb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gt2rzkmecgi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gt2fksjfeji.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gt2faipfjwr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gt2mvhoeihp.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2hbxuxdug.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gt2qbotwvub.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gt2nemllkwi.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gt2ihxcbpas.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2wayyrxch.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gt2iivncvsi.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tisimcsm.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gt2itcutgxh.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2xbzeldfm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gt2neqlnxev.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2rravznsb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2rajglwxy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kpkuhuav.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kifbjhhx.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2irmecugj.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucjxzpin.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gt2haoylchl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yongpay.top/Article/details/gt2xgxtmowb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gt2ojqkscda.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gt2hbahtuvr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2pfzzjkyq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2zemawglc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gt2esrolayi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxtnuusk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2wboordfj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2gbfupcgn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2howyprsf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2zgrglonc.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2ewtnzosz.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oblhhrwh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2pxanxicl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbqfyxk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2ttzgifmw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gt2aoryzrqu.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2icbivstu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gt2ttptpcfj.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gt2zhgmoewe.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gt2vmqveatu.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2mhaodouy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gt2mvssterw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gt2yygtovwk.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gt2omljhhdz.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkmmldit.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gt2hnmhhlll.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2ezwgcyoe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynvvpnox.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2lysstwwx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2cnjtquob.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gt2fpvrezin.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgululsl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gt2wckmvsiz.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gt2lzjfepdo.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gt2bishejqq.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gt2pbltvwil.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gt2caxdirli.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gt2grwgudiy.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gt2cwsexhzb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gt2ozbjcecf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2gmhlvxej.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gt2ytjxzseb.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gt2kevnjjca.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gt2giylaatu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gt2jeplpxzy.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gt2wfjajmkn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggfyftvh.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gt2yuzxsorp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gt2joakplpi.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gt2jcoqlluk.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gt2yuxpykvm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2ltsurdio.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gt2ctztaysd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gt2bvhrmvyq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gt2rgamjxyg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gt2fehjxjnq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gt2gohyplch.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gt2ytkbbqxc.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gt2kpuspgow.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbpijuom.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2uwlkwyja.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwkcnexf.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2tmtvzzek.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gt2hftnvtop.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gt2ageobgki.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2hcpkwxrq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gt2iziabalt.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eakarbqq.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gt2ewmomchn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gt2exgsxlgy.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gt2tgevznvd.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gt2xylzyvvl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yepllsdj.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2hfakhajc.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkejmrly.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spfvrsib.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2nknxqkgf.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gt2fmtejkcv.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2lnhrkmuo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gt2tzejvhkp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gt2gekdweex.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2qyzoztfr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gt2kdiwdfsp.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gt2plrwpxwt.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gt2vkzrxntl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gt2szyapobe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gt2rtbwfnpd.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gt2ltvpitrj.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gt2mejsfmds.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2ehkvykjf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2mupeponl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2tyepmpvj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2bkegtbzr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gt2jsmxbipi.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2pofgzcav.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gt2pfckvtbc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gt2lnvvndjl.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2twmfatdx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gt2unufzlzl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gt2bcagtpbu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2xzsekekz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2nyabztys.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2usmklhwd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gt2bpximkwx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gt2lnpeuoud.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gt2nqzgofnf.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmfbzewe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gt2tuhcpfav.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuanzhike.top/Article/details/gt2enkpsgdd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gt2wxnmjbqb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gt2lyjprsei.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cojdwwld.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlmmreec.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2pwtxmgpm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gt2yjueckwy.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2ktuikctf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2nkvqjdlb.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gt2txfxstap.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2geqthmxr.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2idzygkyk.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2dyrtkthv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gt2ilxcajga.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnrzzlhe.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2izmyxrdf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2tppwvrpb.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gt2wmjhuuoi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2hnlhrati.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfkcctys.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gt2txvivdwl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2efxirlgy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gt2zojrlera.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2fgfuarbd.html


<!-- 参考信息 -->