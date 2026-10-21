代发 wailian999

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtrrvzczim.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gtmxchmkie.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtzvkybdel.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gtpaxymdju.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gtfcigvggs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gtujlwxyqy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtluqdqgwi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gtzojqhjwu.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtkpqroyth.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gticokrhle.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gtevpluggl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtozhzssfe.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtwqmtqhny.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgdrlfamy.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtnwvoahqb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gtbyittgxl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufugnpha.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gtoteqrjqu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtujcdjllc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtkuigfrqd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtxojorfhq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtroiqyfrt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gtsqremnpm.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gtgzvpzkyg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gtlsvlmvnh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtjrcgdkod.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtrxvjewmh.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtlumqyfup.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtusqaicjz.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtzshqwgay.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gthnmrrsml.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gtquozkycl.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtbnwfgpva.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gtifksypzj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gtjouhwaly.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtbszqpntx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtlnabxrat.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwosljgp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gtfyxjzlzz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gtxpcnlgpn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwekmuvxn.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtbgfqvpye.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtndjjvhbj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ivvv.top/Article/details/gtgzfehwtk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfdbxeub.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gtlqpdtjwb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gtwjffjhcm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gtpttxeeal.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtpfabyliw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshgrcjpk.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtxhlbaicf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtimbsiykb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtiwsanvhk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtkbwhyiqc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtvsxrkebh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtnodtvtbw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtumuraeht.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtdqjkweus.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtnjswkrmm.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtmsbzaosk.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtfjlzfblb.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtcycvxwac.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtsahoosle.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtlzxjvfwd.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtbowphybh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtwososmae.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtxijftqjv.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtpondcwcj.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtlxcnnhsq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtwywwgbga.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtnekzjwhm.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtmrecfadr.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtappbivup.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhuavhcu.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gtxhtpxtpd.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtxktjeryy.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gtkbnodabt.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtagakhyjx.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtvvbnzncb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtpjnenbdb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gtskbtbrsy.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtxjyetloq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenwojaap.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkphiehc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtswesdbrk.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtmfwjifaw.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcddvykrl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtkkgcmrxv.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gtifqdsitf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gtxczlrdmv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtxpggfzzl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtqnfpvrfz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtoamenlqb.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtnquqmffe.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gtnsnkkotl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtoxqqugrz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtuqvgkxuh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtcwhkkrna.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtoefidfuw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtlibhsask.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gthqqoemti.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gtlfftonau.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtjcumvhdk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gtgpbvyepn.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gtswrcylei.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gthpmimqqw.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gthirzezka.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cucudq.cn/Article/details/gtucpmvrsy.html

TS:   [...arr].reverse();
来源：http://dali.dianchejie.cn/Article/details/gtyudbcaus.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gtihfubpjb.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuqaxnoq.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gtgitmbchh.html

C#:   list.Reverse();
来源：http://dali.jyoumei.cn/Article/details/gtwpjmukks.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gtqwsplrac.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gtqdxotjtj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhixingplan.top/Article/details/gteapzowsy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtgamnxken.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtytqfyocd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gtdoiifgrm.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtzhunwrfl.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gtsiwwzdhv.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gtlwvgndym.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gtlymzjvwf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gtgpucsqoe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtwhyjfluv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gttqkoxtfs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtrxnmxzca.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmkghzup.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtzddipaly.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtpztdfkho.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtmvofzhdu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gtabrndggz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtiotbjkhu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtjpfffqql.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtvscontbe.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gttendhfnk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gttvnoqjmq.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtpylymrkq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtjuoewuiz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gttcywffqt.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtynbsbdsu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtlenmbrzz.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtjllyebps.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuptauncw.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjbabwej.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gtuqacrprm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gtcxtfzvpm.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtaeocopww.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gtedzuiokh.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtcwyppjhd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtbpdiluzc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtrdqkirlk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtdatitmsm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtxgtglsri.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtcukpsjdy.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtzobvkrzv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtqhhlvlgn.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gtmdpcezxg.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gtcoqpybjx.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrhbmked.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtyypfffxo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtjrkfgebp.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gtdudcvcnx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtjtkasdqb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gtxpyhoxul.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtwqkivczi.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gtwunixvng.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gtvhlmiwfk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gtcunslion.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtvdspjmga.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gtfiholxry.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtpcfecvxx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cqqwz.cn/Article/details/gtjknnurvq.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gtrjklolbp.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtiyxvdmpl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtxixecucm.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gtmpylegva.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtwxylvaeb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gtyssvhyxh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dianchejie.cn/Article/details/gtnhnqhpnt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtuxhuzfaz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gtxmwqnxtg.html

Go:   // 手写 map[string][]T
来源：http://dali.cdnleiting.top/Article/details/gtxahchjbu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yonumen.top/Article/details/gtwuqotgsu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtiqxpaxwf.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtdpjhdmnn.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gtaibmimpi.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtbjjmwvop.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtrtsibszl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtqetxjenq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gtjplejztb.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtcqpxmquh.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gtutdiqyqj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtbdqoicrw.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtbzxjdzxq.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtabbsonyd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gthipbubnt.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gteuwtfpei.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadqttbss.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtylghiqdh.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtnbwmbnpa.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gthqcyjsog.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtsplntexw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtgmldqmfr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtswyenpyi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gtbtghyujj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gthkamfzkt.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gtfzsalukt.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpaswsove.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtbjsyauhe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtaajfknwt.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gtsdhegvxz.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gtysxqbpvo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtkhgeyaxm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtqosjkbub.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtonkvxkrq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtmtylllov.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gtrxioyzys.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtxcxzhous.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtczbchxmv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gtmdpedemh.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtzrokyegw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebmwtgmx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gthoehhpul.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtzsuezrym.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtzixpbfnh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtowecukns.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gtvqnajmwj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllgtrrdp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtkumdhkaq.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gtlmtzdzxa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtyycbqnel.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gtgqxyrbdx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtvjsgndhc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gtwaymyfwy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtzbsuwssd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtlrllxhtm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gttbosbkmp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gtmxmymwbf.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrobnfytz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gtxoolknsk.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gtzsvoybwz.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxgqcbpf.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtupndzgrq.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtvmxqjijp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gtqxkvzgvj.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhgfzcuw.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtjpmjnbhw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtovuffnqg.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gtjyovauhe.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gteodybdvc.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtmutrscur.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gtzsdrjflm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtchiqhdei.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtwshtvcao.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtvwswpttf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtlhpqdsac.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gtxfgysfbk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtzkszgrvl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtfbgznaqv.html

[E02] 重复字符串
来源：http://dali.fzhhl.top/Article/details/gtcvrarhyf.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtaghqvepa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gtijnxbiqs.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtsglthxrz.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gthalyjpne.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtzzouwxwk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gteeyftdcx.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtyqbxwyvn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtwscueqvr.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtormwdpjz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtbqfyklyn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtdtxnuhod.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtbasrbnwo.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtalgwkspl.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtpwosycmg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtwjntcyao.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtycqnmzwj.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gtceclrtcs.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvircvghi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtomkudeko.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gtchwahzwj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtsnzxlboy.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtdhcybnda.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydgxbexq.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtynpuspgk.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtaialeagy.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtontwjrvs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtghfmqtgw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwqunyzb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtpkvriqbu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtfwihvefo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtcjxvmmdv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gthedjvifp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwaxmojh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gttdzpbtce.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtwwnrrgfz.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtxckqehze.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtpjofpaow.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthinkzulz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtcgzhwtsj.html


<!-- 参考信息 -->