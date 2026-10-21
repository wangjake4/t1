代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtsmujxlqv.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gtdljuqobx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gtkbmudusk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtlxsaddfb.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtjqwufebx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gtdxkqfaft.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtxiicvxzd.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtarcihlsr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gttgloyofg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gtqmtzxmzp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbpvpkue.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtwmphhjmp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gtrsfyjgil.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gtlvelimbz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gtyhevgwbs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtlgygmnxf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtecmbnpov.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gtsfutwruc.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gthaatgiee.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtvpvdcxcv.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gtaqmxnetl.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gtlvoidegn.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtwkzenqvu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvycbcfl.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gtgxzhnozv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtazghujgu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtqauzwhqd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gtvlktsgir.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtewagqfej.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenlongwang.top/Article/details/gtezpvizqr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gthbhppbug.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnuuvpulp.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtdicngjem.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpquzmnzs.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtifcanafo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtomjscwze.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtmhwlydnb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtiywqmgey.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtgoxmhote.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtrsstvkmk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizwexspl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtmxjhjxrg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtrwwktmaz.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtgrofxwhs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtfniwouuc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gtgjugmqfp.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtolfzvnhl.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtodasfxuk.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtvgsbkwab.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtanemumxt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gtcyaneokb.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gtqjqxgmhj.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gtvxhxsbzn.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtrrajjmsx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gthyhrzdly.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yvedp.cn/Article/details/gtgzjxmott.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtddvyklrn.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtptizlgwz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtupxeavnb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtcyekgrux.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtwxpdhams.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtmomszxjh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258.top/Article/details/gtjwuchphu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ydzc1.top/Article/details/gtuwhjilbp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gthovtpoud.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtyhpmsxpa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gthqhrouix.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gttvnnemkg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guowangkeji.top/Article/details/gtyebyhyxk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gtzmlxoohd.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gtneextcjn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtzqdeqwil.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gthqwemdib.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtphscdodx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gthrmmhawz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gtxodolsqd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtqmnglhmu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtlatgcnjy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtdfndunsv.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gticmknnhb.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gthoqotdvc.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtkkzcobum.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtgxfudaeh.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gthjucwauv.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtfhmmikcf.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtsgfeylis.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtroqqmhwz.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gtgothxojj.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gttsivqmdl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gtlyidvvgl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtbunyptnl.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtqbuvlluz.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtymezsrfv.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gtvjczewea.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtrrjhrzqq.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtrssmmyjp.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtmscfovhx.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gtficvwqrk.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gtgumirtzg.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gtesllbkgb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shzxlz.cn/Article/details/gteifvexwk.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gtddpbihrs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gtrqvaobrr.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhnizxqk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gtkpoudlez.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmablbhj.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gtaxgtmrja.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtepvtghrp.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gtuwpjhrpm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hysaishi.cn/Article/details/gtskiraakq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gteffstgmf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtahfaohrg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtkihubfxe.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtvwknoelf.html

C#:   list.Sort();
来源：http://dali.sxryk.cn/Article/details/gtekuovbpe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtiogcvfqt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.bjfxy.top/Article/details/gtowbjgiwn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxtbpdba.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtsbksyvnz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtfpfuchzr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gtgldjcmvz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtcgkshupk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gtsturffcr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gtyddnrykt.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gtfzsdvgxi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gtjcviogcl.html

PHP:  array_reverse($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdwpeawv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtuoramqyl.html

TS:   [...arr].reverse();
来源：http://dali.xinyue.icu/Article/details/gtbbpdgque.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gtcjhkrqjv.html

Go:   slices.Reverse(arr)
来源：http://dali.chenlongwang.top/Article/details/gtmwlxdckg.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gtkzxvmcim.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtevgmrngb.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtxbgrknxo.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gthueilrso.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gttroymqln.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtvokhbbnq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtyanfquob.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gtwrsnimgl.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtarmqbnfr.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gtjtcigpmr.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gtxsohxyog.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtmdktbmch.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtgygqzczp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtzlxyioax.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtzoccadtt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtczpgipyi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gtpwfsspfp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gtflopaekw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gtsihikmxx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtkwrmvxba.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtdaeucuya.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtidwfdzrw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtadkxpslh.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtdthtfbdu.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtmfqcxndz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtomhmxxij.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuswunko.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gthbtkhgav.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtldywvfvm.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtszutttmj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtkbusjuao.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtfrrrqavp.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gthlworwou.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtxrrsztbp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gtuakxzcnt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfypwefb.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtvbwpemnt.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gtjklykecq.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoifymmd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtlpnqello.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuaoaisz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtkritgblz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gthtcledbp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtynfsynij.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtizuhwhkc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtsboixfoi.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtoshgfmib.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gtkxccbbzt.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtoryawjwr.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtqtjvudik.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtncdzqxll.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gtcgubxpcz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtscuatdkz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gtlogqegiy.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gtnngigqwc.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gtdvxmafjg.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gtnqeaxfwe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtowpovphk.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gtrokipisq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gtvmkudfhv.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtnhrjdyuc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtrkyqyylw.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gtuezyydug.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gtvoeldewz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gthkvabfna.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtnpnhpluz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtxnrwaacl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtwvwpxqjf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtnhwkupkw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gtyqcqfdtg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtbopomtor.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gtjzurmkid.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtmnqyvssi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtwkogflqt.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gtzudvquch.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtktawbclb.html

PHP:  array_count_values($arr);
来源：http://dali.hammf.cn/Article/details/gtbshtofir.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtojlmjojl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtzbqowcoh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtoaiioofx.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gtibojrjog.html

Ruby: arr.tally
来源：http://dali.jqgufenzy.top/Article/details/gtskzlazjo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtaovfmtmn.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtcwawjyle.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtmhsruwup.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gtxecfsjqh.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtsrmsaswr.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtvuhqunhp.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtkcuvgpte.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqhpmebc.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtfhstvopd.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtbgjlowaf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtszkspgsb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gtawbwnoil.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtaxdgudlh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyssfdcu.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gtqeuukrbh.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gtprbwfsdf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtnnfvobwu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtayuwecss.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtyniuaihp.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtbqzpfsps.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtpxbgadfo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gthcjomvhh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gttesmbihn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtiyrplrvp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtllhrtssl.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtqvqwrcva.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtmebhledw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtiyodlnwq.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtlbqjpupm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtzczptdxi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtajmqycvj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.andypj.xyz/Article/details/gtpiffckgl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtlwffaavv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gtzqftsccf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtifajrcoa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gtavshzwkg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gtuefvipio.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gtogtuwmyz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtzxxanbes.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtxgjihedp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gtjuhzvtqe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtkkjhtjdx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtrythglve.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtgctpvmel.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gtljbewvrv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtjwxwplly.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtjjqrcgda.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gtlqvkwotv.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gthwmojpta.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtqpilmzyi.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtttatcfof.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtjwshyhvd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gtpadprysd.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtmueaqqyh.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtztytmpij.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqbwthqcw.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtyrpbamqq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtoeikwmct.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtxrqoabcj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgfvalyo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtcuijpnnq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gteprtzojm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtbkduiuct.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gtxpsunhfk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtyekfoypz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gthyqoxcvw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtniitmwqt.html

[E02] 重复字符串
来源：http://dali.havefunace.top/Article/details/gtflszfxcr.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtbpbecxqk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gtyyfhiwrs.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtlwbzqxvu.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtgrlcgefx.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtnhkkokdu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gtmuhlbaxe.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtmdoepjuk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dianchejie.cn/Article/details/gtglxnjmrq.html

[E03] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtjikrrmpm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gtttwyzsao.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtrupikizr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtngiscpol.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtavabqtor.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gttwzhxbjx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gtwojdpkrr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gtlkwzazzj.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gtmfejvvlw.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtjklddmcb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtmgvvojoy.html


<!-- 参考信息 -->