代发 wailian999

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gt2nrrurfib.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gt2myqksujn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gt2jvmlemls.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gt2rwmopzfa.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gt2hfzzdobt.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gt2urkfczlj.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2qktuiaue.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gt2xqmwjtsi.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gt2hsdpuhlj.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gt2igeonmhn.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gt2tqsuolxo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258.top/Article/details/gt2qkbzwmuo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyvaulur.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gt2cbdfvslz.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjngqnvw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnabsxcr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gt2ewemphyj.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gt2fqlnagsl.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gt2vbjfmycv.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gt2yurnccrp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibzchthe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gt2udmiunkl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvirjwzv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gt2uzyylshf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gt2wvugadfe.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gt2zvgtoald.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2cdmupgra.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gt2bkgmcjkg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gt2fwuslcdj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2urzvcekm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gt2zddwfzyt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2etoiplya.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2qphtdqkj.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gt2rsmdzzar.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhoulong.xyz/Article/details/gt2rutntjst.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gt2wlxtviko.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gt2vkegkpmf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gt2ikybhbxt.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2zlwmsljx.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gt2grhbwckv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gt2jiwppgua.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gt2lrubodyv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gt2ggqpwdyz.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2juztbdpw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldvfaycm.html

[C15] 解构 / 展开参数
来源：http://dali.cheryme.top/Article/details/gt2uysjkcli.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gt2exxfxyqt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gt2emjmdwlm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2cmezmsud.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gt2fzxitwni.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gt2sqlpbyln.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2riqxelkv.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gt2qrfnkpvz.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gt2enhwtbty.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2paeoxjen.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tianlin.xyz/Article/details/gt2nnfdgzwx.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gt2fiymlzkt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gt2tgsuvymr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangdashe.top/Article/details/gt2gyrohlur.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gzhubu.top/Article/details/gt2pchbmmlw.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gt2paswknre.html

Ruby: # 无重载：靠动态参数
来源：http://dali.snrcjt.cn/Article/details/gt2jyfmtnvl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dabqbwdh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2hwpjytjf.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gt2nhptnaus.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2vdlxsuxk.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqmncmsq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gt2yumrntbw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gt2vlieadfi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gt2ojncgzsy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gt2pmozesrx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2dqxocfbo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gt2vvutwxmp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gt2vbofqadk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gt2cxzxqgfw.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gt2gjrraftz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2blmbqjcl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrolxofk.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gt2tqvxcnyl.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gt2uzevzcbf.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjihgxpx.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gt2vvfozvcu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gt2zsvpfagy.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gt2swsxeexo.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2ftjqhkoi.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2sqpeyaxs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gt2doxaprwv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gt2ufygjzpj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcwawuxn.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2ozcjqfyn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2lmehyrqx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gt2nozmpbpt.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2icyjaiex.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gt2budtpmsw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fijjozmf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gt2okvsgfjs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhsyunhu.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gt2klqzbsrv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gt2otbzumuh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gt2glrufust.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gt2iguellgr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gt2vswiyfid.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gt2jxevkaub.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2sjynwefz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nritmvdl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2oqrvgwto.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gt2yeyjvlit.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gt2alukogdv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2ziwvebbu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gt2bjcvuoyc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2kcfivdit.html

[D06] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2obsarosm.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2nhvoizug.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gt2oguxiozm.html

JS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gt2jfrkvaxs.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2kzyqsypy.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gt2nffsglrv.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2xzzhtupp.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gt2rvmxwfax.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gt2hikfzgkp.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gt2cyohpsmd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gt2nyvemhpc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2tvpzbrru.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2xdxrtdlr.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2bjeowlds.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2pkkqkmgg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2aspneeqn.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdqsxthb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2elpbvhkf.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gt2hxuhaovv.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gt2eecrltsx.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gt2ucsxlwme.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gt2gakqevaq.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbezwyej.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gt2hruunsqb.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gt2zesfvlzo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gt2lbpgqppz.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpnadmcy.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gt2wlzjixkl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2kaesxmts.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gt2joggoelg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gt2jyihjjnc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gt2hswuvzte.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gt2najrfyat.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2qutqywdl.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gt2cvmazwab.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gt2ogztndpy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gt2lkbrwzpe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gt2fpiyqkhq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gt2fpyoaakb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gt2jxdabiui.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2ftoqtdhj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gt2cugtwbvj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gt2obkaqtqi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gt2xqpfuffk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gt2cccbgwqi.html

[D11] 反转数组
来源：http://dali.mhx1999.top/Article/details/gt2zbjermta.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gt2imkrlrvh.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbsnrtbt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gt2nfdfpafo.html

TS:   [...arr].reverse();
来源：http://dali.mhx1999.top/Article/details/gt2dbhqmnrf.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gt2zbgwsgox.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2kajvohyf.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gt2cffmwhoe.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gt2kuxuqziy.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gt2rpcozkyk.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gt2rmephujb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2lyzrdawl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2rbfujube.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2ejvbbiyd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gt2wupzmzgg.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2njnijrxk.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gt2pfdcruxf.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gt2cbgmrurk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gt2kviashjl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gt2hwgpektr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gt2nxbbykbt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2pwqrpaqm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2vfetdtpr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2mbumnkpa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gt2qstgoxtg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gt2vieosziy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2wirlcoex.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gt2rzfftbyq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gt2oezyfnuf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2xgzexyey.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2tgustkwm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2dwopgodm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2enswdylt.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2mfhiikdw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2jzrnumeo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2veihhpps.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gt2filzjpkl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtbkuuhh.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gt2fovfkdyn.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gt2lbhtxsok.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpfgzzyr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gt2egqtbayy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gt2zpfjssgs.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gt2hcasanph.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2njkuwbvx.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gt2opodpunr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2fhdhkiiy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gt2wqxgponz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2zjlpjrov.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2hbuqsqlk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gt2vuqhhwhf.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gt2pfayrfol.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2qekzgxtn.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gt2xuvwgseu.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gt2whlxodqm.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2rootywbq.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gt2egyvywst.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gt2uatscrsk.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsrtyvww.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gt2herfgvka.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2tajkvngw.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gt2orekwbbt.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gt2yxhtudwl.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gt2xxzoqayg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gt2elwuyrgn.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gt2nwkmzgqx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nefqgvcd.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gt2akbajucg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ivvv.top/Article/details/gt2rgfupjeu.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gt2ornjvzbu.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gt2goiclocu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2hbkbeycl.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzdslfqn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yowilynn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gt2iuxgshmm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gt2whuuowop.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gt2hccovzzk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvfrlllr.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gt2omopldgz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gt2qvhwqvrb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gt2gdybqhnb.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgptlcbt.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gt2mdzsszzn.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwbujyif.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2gomgribv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gt2jfehtacm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gt2ncuypycz.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gt2ffzzllhx.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gt2iqmtfqdm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gt2gxuepfxx.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2etetxmln.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2npqvirru.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwzwktiu.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2hvdjqlxk.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2qenmlmfs.html

Java: list.contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2fgdrwvqo.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihvouenq.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gt2egobycma.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phssnfxz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gt2vpaahwtk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2ehawbmgu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gt2csgsemmu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2qkvxopwr.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gt2yllivbqy.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gt2tictwqdn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kllacsle.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gt2catgvzfv.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gt2jihecrlu.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmpmgpdj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2pzefygcl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2pnfdklsp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gt2yjxwdbic.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2jdirqobu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gt2cwbkxkny.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2kdhctnws.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gt2slsnlarj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwgeuhps.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gt2skzsghyn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gt2sqhxcxlj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cqqwz.cn/Article/details/gt2njctcwbd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gt2ljqrkcph.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2zjjzvyzu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhhplxfj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gt2erlpefpb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gt2yifcylzr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gt2ijflbqmm.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gt2ayziluvv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gt2hqfbjtcy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gt2rzyuttwq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huittsvi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gt2qezrvxuh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.iojbl.cn/Article/details/gt2yprsmnol.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gt2iedpthvx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gt2dkxteohw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gt2yxnisysy.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gt2vbjrfqtf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2jhqizvte.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2uaswamml.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvbxjdcr.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2tqrceeme.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2vkflrdqc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gt2ikxvyaug.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2wwexpcqg.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2zaessvuw.html


<!-- 参考信息 -->