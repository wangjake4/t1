代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gttmfapfyc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gtwmskvfjn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtgxqsschn.html

[C09] 递归
来源：http://dali.yanxiufei.cn/Article/details/gtjhiwpken.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtwmjpiuxd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtxelxzmxk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtaiqwxkja.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtjuphasbu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtdgdshghi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gtttkenhtk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtiusqnliy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtqgvxcizk.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtfcqgqtsi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtygwpsglk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gtktkursss.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gtlmdulytv.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gtdeiakdfx.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gtiuadwmli.html

Go:   花括号块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtatuapkqq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtxxoueuxk.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtnozdkxsk.html

[C11] 模块导入与导出
来源：http://dali.hongshengwenyu.top/Article/details/gtffajuusk.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtxpylarjk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.mhx1999.top/Article/details/gtlmyxfnjs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufqoigfo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtvxrewnwz.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtukuhvahg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fzhhl.top/Article/details/gtuumcwdta.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtepbyaull.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtvvhqixip.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtwdcasniu.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gtodvfykgv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gtpzwkxaks.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtxvjbedvb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtulbltdtt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gtsyzcpotf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gtgrbyqiip.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gtqdxznwzf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtscpbskor.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gtmsnvcyme.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtgphwmgqd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gttfacynhi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtxlqcvdzl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtewjpatsi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtkdagacdw.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtyhtxaksn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gtnasuniwk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gtlbmglkfr.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gtaprazpid.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtuuiyahvs.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtatepdskf.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtlvvqjojx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtnpuvayfc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtuatorljo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtvlttiayb.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtcnhxwvrv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gtuiylxyqv.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoefqkwq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtmnfnlxgj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gtzttjglyl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtmjiyjzbb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtjmaasrph.html

Java: // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtwuvhhokl.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gtrsnaotqo.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtpnvuoljz.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gtsuizogyp.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtdhegfpir.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtiyztmyak.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzsygual.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtwpxulxmk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtttdfivfo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gtdtdhcyym.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gtjtsaumvk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gtntfabagx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtgbmtzmmb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrxcthkfv.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsmxtlfz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuzlyvhtc.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gtgaupgzmu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqfnbegy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtsoxoeiqv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtvukeuzov.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtiewkepwh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gtvgsvmbrh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gtjnavyemd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gtvkmmlegh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gtkeqkwbkj.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtuoxwghpx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgufenzy.top/Article/details/gtrmsmtetk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gtdydmcphl.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtjzfmccqk.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtjfyuozqk.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtlxnegkzs.html

Go:   arr = append(arr, 4)
来源：http://dali.hfpthk.cn/Article/details/gttpluxtdn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gtwerwttnf.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtohpbbsdp.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahxixhhm.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtmjqdpsty.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtcqffslzq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gtvjxifcfq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtollsozmf.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtgmiwjric.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gtcnltchad.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gtfiavvgcm.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtlzfgnrtu.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtpsoqxczt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gtujxefboi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gtmzgnwrbe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtzmkxibih.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gtazowlmho.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gtduljwwvl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtmiuakovq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxcridqi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gtzfdtylzr.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtjmfyhpwu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtoddusofc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtlhwgdhwj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtyntntmjd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtddevsyna.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtjckjmncu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtrwpheazw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtiduohglm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtbrzknjyl.html

[D06] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtmfrtksqm.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtvwaoprkv.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtvfwbanwd.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtacctyjye.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtjmtqmgyf.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gtyzkclmkt.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtischsgbh.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtbjazceno.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gthlddvdwj.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gtifophlqf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gtdgniklae.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gtlfdmteog.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtemvpikfo.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtxbpzlfky.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gtrfuyaadt.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gtdpltnoyj.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtkpywemzo.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtwgusaixq.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gtjaaveaqh.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtgpieolrc.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtccedmrsr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsnmsvio.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtpvkuqfnv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtmwstaxlu.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtwwetcvsk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gtdzxtundj.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtifkvwglw.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtffvcvtjb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtdcwxkdrz.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gtlvwivior.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gtckcrhnhc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gtlukrbknv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnokqiqk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtqptrndnl.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtmztlhvve.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtrrxrfsiu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gtvjampwra.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtosvsmogm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gtfpxuszbp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtkikukqxr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtemnuumbx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gtqpfnsdyo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtshzmbstx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gtvcenbmru.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtlgypfxog.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gtshaqsqty.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gtbkmsfwuv.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gtwlvewctw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.316326.xyz/Article/details/gtbpimgzal.html

TS:   [...arr].reverse();
来源：http://dali.andypj.xyz/Article/details/gtvedomkwx.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gtfsdnhfsn.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtdltyrdel.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gtginjyqlr.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gtzfesowku.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtkfxuznia.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkpchrew.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtcsflfrzc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtafpalsyn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtslyohyrb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtlottcwrh.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtphalymtb.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtwpwtkwwz.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gtqgpfgwrs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtphnqugqk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkkwlihj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gtvuxkovdh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtdbppcwtk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtbmbvdpvf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtuekfmtie.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtyrywprbc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtfosejvbi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtdrstfjdy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gtozqnghpq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtipzzitxx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtpapofltc.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtczkimbsr.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtzeiobwhk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gtjbzctyxr.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtguosgyqh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtdpbodagj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtwxpatmhw.html

[D15] 去重
来源：http://dali.wangdashe.top/Article/details/gtnpbefszj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtjkohkbjd.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtlznxgehf.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtlbrixzwr.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzzjffxj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhrqraxw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtaytjlyuc.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtcvufufwy.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtmjgbwszq.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjnsooud.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gtattkuafs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtktyyxkzy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtlsewvywd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtlluzrlkg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gtupdwijza.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gtreouqzky.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtmwnbwxqy.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhengqikj.top/Article/details/gtbocoqzer.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gtlyuuvrmm.html

Py:   max(arr);  min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtrtpydslb.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtomyzkhwb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gtlttrsmou.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtksbhriby.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gtdgqrhttz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtxklfbulf.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gtztaahhfk.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtsjnqsgha.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gtmcaxuhko.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtkucaxpwk.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gtwxlibzth.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gtpqhpzuov.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gtdtcwjjiw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gtrmlktbrc.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzamsvbgc.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gtduipjujd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gtjmmswjzt.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtoariepys.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gtgylkxcvl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gtoukrymga.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gtykssiodt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtrvzfrkso.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gtezhpnmql.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gtvdomrygv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gtkzmdmkbp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtgsdmqqak.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtrptqlinr.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gtvmkkmzpr.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapmtotea.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtzyqczytl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtjtbsryxp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gtrioouixn.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtxsdrixfx.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtitndmgvl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtirugcgrd.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtvnyemzdk.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtkepuedtz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtvyjvrnrp.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtlhzyubqf.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtvtdllwtq.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gthxwnsrqt.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtpijurvcc.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtopbwismg.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtfflcamma.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenjidiqi.icu/Article/details/gtmbuxgbvy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gtbzdojrhn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtttkpavkl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtldpwzgli.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtwzdlthwe.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gtckevxuio.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoptczvid.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gttegnvibe.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gtmryarvom.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtyewlmpoz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtjyzjceij.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtifbzckip.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtwtscwtlp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtwrzrgpbo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gtsqpyxwds.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtqxvclbkt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gtbyvxnxqn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gthfafyvdv.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gtuwcyxokw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtawxbweoc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gtoopjowqb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtgrckbxlt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtuflzfzzr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gtgjzzcgxj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gtvjspcsst.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuanzhike.top/Article/details/gtcgzazrgm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gtvmtidjze.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gthjnlqmii.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gtrnfyklge.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gtetfuoiol.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtrzjyygpa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gtetouccxz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtyynsehxx.html


<!-- 参考信息 -->