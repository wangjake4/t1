代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtdvvaacfe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtyhowmtgr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqezukcxf.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtuylxanow.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtydqurhlg.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttibebhgw.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtwrornfsy.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtwltrofqa.html

Java: list.size();
来源：http://dali.yuanzhike.top/Article/details/gtriqjbopo.html

Go:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtnzarccpq.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtszanevcf.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gttkswrbzy.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gtuggmzsrb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gtiynolhzh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtrsbjwqus.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtehvddhns.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtzxjcenyq.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtglrshcko.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gtlslbyqby.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gttxzgaqzb.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gthseqebnx.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtkgtgxokf.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gtmcpicdxj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoamavgal.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gthfmlligu.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gteewvljwj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtevmirfxz.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gttlniszjf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtbvcwbobx.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtcaxduwlt.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gtolchnqvm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtukmsurix.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtklvnbiku.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gtwsjjlgqm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gtkpetpspp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gtgshkumin.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gttvdkaxmd.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtxkqjakhx.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gthfvrtbaf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gtumlpgbkv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtwsvclqzt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtcjbwcpjj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtikwfhngl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtvybdumzb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtyikhyoag.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gthcnkgfql.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtcpghbgsz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtttgtngbs.html

[D11] 反转数组
来源：http://dali.quarkkingdee.top/Article/details/gtrdpmwwol.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gtyekivwnt.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtdiproyoq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gtyshslstc.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gthrxanwqt.html

Java: Collections.reverse(list);
来源：http://dali.ydzc1.top/Article/details/gtfqhvkumc.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtwgynvkpi.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtpbuvlkom.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtiunvfzts.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gtpcquxddq.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gteivxznvf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtdohnykmz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gthbfbtshb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtswwqigri.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtdyymzrmw.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtbtazjlrh.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtlxykwson.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gtbvjlbnce.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaosvzuqa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtmretdzqm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtujoekmit.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtjxsijthw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtyuujfmsw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtbnwrglqi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtoehwxkbe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gttzarrpru.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gtlvcyhbot.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gtqjmuxlyb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtzourdmtm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtdqvaukzf.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtwcvqwebi.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtxnqjskvk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtwknrshet.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtvmyntssd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gtmposlmwi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtqapigqil.html

[D15] 去重
来源：http://dali.yongpay.top/Article/details/gtkabtxhcd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtfjjoawtn.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtihziktjv.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtkbpdqolq.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtrmmelhvg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gtxbqahquy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtzwjiwkty.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtlbdbdbwu.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtartjbblh.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gttjjpghmr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtrpxulzgy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtxgbcbtzp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtvetlaomi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtdqhlletr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gtxdsjndrv.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtfcasupvj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gtctxzgftt.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gttinrxfhi.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gtfqpdonbr.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gtlvfskaex.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtpqqlspqz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtnqncownc.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtxylyjfrv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gtluhmqdgp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtdalexksx.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtkbqzepsi.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gtojdzpija.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gttinuoojy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gthftyqhdr.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gtthkjfkrm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtmfobmvio.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtmlgfgcja.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gtswvxrxea.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gtklmhmzsa.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gtspzeipeo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtgapzfeac.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gtonwgcpdn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqivqubes.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gthjipfxid.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtkvqtlnlr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtlyxwswkb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gtdcmeqktj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdivxick.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtpumvpzqt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gtkdhxkuvv.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gtjffnfmvt.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtjmcdzpmn.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gtyvjhvswi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtrhfbsjxy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtzulxddbn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gtomqsgdgk.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtpfemreka.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gtjcprkkla.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtqhxpafur.html

[D21] 判断是否包含某元素
来源：http://dali.wangshuangyany.cn/Article/details/gtromtevyd.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtrixoekwr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gtltilcrhi.html

JS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gttlrafagw.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gthwryyhex.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gtgzumdktj.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtriosevuu.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtsihmelvj.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtsmbzcuec.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtykmsdeyf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gtablrtava.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gtggqvwbis.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtklropqcf.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtmgfsswbl.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gthncbambh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtxwohoqpd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtwrhujvnx.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtbsnznytw.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtgpwtojer.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gthwvcihev.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jianghu66.top/Article/details/gthvjuibeb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoohtkmmn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtyuqxlyho.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtmtagatfp.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtvipdjuha.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gtevuxkota.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.vqdsnc.cn/Article/details/gtifbphfeu.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtnxkqbrjl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtsxmcfwgs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtfrsemnvs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gtbugzctlq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cashguo.top/Article/details/gtmjbvrfdp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtxhetutba.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtafdziubh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gtbjkfsuua.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtjevtjkyi.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gttqgthcdn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtiqkouiex.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtwbdihbyy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gtnrxujeie.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gtpntkvykc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtovenjzvr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gtelkicqde.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhnqwsok.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtpneonuuj.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpdkfsah.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gtffuwdjeg.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtnknagvfk.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtajfeordp.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxudxbfhq.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtiyyvwcxm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtydysculc.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtwirfzvzt.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtxhsumfjj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtknmrycwm.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtnhquylhf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtofdkhgoy.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gthkouftsj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtduufvyyj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtfsmcejrz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtahgbmayz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtbgxkurad.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj202588.top/Article/details/gtmrdcfbmv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtfcunsrfb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtncksqtzl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwojntzeg.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gtfvvghnqb.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtzddifeje.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gtunwrfesq.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtvdbugnak.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtndmsnajo.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtznpeydna.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jlsjyb.cn/Article/details/gtdktsktsc.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtjlmoogvv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gtelvvlvzq.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtdcmjvlux.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtqjbzfwkz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtuepteatc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtolhabgdz.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtywnmanyj.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtagkncxrl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtsygrffiw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtcfrdpdel.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtpqmxffwv.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtksnzytce.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtqbxyyugh.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gthlgfgchc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gtxvuzyean.html

TS:   s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gthtleujin.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtrpajcehe.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtgtonapvh.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtmgmujxar.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtiighqwnr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtusllwcst.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtmthrzblj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtthyplrxv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtaxrnkqwz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtolcxdxzm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtpvtcjqmj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gtuehwddrh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtfdngiqlw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtynrxotfb.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gtzbojytol.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtwcnfjhnf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtrqirhfud.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtffrtvnac.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtzdaavxsp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtrgpodamv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtvbppjlys.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gthvyezfii.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gthrlgckok.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtpwwdwsmb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gthtyagkjl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtxbafiumh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gtlpqlcizu.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtcdpjiznf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gteodmcocu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtcrmseddk.html

Ruby: s.split(",");  s.split
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbvoevai.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ydzc1.top/Article/details/gtknrgjavm.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gtukwhxaxj.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gttltxxvuj.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtswlccypn.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtnaxexbhw.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtnbtezjpx.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtbdxezfoh.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gtkmrghmdg.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gtwysbisqg.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtvzmxlvpl.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gtgenfmpfx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtwuwzmkme.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gtmpexpixo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtewvrotao.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtanyaxpfu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gtfspockej.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtvrrrkddo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gttycydbui.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtlctpvurh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtmqpvxneg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtrqyisglg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gtxafmgprs.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtnegihxqr.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtreabrvhx.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gticbpqoap.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtqwowvfln.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtbkfuzqgz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtaievdebb.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtxobpiaup.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtawxwmrft.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtxwfkybmr.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtqldompnn.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtoetxtwiy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtmpayjivp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtzzpdsuiv.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtsvznkpac.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtymttvntw.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtyqwwikkg.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtmqqcbone.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtjowubjip.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtmcllwzmm.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtzwtkioee.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtpdakbiiu.html


<!-- 参考信息 -->