代发 wailian999

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gt2vibyzdlc.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2dekwzepz.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2mixwyqak.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gt2qavmwrnd.html

C#:   块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2fdqtakne.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gt2reanoszt.html

Py:   from module import func
来源：http://dali.shuidangran.top/Article/details/gt2vazmahle.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gt2gypeplvj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obnugurv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gt2sswkkqms.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gt2bxokrdwa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbvsuwba.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gt2xsuwwhhb.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gt2nmwsmhpd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gt2ojsiqqlx.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gt2gfnicznd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gt2fqvfeqps.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gt2lavyexjv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gt2hvlxiymt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkfxkztq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gt2gnaagwho.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gt2dbjwflai.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mribyoyk.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gt2lowwpigg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gt2lkjqvljg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2hxdlsakh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gt2yjfqmsnd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2wtkbdetq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2utccqydq.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gt2bxbavxco.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gt2cglaillw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gt2zxpfakah.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gt2jnpgjfnu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gt2vyylgrzc.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gt2axhdyolh.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2xbieymua.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vbzfzzpu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gt2jgrkjhub.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jlsjyb.cn/Article/details/gt2uynjrvcg.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2cjzpcujd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gt2grptmtju.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2equngbeh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2niiwcuda.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gt2dopghuyu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2rariptgr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gt2kqtjrxto.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2jthpalyv.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2pwwwzaob.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gt2pnknzvow.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gt2kjyqachg.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gt2wsrfoohi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gt2owlvhfxn.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gt2pnxbhpfa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gt2mkwiuftl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gt2kvjspeay.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gt2kkntopex.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gt2xalyhvgb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gt2flsqwdmg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2negpxnzu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcfpmuhs.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gt2whxagzrn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fxxxddkm.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2dvorawxe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gt2bmgzcafp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2pvxmppda.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2vlybiqno.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gt2hnruvjiz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gt2cdjkpayk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbtjpqrm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2pwqjpobn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ivvv.top/Article/details/gt2yuwnmnww.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gt2nfnzdpzb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gt2puulpaou.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gt2xnrzuvej.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2rfkyxjjs.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2kpwfjfnr.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gt2cszldscd.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2swxmovub.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqhflmsz.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2cwrzhhqs.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gt2xxdmtskq.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2vlkcrcum.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gt2afztftrk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinghuilouyu.cn/Article/details/gt2seoslmlu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2itippdri.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2trppjnok.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gt2clycvsio.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gt2kapedwnj.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2ctynetkz.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gt2tvcozimd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gt2xrtazpnc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2wuncassf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gt2cdcuazmm.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2pbdzkzjn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gt2sqeygbjm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gt2ujlpuisj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gt2ohrpwyah.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuxming.cn/Article/details/gt2fsntzxqz.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gt2dzdzqzbn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gt2ixwvksuq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2rnwuprze.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2kxovjjkh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.bjfxy.top/Article/details/gt2vsvumwme.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gt2nlqtkxim.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2gbociler.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2utfgnokq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2pmiqjejf.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2vtfmgvvx.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpigcqeh.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2vyaikkxk.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gt2lvvucphm.html

TS:   arr.length
来源：http://dali.hammf.cn/Article/details/gt2kciggfoa.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gt2fkqsktvb.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2ntxcocgk.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2ofqoimul.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gt2mvnvrgqr.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gt2isbhxtxe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gt2pucffbtb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hiufqpcv.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2tmsbjzup.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyabmgka.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2atcwsuqp.html

Go:   arr[1:4]
来源：http://dali.yueranfly.top/Article/details/gt2uesqwiyj.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gt2lyyfecxr.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gt2zzsslnqk.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gt2yciifwgi.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2irvnnlml.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gt2gbkmsrxp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gt2igxoirjp.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gt2mqjkwuit.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2mhdboltl.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gt2cylkhmca.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2layolzoo.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gt2ddfjvnzy.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gt2ftsjezsl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gt2olkqoxdk.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2cqrruxml.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvryjjln.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gt2kgxrhouj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gt2swbrrkxx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2rcbbduan.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2ouwasbvk.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gt2lnjqzjyo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwnmgxla.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gt2vvkuwzsu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gt2sxlbffkx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gt2jfuedlhk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2shebhvex.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gt2ugpaimiy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gt2tyoxiwty.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2gbweewnz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gt2iovamist.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gt2acxfutke.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gt2dekrgoea.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2mcodwdjy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxinkj.top/Article/details/gt2mdepoqbh.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdiopmga.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcfwcbco.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2nddizsyh.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2yobezeui.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2rvrbxoid.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gt2sbhaumva.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2qeefxfqp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gt2mtuiuzqe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2kotivxqp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gt2ygvildym.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gt2jdszbxwm.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shfnzbji.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gt2phqmjlbx.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gt2abjzaoni.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gt2wnvutrun.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gt2zlqmukzk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gt2rmhjeqod.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2bnixwdzf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gt2aupgeott.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gt2xsuehmuz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gt2kmfyeuhf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2cutgknmx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2mzirovnn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gt2byryjnpm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2cmaswntp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gt2ieasuznk.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2qjrqnzzf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2arrfjehc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjjgwxqi.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2mixuppfz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2aeviwhdq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2bspawxfm.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gt2cdzlipug.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gt2fgqoezos.html

PHP:  array_unique($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlqhyxun.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2vramqndj.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2ydaobwdg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gt2vllxnyic.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gt2xsaxubav.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkfqiktm.html

C#:   list.Distinct().ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2mmumpthg.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gt2aiiqvnae.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2zsydzekq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gt2rqrhjcug.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2aipuapnr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lakfpxcf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gt2btahhwpt.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gt2fsabyfvr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gt2odpzhfwa.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gt2hpcyipca.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gt2zovmeayy.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2hkhwcsxr.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2osdldbcd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gt2cblmwkcq.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gt2nnztabwy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2utzjckvf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2gxxalhym.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2olmjvwox.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2ufussnnk.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gt2ogchdunt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gt2axpcnvck.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gt2axkkcdsj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mikrswgz.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gt2qvkicfnc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gt2effwlviv.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gt2sgkkxiac.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gt2ifhvxvxp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwiomho.html

[D19] 按字段分组
来源：http://dali.jlsjyb.cn/Article/details/gt2rgnmkfcf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2tznehkup.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gt2sudckgci.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gt2pwcseodc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gt2pjdktocg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gt2obhntofa.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gt2kivskqyh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sxryk.cn/Article/details/gt2dkzbhfco.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gt2rzgxmahz.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gt2agivvber.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2gpmmnalr.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gt2nrcumsij.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2xrxtjhsl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2tmzejutu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gt2sggwfcna.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gt2ggldrcor.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gt2uxuxcxly.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gt2nqoqvgds.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gt2wwvpsazj.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfkjsnxa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gt2yyoufpic.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gt2mfapnfhu.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2chamcqed.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2sosxoodb.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2wxiqniut.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2yyzmsape.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvstajkn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gt2zwnozjct.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gt2llwqjmwb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gt2zkyupdwc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gt2emsivkrr.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gt2xlyuhycl.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2fgrfxden.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gt2jocpjwac.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2csgjgtbd.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gt2ontcypsl.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gt2dntyouqi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gt2znxpbnuu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gt2fxcacmfd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2guabuedt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2xipsifsk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gt2cmkknpta.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2ifwwlvjz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gt2hrqmgoxx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gt2zuolhozq.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gt2shgcicju.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puivwkxa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gt2kjtlchei.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2mqibtaww.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2ckrmjuip.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gt2cfylstmo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gt2kqmpkbgw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gt2oblxopjf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gt2yvlkczru.html

[D25] Set 集合去重与交并差
来源：http://dali.zhongyouzk.top/Article/details/gt2jdumczvk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gt2inzsbygz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gt2xuafzylm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gt2iyohgghq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gt2pjgtevjr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gt2ckvemxkn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gt2imxafrio.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gt2qgkkodoj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2yanyfbbe.html

[D26] 数组转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsykazbg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gt2qjrrpkyj.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eopwcztz.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2lixkfbyj.html

TS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2uyfafrdq.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2gvpkfvyr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gt2hwflvaea.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2dxvkgkla.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2vmhjwfrj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouyhybun.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czukdigs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2hsrimrhx.html

[E01] 拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2djfieovr.html


<!-- 参考信息 -->