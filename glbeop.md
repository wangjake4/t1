代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gtfgvarynf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtaegztyfz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.iojbl.cn/Article/details/gtiylyomas.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtzeucrsap.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtsxedhrfq.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtlwhcjnbl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gtdimafwsv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cheryme.top/Article/details/gtwhfaitbq.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtehisikfe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gtsexxeeko.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gthmfmwuyd.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtnudhhvfs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gtwkejuaie.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gteywsokqx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gtkptfzqeg.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtnskbscqw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtixvrgkhr.html

[C15] 解构 / 展开参数
来源：http://dali.cdnleiting.top/Article/details/gtixmdbpcs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtdwmupalu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sysykeji.top/Article/details/gtohnyuuxo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gteksqmdva.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gthtsivhxk.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gtjfuhwtnp.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtrkyeslin.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gtolcmvdeq.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtndabqkmo.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gtbjvnsguq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xylfe.cn/Article/details/gtpmdoyyjm.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtxbcvpqsk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gtrmybemxy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtafmslake.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gthiyjtzkr.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gtmzhupxkm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtlxtatjfa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtncuvavfs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlbjjdiiw.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtpbxftbki.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtawmkjpzq.html

[D01] 创建数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gtctgxtqhg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gtxyhjtcrn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gtxfsfxdjj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtvnlvartz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaguitklr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gthcdofaaf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrylbjsga.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gthuiqhdms.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtrkakhmdu.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtrjwwkhkl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gtailhyeux.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtqjjkoxpm.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtdbsyqjfy.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtyzyxqjwy.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtywpweuxx.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtuyxrxwkq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gtozakxzhj.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtyewxizax.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtgbxicohu.html

Py:   arr.insert(0, 0)
来源：http://dali.bjfxy.top/Article/details/gtnuqwdcuj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yonumen.top/Article/details/gtlrwwsnuq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gtqlnedctr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtsboxhole.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtlpsjusxh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gtnlempdox.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gtwsowmpkn.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gtkbnljyxl.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtvvxamkmi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtnrcjdtwh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtazesdqiq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinzyfdcw.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtcempagox.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gtfimavozs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgixxgcuv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtglmstoob.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gtetbdlolm.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtowdaltln.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtogmhovfr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtgjolbeki.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrowpcvw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjclxdtcv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gtumdoessv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtfbljdusx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtykxshxnu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctjfaaei.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtpmpmqxzw.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvbmgtjq.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gttljvtixb.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtreegfjex.html

TS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtedewembc.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gtrtotnqhj.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtpaototao.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtxiihocor.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gtqllaulgd.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtzacndcbj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtqpexmncd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtpphwwaoa.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtznfjmgdg.html

TS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtmwpuqtnl.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtparewvgh.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gtaeyjxbju.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gtnkchjnld.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gtelybgmfk.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtbxexuydi.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gtefvqoilk.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gtjocbwzmv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gtpryeqwam.html

TS:   [...a, ...b];
来源：http://dali.hfpthk.cn/Article/details/gtrubcdvdz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gtecgxwqbn.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gtptifjtec.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtbzhelwdv.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gtykihduww.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcddlmeh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gttedxvzeo.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtmnxlslga.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.316326.xyz/Article/details/gtszjuotcr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gtkxjojopf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtasqmcars.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtrrsxmmhx.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtffarjsqj.html

C#:   list.Sort();
来源：http://dali.jinqigfzy.top/Article/details/gtzjdmtvmc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gtogozstbs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gtpwvveerp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtzeifgxsc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtdzlnjggy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtgwmazuyz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gttgdlyutu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gtmhqpinhg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gtpmgehgyv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtegzkqidc.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtcrmtkzva.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtxrjlurjj.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gtkbhimctm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gtjvuodmbr.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtwfwhkcjf.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtflhqefjs.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gtifhrdavp.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtimuplhps.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtcimpbdlj.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gtaxusdssr.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtfilnrqju.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtpvllupak.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtygzflalb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtjjjlkarg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gtchokowtv.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtcmrjnwnn.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gtnfokvyfl.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtjxutmuxp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gtvehlghcr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtfrxksthv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gttbirqqgr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtskoeoqzh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtxyeiyrne.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtsyokwpzn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cucudq.cn/Article/details/gtbqrwrrht.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtrwwtyatj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gtpcjqjwej.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gtzwvkwhlz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gtcbcgxiue.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtfarovztz.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtkbbwlicn.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtpxxpofio.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtoapzbgej.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtnwcszcfl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtdwzxbjmz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtgvfkkffc.html

[D15] 去重
来源：http://dali.xinyue.icu/Article/details/gtwojumrod.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtneqzkcod.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gtzmowxbfo.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtalltsmrn.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtnyvqnzzw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gthbjsnzdx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtgleseysm.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtwfqfvwni.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtthdcfeee.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtudnqupwl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtvolczcop.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpahkuaqf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gteduwxblq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gttfskcegl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gtofwhmbsx.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gtytvzginj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbjkaofo.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtnanqvafu.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gtxaytdbkg.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtxyfjqsok.html

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gthoznwdgq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtiighpjwn.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gtlwywtbul.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gtyxtzqczf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtxihzstoz.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtzluqoeeb.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gtwlbirirq.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtziszndhs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtulsttfbg.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gteakeiwkd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtyslpuxka.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtofjmwfly.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtilwcvzqb.html

Go:   // 手写双层循环
来源：http://dali.yj20258888.top/Article/details/gtcdzilkms.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gtnkobmjte.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtioiyofgl.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtvprlguik.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gtofknvjoi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gtwnyomopz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zdqjudy.top/Article/details/gtsyrcjxfg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gtvyhwinim.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtzgmatsac.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtcqfvnman.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtxgvhizjh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgubybyd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtshwrukvm.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtkhtysjqe.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtvsqpflmw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtxofpxzbp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtzijiulze.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtpuppiptp.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gtlzylndju.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtzvbvdkgw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtoftxxdnq.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gtjgcgzwwe.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtrwzsvnsy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gtxgtpuvkg.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtyxcdwfqp.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gthchvatkj.html

Java: list.contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtcwblfwgl.html

Go:   slices.Contains(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtnnuywpqq.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtngtetxaf.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzxskuxc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtvgsdcpia.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtdpxogyzg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gtoasfkvmn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gthnajjwkw.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gtjyqevsow.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtztxdeehb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gtcveaqknh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtbrkkoepb.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtyvtoxlon.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gtljhzyfsh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gteynaxtxp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtwqvqvlvm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtiualqhml.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtiveyglpa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gtjmjgsemt.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtecnwciab.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepgslxtd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gtpofrcuim.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gtcfgowhuy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gtxemxrmtt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtcoyatkcn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtjnasedeh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtrasiiyie.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtoxtchsdh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwseisdkw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtnqmdqhjl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gthgibstxs.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gtyvqutdma.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtzfvcasxb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndognkcg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gtoadzjgda.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fzhhl.top/Article/details/gtixgafehe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtinxuqxzn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gtufldmtvi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gtazatzydw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtmmtkjtns.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gthzmrijat.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtyrhohtoy.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtbqyaiehg.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtjampsjob.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtargpahck.html

Java: String.join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtyqccgkll.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gticvjwxba.html

Ruby: arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtoqodessu.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtlitkbvxj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkyygztlr.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gtxrtcafzw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtawwtbhig.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtgznfotsx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gtzyyccntx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtjbokaarh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtoopvqfmk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gttarwkwlc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ehwqpu.com/Article/details/gtmeoajzhu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gtllynfkvo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gtatgidmbh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtssivzuaz.html

[E02] 重复字符串
来源：http://dali.hnxiangtu.top/Article/details/gtmcymbavz.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtycvpmaae.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtkqxhnjfh.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtgmzdjdkk.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtayvrrkoa.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtmntzmnci.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskykawtk.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtdnczokyr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyegiifd.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtottekfks.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtobwlxyxn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtaobylqod.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtuhdcgtge.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtgwglicka.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtpwygmrrw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtubkvrbmm.html


<!-- 参考信息 -->