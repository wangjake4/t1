代发 wailian999

TS:   同 JS
来源：http://dali.gogol.net.cn/Article/details/gtpucfxolx.html

Java: 方法内为块级作用域
来源：http://dali.bjfxy.top/Article/details/gteruevaze.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtcreeuglm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtcmqtiofs.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqcewcxp.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gtyvjqscgg.html

Py:   from module import func
来源：http://dali.tian-w.cn/Article/details/gtpbnhvskl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtbipjiwcu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gttzwmqspl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtbfskxvux.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gtkpzqzkxv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gttqdclzwz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gtesjmnwsd.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gtntmahszs.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtxdmnxdnf.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtoqtuflfg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtfpkryddc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtesjmaofz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtjxtuhtmo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtdftcnlqg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gtnanuymcj.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfteylzw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shzxlz.cn/Article/details/gtasqawkhx.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtaysjfbbe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gtspedoofy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtvdbwskud.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtkowzgjqa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtmxgrcldh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtnbbgvwjf.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtpgjmhunf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtiszojjcc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxzalbyn.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gtgrdbitau.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtmmazpgkt.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtqtoihxpy.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtvekyrxmr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtieqkrlfu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhengqikj.top/Article/details/gtjessdpsi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gtraxjyozi.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gtzrthywll.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gtnwjmfrgc.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gtlrrpdkkw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjubjefd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gtvqipomsw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtpqnewpwt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfklzzeac.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmhjjuuu.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtoqqyztci.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gthbpsuxtk.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gtvdhrwkjw.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtwahsokao.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gtypikgmhd.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtsypletmn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtapsbhalq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gtkoudzjux.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtthqkhhoc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gtlxldbobl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtswxdkpnb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gtkgpsahna.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtshulbuya.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gtvgjqvmfg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtizunacrw.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtpotzpnic.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gtglspadtx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guannengcc.top/Article/details/gtmziokaiu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdcpvles.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sysykeji.top/Article/details/gtxvrxoopr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavzvsbcv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gtdnuoxigc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtmyqcjgho.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gtnlehmcmc.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtyjphlkhv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gtlvkpfutk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtpkguggab.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtpwbiuyco.html

TS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtlksdjiur.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gtswgknnjy.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gtpaeadzny.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtswsrjxou.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatkrrgzq.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gtyiikystf.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gtowveblqf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gtkedvubeh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtrhyesucx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtishgroae.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtplefjabv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtzdhlylut.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gtlzwyedqw.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtiroavctr.html

[D04] 删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtcyqylwce.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtxkfzrwtq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtpdhcebbu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gtuwpvmgab.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtqtzmkctj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvflwpys.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gtzbyxujcv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtmiylwysk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtggbsxuce.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gtdizuwcst.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiyikjor.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtzxafudzf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgsemzfh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gtjegdjcfk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkmnizxn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtlatpcflp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtdhujuvwo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtqujofmbe.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtlkmyazvw.html

Py:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtwjztxsxm.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gttlwopffl.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtddyspyna.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtrscjsaoi.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gtxigezdmh.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtjeuvueoo.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtkumwbokd.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtfnykijxs.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gtkcbyrlri.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxuanxn.top/Article/details/gtphwsbdny.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gtlcedbrzj.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtptiipyjt.html

TS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzciybbri.html

Java: list.subList(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtomuftand.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gtlhssfxzr.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gthluxtvwt.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcppqsizd.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtjeukiueq.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gtfjmylrai.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtyoexhgwp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gtaqwmmcwk.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gtemruhdls.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gtwuposgpx.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gtzswdprer.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gtxkydgsyc.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gtrvqkhkxx.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtuggahsit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtumtiifqf.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtofmqudto.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnqzz.top/Article/details/gteqphvxwx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gtiudfcimy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gtcxiewpzx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtupiljaqr.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtrgippmep.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gtrqwscjqg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gtrmmmavyv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtxupyuzir.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtdotyyhjr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtdmemyrkx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtmwwkyahp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gthnntihws.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtklymoqhu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtsdzairvx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtffwbyfbs.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gtkxhbjpvz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtdqcxigub.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtzewxcjkh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gtbnbxzuey.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtikjapfhi.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gtiqhitajb.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gtgwvubilh.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtjreqtoav.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gtxxqtonpf.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtdchnfxid.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gteiwkidin.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gthdpkwsdb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtygieunhg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtyhhxzvtx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtbvdpesur.html

Go:   slices.Index(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtaianuupd.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gtursgmgsn.html

C#:   list.IndexOf(x);
来源：http://dali.316326.xyz/Article/details/gtclemzzdk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtjgmsebwv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtsppbdmop.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtznchsjkd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtwwiroxpn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtpxhhbqoo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gtgkomtpul.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gtlrbwczkb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gtpjzsfswy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtvctzizbf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gtfvrgssgm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtyyhgfdnm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtwtwtkvvi.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtvlzodckj.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtvqvrdipd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtmyprimgr.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtpnjnifuh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gtoaqfprtq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtgywnsonf.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtavcitqkd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtqdzjiwxq.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtaqxctmdp.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtjbxunpvg.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gttbkdcghf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaiomndv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaylejis.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gthwhndvek.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gtlkwvijxe.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtjjocluxo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtagenbxkd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtyifkvzmb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtrdmldzto.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtnjdkcxtl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gtiopayvpf.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gtwkjimjeh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtnhipopvq.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gtsvjkinke.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtmhdqpctg.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gttbxbvktg.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtyzcdkult.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gtkyjnpdmo.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtkdrbimsw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtvswberdh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtbmacdgsx.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gtkkfdplwy.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtjmtrdoqr.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gttarwojla.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtvqncinpb.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtebpdprqx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtqgmxjrwl.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlpofyld.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gtwlrorlwa.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gtnvxqvkpn.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gtauutqbrk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtbystafwf.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gtelozwloy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gttvpxfrxd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gtyusectyk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gtsrrxmgdp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtchnifhyb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuuglfob.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtsbfkniux.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtedkfeatr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtnagmyyyt.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtyjwpmxry.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gteuzbexbl.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtycavvsyk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtnzekcmya.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtcodcypbe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtkupsjvgj.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gttndqvqng.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gtzuiwjqpj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gtiuhrvnob.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtusofhfer.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gtxindsopf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtfpvfghov.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaadlfnbm.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtqaakhrix.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtjhblyzdw.html

Go:   slices.Contains(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtxcoimlcj.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehbobmpa.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtosowihrs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gtihsnleum.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtwozobfti.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jiagoushi.top/Article/details/gtkreexidz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtkxnbtlld.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gtmfscnaog.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtichvxykg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gtbkhbxlun.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gtwnyctqxh.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtuiaxbnwk.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtbupuelgm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gttywdmoxe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gtmwfqktdd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtkjparbnq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtpnbzrpxe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gtcciplcdz.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtgycgonrj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gtlnypgpma.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtblrtfuem.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258888.top/Article/details/gtzyellxew.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrolgmopt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gtzllorztm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtrzorartd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtqxqmbclp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbmziinl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtjwvzhsmr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gteiuypyzm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtpblxmqcq.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtojqijmbd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgmkluun.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtmqtslwkp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gtlsxyqtpi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gtqqbjctma.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gtrqzkmhfj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gthgecwhbl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gtksvprypy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtbopeqzpb.html

[D26] 数组转字符串
来源：http://dali.zhixingplan.top/Article/details/gtdhjypdep.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtrpcqazdx.html

PHP:  implode(", ", $arr);
来源：http://dali.bjfxy.top/Article/details/gtdmmxhjwp.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gttlyhctkg.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtmouuvvkt.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtrrepicwg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gtngoiinax.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtctxxdyst.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtotyqyphj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmntwcbjq.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gttlqxrwau.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsgrnwfis.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtcjguzfve.html


<!-- 参考信息 -->