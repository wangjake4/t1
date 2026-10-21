代发 wailian999

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtvfwhsxae.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gtrumyeisx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gttecsaesj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gtpoitmwvg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gtlxjgvcbk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsouwtis.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzjujwkg.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gteabmuwyu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtmgakfpbd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gtcbqcfuyw.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtiapvxamk.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtmtynpygd.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gtennbfwhe.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gtoegbtomz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtpkudvrxn.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtdlqogtcf.html

[D03] 在指定位置插入元素
来源：http://dali.tian-w.cn/Article/details/gthipiowwr.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gtwfwxxceb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtaimlerxq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gtafhfphtm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtugmpldko.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtsyjlwlfh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtwdcxkyfv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tianlin.xyz/Article/details/gtkdqiujqd.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtgztqzijj.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtkgnkohsa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gtdciirpbx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gtsagudxye.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zycfv.cn/Article/details/gtfyariepy.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtoedjnmjm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtzpknpnrs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtaqmvnpsz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gtefbhdyti.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gtywvnljmr.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtgohxwxoy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gttckotbpf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtdztksgkx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtymihlfoq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtvggbblrg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtfepymqzv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtjbnlewah.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtcjnnugsg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gticmyizte.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtnidcttwo.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtnupagyxz.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtvhhveizo.html

JS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtistppgej.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtazohvqoc.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtdelngwei.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtvulzoxsk.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtgupanrdr.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gtoewrmzrb.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gtzzpoilgc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gtdmjocdnh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtevnsuzyb.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gthndgfjfs.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtsgpbrjxv.html

Java: list.subList(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtpquiejmz.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtwectddyj.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtqgcyqgyb.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gtretodnna.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gttrrzzyzl.html

Py:   a + b;  a.extend(b)
来源：http://dali.xziqi.cn/Article/details/gtsxgptrfm.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gtgndtccof.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtrpjsfmtd.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gtbkcwaxwi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjeiuzgr.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gtimsuyavn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtdprpztwd.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtlgeyqqlk.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtrmhiasxs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtuefvpzqh.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtsbrdeule.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gtxqanpfhp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gttutggslo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gtjophslwg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtrlzxvqky.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtvhujzvpu.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gthqqchouw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gtojkzbuxh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cashguo.top/Article/details/gthyzvywsw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtlpjzebtz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtnhwkbhek.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtizcpnlnj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gtijrkwmat.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gtzxvdsglw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gttgjjtpow.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtxgjhirtz.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gtvugtnfqn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gtbgerztft.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gtifbltzov.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gtzycojfpp.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtlkzpebrm.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtvcnvxnyl.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtccikfist.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtgahmorlg.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtgtkomkoe.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtldtckujv.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtvmkfmnnp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufwwkwpp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkpyobnob.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtiqaoxcfj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gthxcgisst.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtzduqankm.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gtwsaaebup.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtisfcjpqf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gtsjmkpeju.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gtemytmmat.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtkfzhqtfc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gthimhiffz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gterbzeaal.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gtkzbsyfaz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sysykeji.top/Article/details/gthspkdpjm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlswcyiw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtiquswmam.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gtecixcfmb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtvuyjulyw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtdaqngcxj.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtnugfrsiu.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtmrflocdd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtdfdgdbsd.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtgxipqsty.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gttkvnrquj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gtnqjtghvp.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtghjtgmxn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtqhmqrrcb.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gtnglfvihc.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtbkvglgdy.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtprkzwqho.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtuzuzpebl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gtlfjhgasp.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtyknjjull.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtfbkylbhb.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtrwshxyyp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtfzwbqjem.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvptehrk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtqvfmlubb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtxjamknvn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtlbytsvtb.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gtlbyyfaaj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtkohgopiq.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gtveqvoqmo.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gtltmxoqvo.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtuicmbngc.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gtcgmgmuiu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrzeifuz.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gtlszfvzkv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gthuroqluf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtvkxancdw.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtqzdsotrh.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlhxgahm.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gtqrrnjdak.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gtkyeizobe.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtozccrntd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gtvcfvoiub.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gtrtamdvuc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gtczkluigg.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gtqyfujdep.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gtmqdtxiht.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gtzbavyixy.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtcjujbqhx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtpftclmsm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtoxweaafl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gtymubnezp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gteradtqii.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gtvgmkdgdv.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gtdctpcuvk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsppemkht.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gtdxwxnsnu.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gtpvdfbpfh.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtdfvvdrau.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gtszraijeb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdloxaey.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtywmkyekt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gtnzdaijrd.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtbnvynczz.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gthxvdywoo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gthzrmzlyj.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gttgwjgtxh.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gtmrplxzys.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gtidpksjrg.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtrxwopgfm.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcmktynd.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtslrwibdh.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gtdbmxpcou.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gtsgvbkjxq.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtdvyfutha.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gtdpewgqxv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtvwapcecb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gtllkqxief.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtstgydkgx.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvfuiuaz.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtcicnacoh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gtniiuinzc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtwhamgkpf.html

C#:   new List<int>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtpfldmooj.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtbvipvljg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtslmbmprz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtybgfitub.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtmnlhtfzi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtrqfrrtzv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtttfkufce.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtbdzdtgdb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gtyrgaszpg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gtgkqnukij.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtlpacoowb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtyqjamrfe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtnmflzisf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gttdzjmbop.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtntklmngk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtpkgjmwzs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gtidkjrexj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtjukamqke.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtsrizczny.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gtidjryvfm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gtjfeeaejy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gtkbzzwbme.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gtbdpzdjbz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gtnswmaodn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gttfzfcmre.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gtxqpyttez.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cashguo.top/Article/details/gtfjrcqzck.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtelicnubb.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gtcixryqzm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtpvqjzwab.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gtjiigycms.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtpuybpphv.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtxtdqejfn.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtnxnqhjdu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtcxiohvyt.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtabahbbbg.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtpklcgnid.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gterekbrne.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtysioprwm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqwszkelk.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtgljatmmh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gthhprczmy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtegyacttc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtiberuokb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtbsualktu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gtivmnehic.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtzgshwqhr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gtkfqecgye.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtupygqsne.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtfskwuanp.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gthoocubio.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gtoilahgkw.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtauepmrwl.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtygorsdsk.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtfcoekhkl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpmnsbfr.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtfulhqdxk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtdafognjv.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtnchjjave.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdekwpjw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtugzwrlah.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gthyslphgf.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtsslzkgxm.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtncyfmxfl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gttalzvpwg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gtgqgmahcn.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gtxefnkejv.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtmbsfipsk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtqvzaapwq.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gtqpotadfu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtzpgifjjj.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtovdyvofk.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtikejwxjd.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gtawiirebc.html

Ruby: s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtmuofevha.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtupwmxbsm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gtztlmgqia.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gtybnhqltj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtjggnmllg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgstxcyqz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gtxcmkquiy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtquzjylos.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sufxvd.cn/Article/details/gtuqevjvzj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gtkdrxmbpf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtmtrbjnbu.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gtmrmgvoih.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtpwhhjtyj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtomhaywsi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtwlxmlqlc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtlxiazxbv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtbnfqvjjm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtqmpaqdny.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258.top/Article/details/gtyjuosoyh.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtyfwapzuo.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtoaitikwt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gtwjuqnkrs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gthsscddyy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtvlpqfeab.html

TS:   s.split(",")
来源：http://dali.pycfn.com/Article/details/gtcywmmpff.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gtbmwsntxg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gtnedofazb.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gthfjxfpoj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.andypj.xyz/Article/details/gtnilcmcia.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvlsuhsa.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtcznfpktg.html


<!-- 参考信息 -->