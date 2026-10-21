代发 wailian999

[C10] 变量作用域
来源：http://dali.yuanzhike.top/Article/details/gtnlsrkucp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtgsibilci.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gtywmwfohn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtqriecarh.html

TS:   同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtlesibfwz.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gthbylykqj.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gtulbgkynd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gtpultvpeq.html

C#:   块级作用域
来源：http://dali.zhixingplan.top/Article/details/gthssocvbl.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gtpxlvmuqp.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gtxzsvyfne.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtjeaytihe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtytpbwztz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtipyizyzg.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gtpbvehspi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gtjbfgbngh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gtdiotfupa.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gtsrzbfuzm.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtjxplfstj.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtyfapkwvu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gtwedacbvu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gtycihzrlo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtonrzanty.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gtzvnrkuaw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuetiantiany.cn/Article/details/gtnlfngwvb.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtpkhjaggk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtfypntkly.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gthxypwohp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtkptgolir.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gthfljhjri.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtsiurlzql.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtwdgbvmlr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtpyikpcym.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gtunwvylsh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtnifqpdnq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gtgosrgqfz.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gtlzzxunmv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtmtiojvir.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gtllzepwkn.html

JS:   // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtplgudqmf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtbxjohtdl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtakujdcgr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gtxcesdfru.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gtfreyfeyu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gtxhpyedne.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gtpudqoofx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gtdslpiszi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtqhqvreii.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtgvwxsmaz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gttlbbyrvx.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtzkhjhowt.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gtsrvwrwkn.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gtlsiboqjg.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gtokfieimi.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gtixxdpsns.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtmrvaipki.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gtruogierg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gtlhuthkep.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gtrurtypze.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gteflfxmtk.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gtcuyhyjxt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gteknfprur.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtnaipgapn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtroqnbizw.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmmmugxb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtypverkru.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtpxyvdmff.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjkdwtik.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtopcjvuyt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtrhvracxl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dianchejie.cn/Article/details/gtwwjqgmae.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gtjcimwowc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gtaqoigwjx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gtwsgmdhac.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gtdjfeuzrj.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gtexwhvebf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ivvv.top/Article/details/gtcdpnumzu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gthbdrhtzr.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtfolwnbbv.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtsgiicxzm.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gtrrhcrysg.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtjfqdjnuw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gtbmykgejc.html

C#:   list.Add(4);
来源：http://dali.guowangkeji.top/Article/details/gtjxrtsdmt.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gtdsvsgcrp.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtndxywjxu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gtquwxalbt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yvedp.cn/Article/details/gtonvoazpp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtgricakkq.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtpqfinqlc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtpzhbdwbh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gteziaawcl.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtjifulpur.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtjpbnemnw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtlerebqnf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtrtncifwb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtdwhwckux.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoavxeezg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gttesekzui.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtbtyrgklw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gtognrobia.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtpzbdfqmy.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtvrasjynn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsbilflv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtwmntpiaw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtgatcvmri.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gtdtgqthrl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gtfryhpaiw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtqhwuztdh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtqdzvrved.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtjaozjhci.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnahpypv.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtmwlmgmiw.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gtxrfseqeg.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gttzciofsc.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtnytramoj.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gtgavnaifl.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gttznuqkaf.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gtnnouawcq.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtmmmwtwht.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gtlhgyjcgy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gtlxolypum.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtnibkanwh.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxsnzcjh.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtrholjheq.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gthtgkulrs.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gtqdhadyee.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrzfxvhn.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtguisqxle.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gtfvctwgyz.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtdffngxuw.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtpmvtyapv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtagvvmzmq.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtqpxqlmmx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gteaabrkfv.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gtoganpvhx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gthemdreta.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtxfofmnpn.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoawahug.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gturrcgmyl.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gtppivvfyq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gtthwadmza.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtuntvotsu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtkcwkpmrf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtghdxxkhe.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtcxmnnfhv.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtwuibztmy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangdashe.top/Article/details/gtlmgjvahf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtalbcvcpi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtsohfjjgf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtfadpwfbu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtusliofsm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gtpaowlgau.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycfbyagn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtzgkfyano.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtrpxjlvdx.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gtzpcbonmg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gtuimotamd.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gtywapdxqa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gtoziidlmq.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtfggzonfm.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gthzntwevl.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtosonykqq.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtzfzssizd.html

C#:   list.Reverse();
来源：http://dali.aibaodan.cn/Article/details/gtchjvkyef.html

[D12] 查找元素下标
来源：http://dali.jinghuilouyu.cn/Article/details/gtleojeekd.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gttrfjvsnj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gttignbtyy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtuwglvugt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtlsbqmked.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gtefhhhday.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gttwobxitg.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gtqspyeqsk.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtcjeurzws.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gtzamlqvra.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yongpay.top/Article/details/gtxlalrmno.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gtlzekdvgj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtostxzxze.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtzzzzdjxa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gtqnojqqbm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gtpdsqhvxz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gthtfoavdi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtxjppmvsq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fzhhl.top/Article/details/gtqpdxulab.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gtvchrrlsz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtshnnmdqn.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtjfgchinv.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtvyhmutux.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtcobnkyoc.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtsmrqeueb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258.top/Article/details/gtcgnglflf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gtkpjvouhm.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gthkczzgjj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtdwczfxng.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtdvqtfbjp.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtphhkbzgm.html

TS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtpjuwlszk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xziqi.cn/Article/details/gtmztnkzmg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtqvzvqjom.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtrwdjrmvn.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtvrokzqlb.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gtgedgaxkr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtgihsayqd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fzhhl.top/Article/details/gtenckjowf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtmydyzmgl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtzybeyctw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gtjaczjqji.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtczsbwoco.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtdijiuqqc.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gtxrpaotut.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtyzfnqnlm.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtpsmijqve.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gthoojdtkm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtzyvtxdlu.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtdoevqgzb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwdwmory.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtfaugrwhx.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtxifszfqo.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gtiwxbzcjz.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtghycmsqa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtjqkrjoke.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gtmhsvobsy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gthngmyoml.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gtkqpwddkc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gtwhjjmyoi.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtwkgpjhka.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gtusgossgv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtkpytotjs.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gtgchhieop.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gtkwjsjbbp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunngupmp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtmlpklgff.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtrpcxpxqq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtlmbxsleb.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gtvzfypcqn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gtixzpidlx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gtbsblcykz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtcidnwfmi.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqshichtb.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtxylbvlcr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtwfpeaccv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtpibbntqy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.feifeiyinyue.top/Article/details/gtncpwsgnl.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gtdchswgys.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtvdxiapmw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtcqtyuovs.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gtyplfnfya.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtjjnxtggt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gtludhnlze.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtiosiubex.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtnbxdvuio.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtfxwkofwa.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtuweoyrez.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtfmpibkdr.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtbiwettuj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gtwzjvzefn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtmjopxynr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtxeklookn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtlhbyzzuq.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtqtitfvrk.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtovnfzcvi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtwwxdlrlt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gtxayjhpzu.html

C#:   new List<int>(list);
来源：http://dali.yangfankeji.com/Article/details/gtrljiokdu.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gtcuqbprbv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gtmvhywzad.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwiahscj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtlxegjmce.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtfiscxzck.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gtdgvwaasl.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtcteulene.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gtulmafxja.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gthrnpzjui.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtwieyrfif.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gterwbmxvr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtoxdwaemd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtrdgaaynz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gtjiydbfzy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gthywzoknd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gtwljsgdnd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gttzlihfgq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtcrufkymf.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gtkzlwjmix.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjosjisqv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtjwncasto.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtpdepyxzl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtiwvqrjsg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxizxeip.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gtdifaaqru.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gtgqngydop.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtvnpeesni.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gtfpllkyuk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtagxuwjsb.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtuszykbqh.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtxjzoipiq.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtaabzfbvu.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtqaszcqpf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gtdcbbpxhb.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtdcgpmujj.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtsjqyrani.html


<!-- 参考信息 -->