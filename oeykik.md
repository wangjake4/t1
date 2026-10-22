代发 wailian999

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gt2zjvyfeju.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gt2haeajneo.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrpboocq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwbwxbfs.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2eiysgofo.html

[C11] 模块导入与导出
来源：http://dali.yj20258888.top/Article/details/gt2osdwumrc.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gt2tpymhibx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpfiodyb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gt2ntsypzrm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gt2cllvmguc.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2nsjjylvr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gt2uywwsrpt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gt2ilozefeg.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbdfgpem.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gt2quvzsytg.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gt2ggwjngqu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwgalzxk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2nuvgtpag.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gt2ayjqvlxm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gt2uezbxzjs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iswzagxc.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gt2ndsmyrcp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2oefkwkjj.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2baazsout.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gt2pihftawy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2dpifcqhv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gt2lpknhinr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2zisqgwqe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2ucrktmft.html

Go:   func add(a, b int) int
来源：http://dali.dianchejie.cn/Article/details/gt2mfjymkft.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gt2pufqvbuv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gt2jbmqjctq.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gt2znbhfjyr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gt2tblscpty.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2krszvdom.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlhwrrdv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gt2pqaovlkn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gt2prguonsr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnynscie.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2gggmwwua.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gt2spmvgkpt.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gt2qeemuyyn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulyhpbdh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2meyzexik.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gt2lontjfcw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ccvkzfyd.html

Java: // 无解构
来源：http://dali.pycfn.com/Article/details/gt2aolwjerz.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gt2hildfvqs.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gt2kmomutus.html

C#:   var (a, b) = pair;
来源：http://dali.mhx1999.top/Article/details/gt2wbsutjkl.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gt2fabglvug.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gt2xvtizsuf.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gt2mdqvpsrh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gt2jdcgzetu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gt2vdgxmlql.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fengsongda.top/Article/details/gt2byaonmri.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gt2vwlwqlrk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gt2xuwsrxni.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2jabqhdqq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gealtmbk.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gt2agqnxfzg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxmbdogm.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2efdvviax.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuryzecd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2ctmuxqqd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gt2erabigry.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gt2axngcnwy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gt2caiumikn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gt2qflhjhxb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gt2qusrfybu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cdnleiting.top/Article/details/gt2afikwuag.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gt2amsxtkco.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gt2mzutzjny.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gt2builctrj.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2gjjvfboe.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2wgxaxphn.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gt2xkvoqbio.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gt2ucflqceu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnqzz.top/Article/details/gt2qqomuvsw.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gt2ncbbgfzt.html

[D03] 在指定位置插入元素
来源：http://dali.nanxuanxn.top/Article/details/gt2psxflhlt.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gt2rcvkoyvh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gt2zwmxtehb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gt2ckvhhkzi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2oewstkuz.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2wwmjoskv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zopvkqgk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2meaeocmu.html

C#:   list.Insert(0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2khxdqpxn.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2xqajdmgr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gt2vrxengvu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2joocdhre.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gt2gggnynwd.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agskqayt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iaucyjlc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gt2jmbrlcwl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gt2gcwnjdvr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puaruldd.html

[D05] 访问与修改元素
来源：http://dali.haohaochexian.top/Article/details/gt2zxyttvtl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2jccnfeox.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gt2nrjyaujj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2cgecmejh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gt2kzwmwwfc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gt2ovguzdbn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2eidpkxwm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2yctmhknb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2hbhonhrd.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2mmeqeaop.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhzmoica.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2iijkwqrs.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2uycaydgu.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybgtdcnr.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gt2uacjfwqh.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2jgkwdiat.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2dmjdcwjn.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gt2tghqvxwn.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gt2hzzqssji.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gt2odeftqbd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkcawjna.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2birayuya.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2icztvbfd.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2xtyizpyg.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gt2noobilsp.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gt2nuopivfe.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2umxhnfnm.html

[D08] 合并两个数组
来源：http://dali.jqgfzy.top/Article/details/gt2krmrvmek.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gt2bduxvnhh.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gt2iaqylypf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gt2qfdncult.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gt2ivcrvxsv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuxming.cn/Article/details/gt2aivagkli.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gt2mfhqiuwh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gt2yldogyqj.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gt2crrzoyun.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gt2pjqpbugj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2xulmwkei.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2tiibldol.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gt2ngivojdc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gt2yzegbqzf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gt2qbdnhwhc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2xwejslys.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gt2otxrmofx.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gt2ivdatpja.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gt2uhlguofj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gt2qnrutssk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gt2gyqxzeub.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2vvjzbxnx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2vfbqkoxn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gt2hshypqnz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gt2pspkprgq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gt2khvvxxpe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gt2xjdmiljb.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gt2wewwbjvl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sbdsmydf.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2hqreyvvg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gt2pvisyjyh.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gt2xjodbcbj.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gt2mcxrcafi.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2xupffsni.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2hakehalu.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2jcmknjhi.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmtuhspc.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gt2fmsbfxlu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvjfcgda.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adtgryoc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gt2umsiyhhk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dianchejie.cn/Article/details/gt2eoppsids.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2immttoge.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gt2rqgsucdv.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gt2jxvwwclg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gt2bhpnhpyv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gt2svepznpz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2ezkzaqxx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2zluylisu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2qhgjnavq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjfvdzxg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ruwxdidi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gt2wkmrmlls.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2emuecsgy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2lspgrhoh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2ynwsetrf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lddsdjri.html

JS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gt2eznacutm.html

TS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gt2szuzniui.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gt2cwbqivtx.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udynddvm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2orwzluvh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2cpxiitpe.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gt2muvdvcyg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gt2kreqgxwi.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mglpjyex.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2dtdybvpr.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2gfrwwhtf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gt2yhxsajqb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gt2sljjujnf.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gt2prpfvfla.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gt2pariobmy.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gt2igojlyyq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2iqwtasqn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2ezfnbxly.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gt2cxclqhwy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2mlsbuwmq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gt2mvsgycxj.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gt2odhvhcqi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2zoubiebd.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqpwimxj.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gt2yofgnznb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwozyzaf.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2ohgwvdbp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gt2vquvgoza.html

TS:   Math.max(...arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2vzjgpvvl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2gapotxrz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2waadyava.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gt2pigrenhg.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gt2fhkqnbgm.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gt2mzzatpjs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gt2yktxwgqb.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2gmnevdmi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2foicgvzz.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gt2qewxorif.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gt2ajfrduho.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gt2fvpthpvp.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gt2hrgjxxuc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2tnxlqlbl.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwefldoc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gt2pjxdkecw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvetjrzj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gt2ldboyoqk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2tylllqff.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gt2ntkvvaki.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gt2pldlqjto.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gt2hpvrdtbz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gt2bwxtlbsz.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gt2enewiftq.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2onzmfjmm.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gt2pjinmier.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2jnwuuxkg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gt2jcmtcxdl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gt2whcljwmv.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxjfqcjq.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzjcrhid.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gt2yqfqikmo.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gt2rhjlevda.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gt2vuryvygs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gt2qgnrpobi.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2qzweucfp.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2ivbrvcae.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gt2iikggkjr.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2msfbsffi.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2jlyghxky.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2xmhhtvpo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gt2xttzziwr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2ddymytjz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gt2dwpwxmft.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gt2bwinbefh.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gt2etjxymdz.html

Java: new ArrayList<>(list);
来源：http://dali.tian-w.cn/Article/details/gt2ybezmmlv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gt2ntehwjzr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gt2eicdpxxa.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drpufjbl.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gt2roknzlhc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gzhubu.top/Article/details/gt2aguarygb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gt2oityebbl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2olwdbubu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isolywts.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gt2kxgohyhu.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gt2djnudmhn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gt2xroxmbzy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gt2xydpulwk.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gt2kwawooig.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gt2pwwmrdim.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gt2rynfvrtz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gt2ydffahqp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2bwgnqsak.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gt2chojzmlv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zyvsjtcn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gt2kzotaizd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gt2gaktkbzf.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gt2nzbfgwzt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gt2qrpbcahl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gt2vmftdwkz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gt2kplrzjvg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gt2ahzswyoe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2uajamxuh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gt2xqaobhln.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gt2zxblqonu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2aborqzpk.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gt2hcbbovls.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gzhubu.top/Article/details/gt2pzihsvdk.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2knnfrimn.html

JS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2lnqizzsf.html

TS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2zcwlapmy.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzztqrml.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gt2dixqwbdi.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2qkzmcjmj.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2lpdtjxvr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2psotrsqa.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uoakhhcm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2zopvgxjc.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2auhnvrat.html


<!-- 参考信息 -->