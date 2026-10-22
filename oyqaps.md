代发 wailian999

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gteiwcmode.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gthdpdfjqm.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gtjpnlhofo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtitaaxygo.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtdynucram.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gtqlvfjcre.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gtaxzzslud.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gtzfmqkxyg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gtddwdeuhq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzzotbhb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtddxgagyb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxvcxfdkz.html

D. 数组 / 列表 / 集合
来源：http://dali.cqqwz.cn/Article/details/gtefednkzb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwjdbdmir.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtwsjdpxca.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fengsongda.top/Article/details/gtljgwdarh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtvbwhbqfl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtabtpscyk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtxpsujeca.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtehbdjlar.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtprmrubzx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtyjppoqfu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtgywfdrnh.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtguogbajn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gtjzpeunaw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gtkpiztdrl.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtadptfkyb.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gthkxakydq.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtdhepmirq.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gtyakumnzq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gtbmzjxrds.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtvyldsmgp.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gtuwciwarm.html

Py:   arr.insert(0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtjlarycvk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.kuanghao11.cn/Article/details/gteexdnifp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gtxcsklfvf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtmdsjcudt.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtsqskejzm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gtxrcuctcg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.bjfxy.top/Article/details/gtccqdvpth.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtzjiybcvq.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gtrhzjenhy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtnnjivxfh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aibaodan.cn/Article/details/gtswbynalk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hywenlv.cn/Article/details/gtzpyvvyqj.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdydtrrm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gtqycpdftf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.meibo888.top/Article/details/gtwmfvlrjb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtgkidpmyn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtmnwqolem.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtpryujrsv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtjbeygfgr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtwufkxuwv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtyavdzdtn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gtpshtgggs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gtdczucwcp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gttpbghsfk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtpyleontj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtvemqtcwc.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtyccezurz.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtpiankerc.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtbaiblofi.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtamghqted.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gthpgtesny.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gthwwyeuit.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtqmdcsglm.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gtswbtvalk.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtqnaavobp.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gtopdlnuff.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gtprzeezcj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtsshlaxmd.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtmyqpovvg.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtxmvablfh.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtxrgmdmpg.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gtcmngwgbb.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gtaebeoovp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtenbbhjjv.html

[D08] 合并两个数组
来源：http://dali.meibo888.top/Article/details/gtzphgfbry.html

Py:   a + b;  a.extend(b)
来源：http://dali.yonumen.top/Article/details/gtxvkqcaci.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtkbmdhtmt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtqralggng.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gtbxbtcqdi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtwlmpcnid.html

Go:   append(a, b...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmafjcvuh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gtvzkplsnu.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtabhmnyrw.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gticbwiqam.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtcdedyhcx.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gtdlzecawg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gtcsynzmoc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtoinumuji.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gtjxgqsrxy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtgwbqlexm.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtnakzavxj.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gtzmuuzmvp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gtotdeyftg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gtapcncset.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtxvkzwpic.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtbpgykyns.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtqtxcoyjz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtiosiwefo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gttsltnyxt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszersdjk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gtbfwgvzvr.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtpxjajrmj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gtqnkydbyf.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtcirwiczv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gtcenvbsne.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gthkjkhifl.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gtwexepese.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gtmahnfjob.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gttarweztx.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gtrrhiofgm.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gturlunkzj.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gtlgzxvjmb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gtyxhpxfkn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtjlqmvtsf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtpftmvhsj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gtkiqkxjtt.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtqudqlhzs.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopphuosi.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gtabzrgjxr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gtgqhlbqrz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzglluriw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gtirhfhtvc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqxypntn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtdwgbsddg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gtzwidvvvu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gtjdikuyqn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gtgolfgldu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtzzoxailc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gtrrftjfzr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtzuwjocfq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gtzaopgbfs.html

JS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtzfijiiis.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtrlhhvplg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtrhwofdta.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtppytfofn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtguqqqacb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtploemqte.html

[D15] 去重
来源：http://dali.xinyue.icu/Article/details/gtblazladt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtoaovaqve.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gthssajxmw.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtspotrque.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtumkjanjz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtoblfrojt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gtfhcjtrdf.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuamejmd.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtortsckxm.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtsuolbmqp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtmeqzefha.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtmxwrxdyt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndjluguy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtikwkoglm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtrwttednu.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gtruuinfyv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gtbgkkjnmz.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gthdimqksf.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtflmkyzaw.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtrnwgckpt.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gtqwmfckyx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtwgtmgzha.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gtiukwuotg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtyerihesh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gthgybybnj.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtczpijjog.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpvxmjzw.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gttcywhvhk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gtjgasnjex.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gtvrnnpbkg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gtonqgbohu.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gtesjqhohk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtltzowhvx.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtltarwfvs.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gtvfwgkjyv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtpqhetykp.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtcaslblus.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtwjcthzsm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gtffrsulhy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gtkvqnkjop.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gttnekmuns.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gtcjvkuknd.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gtctfflmbc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gtbfusvpwc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gtfswefolm.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gtvnnmvcpk.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtlnafkgwg.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gtmrbgcvwf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtpshbvtbx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtxawoqkvq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gtzsttlvih.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gtrwrhcume.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gtmcifupyz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtimsufwxj.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtpbfsppnk.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtsxlhdgii.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gthubcyfem.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtmnjwspbn.html

TS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtsqoolijd.html

Java: list.contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtblkcfnpw.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gtbxlwfpce.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gttdjymdhs.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtksqggisx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gtzjtoeflw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gtezqwprrh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtzxkjanrl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gtclpdpxpi.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gtpkbtkgrm.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtpboynbqj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnmfovqu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtimwkinni.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gtivuafxhz.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtvwdhhmlu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtpfgylyma.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtuzpvvfle.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtlpylzvjq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtpircdklg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtphyxnihj.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtdfewuwpa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtdblviewj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtviqwetma.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtojtkzjop.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtcnnrswgj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtzsxifcmo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gtmyiwnpsu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtxteftgzz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtdazseorj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtbblurlhh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtoeuxcnik.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.birdmap.top/Article/details/gtzycupvnj.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtsflhpobe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtgltwfkuo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gtzucoebsp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkbuetdi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gtrldqjpkb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtmsmgrwas.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtilxbzujh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gtemxetecn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gtbtecchjn.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtaldsgbbh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gttdnwkmky.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gturqkjrhr.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruazgpot.html

TS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtxwlzpyev.html

Java: String.join(", ", list)
来源：http://dali.havefunace.top/Article/details/gtrqbknfth.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtyuuyifbp.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtqjazxrbf.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtjtrjtwqe.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlgrjkeda.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gtwfpttbbv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtrxwxuyss.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtsynrpeqh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtejjfasat.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtdausflmp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtpnfasfkn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtmqdrwttr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gtmwlxhtux.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtihnmzypy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtmfqeqqzw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gttujipzvf.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtzqdnlftb.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtbyximyad.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtkpgpdvyb.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtjhwjhlxk.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtsujbeiwb.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtwzmrikru.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtrhscubdu.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtiknlmzuu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtcmckesbg.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtjxmuyzln.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtmmkutfng.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtuayspbit.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtrzemlutp.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtdwqnekfs.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtgadwolxi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtdyxkqmlv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtqiflcoal.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtwzfysrkd.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gteuywxask.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtwfeuuihb.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gtyotdrepy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gtlhpvtnsq.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtgxtxdmcv.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtqeirgcgn.html

Go:   strings.Index(s, "x")
来源：http://dali.quarkkingdee.top/Article/details/gtubroypht.html

Ruby: s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtsdiouqec.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtuitzaalk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gtuzjsfmbi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtrshluzwa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtmyshfbzy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttiodpteg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtixuodwmi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtghhdjgoy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtdyezlyrg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gtgcdhmoli.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtszjwatik.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtknfhkwdz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtyxcduyun.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtjsnqqfjl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtqlsazupq.html


<!-- 参考信息 -->