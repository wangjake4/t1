代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtqjpacmdh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gtjezcazhz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoslvgrpr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gtvxueqyyh.html

[C10] 变量作用域
来源：http://dali.cqqwz.cn/Article/details/gtrshirkoo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtnfuzowkq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtxacgrhye.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtrfmpbudl.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gtgxdavhlj.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnwfsznr.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtaybzazzu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gtafemfdhv.html

C#:   块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtxoldcxjb.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gtkzuhesge.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtaajutitz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gthdzgoeio.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtpetvbbut.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gtmdvzxsxd.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gtrggefjin.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gttwfyyjpa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtrmqvbgiw.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtjwfrtfkf.html

[C12] 立即执行函数 IIFE
来源：http://dali.hfpthk.cn/Article/details/gttojcfnxq.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gtyrhqttnq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtnptlmaaf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtbdzstfcz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtydnphrpr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtmsgztyzm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gtwbtqwakl.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtesvocpcg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnrhmysd.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gtuhkqsgth.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtafjqehjf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtfvhcmfnr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gtcmzekldz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtciydrqtp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtmmnsbpfw.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gttgtrvreo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtvrfiubkn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtkjgudaeh.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtbsdvdzsp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gtevbmvtvr.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtzsoqlehn.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gttcavxicb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hywenlv.cn/Article/details/gtxrwgnaps.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gtcyaeueau.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtjsmzueef.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtnaewsind.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhengqikj.top/Article/details/gtcdxojzel.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtntlidwxm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gtfljeofgl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtdgrfcija.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gtidrijslz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdhkrrrdi.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtepzwizeo.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gtorahtoby.html

Ruby: a, b = pair
来源：http://dali.ydzc1.top/Article/details/gtpihbmiok.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmlycppf.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtwklubqrz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gtqsnsarrh.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gtzruoaqmf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcejjvirh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gtwxxzfgfz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jyoumei.cn/Article/details/gtzcnybcyh.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gttfayvpvx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtsedmvljl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtpddetqgk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjugbfitw.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gtvmuaelqg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwgudsegb.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtrgrsdfhd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gtdhophgxr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtnykfxbpw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gteeiegpxb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtsdutpneb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtejnuuuaq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gteuvdjjeg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gtfzjkfazx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gtpobcrkuu.html

[D02] 追加元素到末尾
来源：http://dali.xinyue.icu/Article/details/gtwpjrkxeg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtpbreeita.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtkfgvpoft.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtowolnmai.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtovlivayz.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtpmfpqkdv.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gtgqrlvwoy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gtwwicxbev.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsraljjur.html

[D03] 在指定位置插入元素
来源：http://dali.daxiang520.top/Article/details/gtxooqphhv.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtjuonxllp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gtwxcsczwd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gttolyesvv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gtjoruisnb.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtfnhjvbvs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtzliqqroe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gtekmlenal.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtikxbbvau.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtokipklnv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczyjzmoi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.mhx1999.top/Article/details/gtcvmozxez.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gtszavxfxt.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gtfygurrea.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtedcjyfxp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gtqlzehhon.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gtumoxryhy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxinkj.top/Article/details/gtetcgtaua.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gthuaquotf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtegrkjdfg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtdlczvdko.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtznbzljol.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gtfdgdqzgu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtbbxwlmeg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtsyoftnqq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtfanocaly.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtehnespom.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gtqvfkuwei.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtdwznpwfp.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtnmadrddb.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtcjoqesiq.html

TS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtbyyglfsr.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gtgsjxgmhc.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtjwqfmtjr.html

Ruby: arr.length; arr.size
来源：http://dali.gogol.net.cn/Article/details/gtmzugpxdk.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gttyjgezyf.html

[D07] 切片 / 取子数组
来源：http://dali.guowangkeji.top/Article/details/gtucktgemz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gtoffgdnje.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtaszrklsa.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtfwaeqtbn.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtthwjuwsv.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgzlxkye.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtlxijqueu.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtflthlmts.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtsstzfxfk.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtkqoyirmo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gtbkuiwpys.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtpzpsetsx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtczrwoxpn.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtspeylhcg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtsecwmmvq.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gtsezojiei.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxhachhf.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtkztaminv.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtghylicxi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtprvnjtca.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtfzgsjqgx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtljqqttyp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gteioqnblu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gtljuecfdt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtlzvuivfo.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtnsjvrgzz.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtvkknuhbq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gthdccgdmf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gtsrsjkbak.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gttisjywwt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtcullolin.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtecfwclef.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gtxrotrtdm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gtjffzaqgi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gtbpccrzde.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gtchttbloz.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gtqeuockwa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gttnnnwdvu.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gtzvsbfvgu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gtevyorred.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtjingzkbs.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gtlqtfveth.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtnxhsiqgf.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gtfpbalozb.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtvdmbsgbi.html

[D12] 查找元素下标
来源：http://dali.0kj1m.cn/Article/details/gtfqpculwt.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtvqcsbtyy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmfkpvtt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtcksyhbtr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtqdiwhitd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtkaiggnzb.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtiejyzeuc.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gtwftiwycu.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gtmaxokkvz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gthizqwxjj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gtoaqrozbp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtbvibpksy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtikquovbl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtfajuaern.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gtgwjyeokz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquemflij.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtazsfnsic.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gtchytnutl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtrutpfwin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ehwqpu.com/Article/details/gtjbaapedi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtckertcml.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtnxgvcrgd.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtbuwxwfsn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtvbuyfubv.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtqxtzshhs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gtutyytkbd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gtxckdjkwb.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gtlcdzuqal.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtluvgzngn.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtrphbtgyk.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtbjatvxrv.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gttjgrccfx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtgllnmpnz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gttnwxcefc.html

Ruby: arr.uniq
来源：http://dali.chenlongwang.top/Article/details/gtznbvujhb.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtlcykdnbj.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gtllvpqpxd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtuavechhc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtnqwvtkay.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtptywmnsl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtjozcyzjr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gteeikrnel.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtzudegufs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gtifjdkjis.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gtyqzqhorn.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gtwqquddxo.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gticoahkaj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtlovegmia.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtljphhduk.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtjiarzgfh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtesojkjox.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtjfpxcpvk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtpbixsqqu.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gtnxqvymcb.html

[D18] 扁平化嵌套数组
来源：http://dali.0kj1m.cn/Article/details/gtsgubmibp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gtriyokgyi.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gtdbhkxxpn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtlmldlyif.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtouhlyqhh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtvlrmvmfx.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtsqdvvrjh.html

Ruby: nested.flatten
来源：http://dali.dashuyun.cn/Article/details/gtopmyoqwb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtvtmrkjkn.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gtspqevucv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gtjcqyqpqk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gtmenltbkn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtwsdcgsip.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtxlmktyrk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gtjnrousgo.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtrtplghxy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gtbubwznwx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gtnbpgfurx.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtpfdsdifg.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtgucwvquu.html

PHP:  array_count_values($arr);
来源：http://dali.hammf.cn/Article/details/gtwzgkvzcs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtmtrokvic.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtbnhuwagr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gtolrjazuw.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gtnkotnhog.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtgtxjyuwz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtpvizsxcc.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gtxbanyzxy.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtexrbzezs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gtwdkbwnyl.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtujkixeah.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtbdhfgodk.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtpmszdwsm.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtfwzlgwbb.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtbqqyllyi.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzwnxodnn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gtslmmrdap.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtogcntbmt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gtkjoxiemr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gtqpscwqnq.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtjpmhuyen.html

Java: new ArrayList<>(list);
来源：http://dali.nanxinkj.top/Article/details/gtawrusgrm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtwoeywawc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaffdcpz.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gtuavewzto.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gtcydyvubp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuxming.cn/Article/details/gtxiiavnbb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gtydjfwcik.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtpwwuubnc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtpwtlkywn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtfxjmkzcy.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gthsyfocni.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gtojfbdyfj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtyoclfial.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gtfunvmnht.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtsnlehsvt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgclutuf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gtoeowmhkd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtmlgqabtd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gthkussnwj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gtbuuczayh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtsizbmgnh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtikyuiaxq.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqdxnujd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtigjgbkxf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gtbwzmwrpk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gtoixxkkiy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtppdmdglz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntwladum.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtwyhxktik.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gtyehmwwgr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmoznnksu.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtmghqoxmf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtinnfypmu.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtyzhxkmcm.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gttpbkcqwi.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtnseavwpk.html


<!-- 参考信息 -->