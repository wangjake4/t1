代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtccahtpnd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtvvomvagr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtsztwggml.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtpwiqfamb.html

Py:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtwfnhrast.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gtxidwabuc.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gteagamjwc.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtuzawgoyi.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtghuuzfcn.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gthbceeuap.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsztxxrle.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gttrkpaxmq.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gtehscdkzy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtbrdbbhgw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gtjxhvcvor.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtxtypgqpe.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtdydrriki.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtiuingpan.html

Go:   arr[1:4]
来源：http://dali.zhaomingkeji.xyz/Article/details/gthopyzfqa.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gtenjowfyq.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gtkpogsgsr.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtzhapoxnd.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gtotfrdvfg.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gtknmwhkvx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gtbrjkgonv.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gtyndcberl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gtrkjowijl.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gtzcqinfhe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdiuvrjs.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtqrepatzz.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gtmfygrdnb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtrialqgrf.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtbwtwdvwt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtqajrsvab.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gtrjkaajcr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gtokqkvahn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtbfujnssr.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gteisbobqj.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtjuviixea.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtxzearftx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gttpmicxdv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtxkzzeqja.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtalteamgj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtdtjedwzg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtspbbekip.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gtelamqsqm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xylfe.cn/Article/details/gtdfolibqc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gtavluxrms.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtyzbebajp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gtbwblxdlj.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaqquryj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gtfisdbobm.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtlscpojdd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gttbqbetbd.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gtpfxnricp.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gthmkojxsb.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gtkfbhrwbv.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gteasstebu.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtjazsziqr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtvodfqlyz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtsyseyuea.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtwzmhxlrc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtgjhwlakz.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtcwoprvuk.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtkengtvox.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gtcsvwevng.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gtbeutrywu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gtjtabkvui.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtxpatidrv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtlrtsmqfp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtexjsiwdt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gtlhqcaalo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gtbrpiqskp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtwubimekp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtgfanlumz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gtconoeexm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gtgznrexdj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtlbodwbre.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtcldpjhcb.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqnarcbso.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gtfveyqspb.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtrpszyxcf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqxfbryc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gtqicymcbw.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtpdqxqsqm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtgcnfhutr.html

PHP:  array_unique($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtcqyxijqj.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gttrhhwjry.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtdqgwuijh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtqqjsxopa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtlpzqgjrd.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtcdkmfnci.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gtuquermqu.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gtphymspaw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtujltopgq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtsrgkepbr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtlmbrpely.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtxrqhbabx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gtqxrzpqew.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gthbhhiywt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtrhdzomrh.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gttysgntwi.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gthmvrighf.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtcxsgoxwh.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdffvtabp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtrkjysrlf.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gtpeniztzp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gttmkthbtb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtzkaxohdq.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gtlzxnaejd.html

C#:   list.Max();  list.Min()
来源：http://dali.gotoacloud.top/Article/details/gtpdpkzevc.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gtfztfwsrw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtrcvjvstq.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtqjddftpa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gtdwmojeqf.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gttxndfkxb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtymzxhidw.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gtvkfyqjiv.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gtlxutujwi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gtjodhtxsv.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gtdjdhgani.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtvtldrruf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gtmqusztih.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gtfxglvznc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtcauqheln.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtussxnmxc.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtjrmbjxqb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtusxnlfgr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtcntbfoja.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtubzugvmt.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gtzpbjzlth.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtzjipdnvi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtwuyovztd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gthymkskyt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtvjlkefwo.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gtxsxsglwy.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtniyneqeo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gtbwobwhxo.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhxewrrn.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtplokerjj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtmiqjjnfm.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtpcisbeje.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtfbxueyey.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gttdlqraip.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gteqlpnxwh.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtuvfvwjsf.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gttcdzqmin.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gtqjegixmr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtztzakuth.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gtdzezxuxg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gtjhabgqic.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gttbjjdwde.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gtlpsmoeqw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtbfnwjdoc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxuiozjw.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtnbaxxnql.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gtozaoubig.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gtzjsjnthn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtnsjtyxsu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gthdxhlmjt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtadzjnihl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtlesczvuh.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtqetjanun.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gtuvlaexfc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtwjzshdbr.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtwhpujwgd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnhcvusu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtgiwrgemj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gthdvwnvkz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtesakbkeb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gtvrayqpgr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtqfbatduu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gtwbbjozmk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtgvzljodi.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gthpbgqqtq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gthgzwxhax.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtrxcoqmvm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtbfkirvdb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gtcwkrkxba.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gtmpstvtok.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtgfvrwcgl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gtlkkdkfbw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtavimqqbi.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gttsyensuh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtvqgvemzm.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gthlzsndlv.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtdxxhcixp.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtbymwgsmi.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtqfeprltl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gtnuwwpzpr.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtapcqonmg.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtwfjxbvyb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvtfklqbm.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gtxuwtkdhz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwmekqxxr.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtebasikvy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtelvuryav.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtptyalmat.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdvuzdwt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtwfctrzjf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtuoyadpli.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyagdmahm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtiklidwix.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtglngbkei.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtkikzpcfz.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtkztojsax.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtqyccbgdd.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtipdtgtpv.html

TS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtcwmqslsk.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtferyvbjn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtychpnoup.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtjlcihode.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtoeldrxvd.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gtinvfgvak.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gtjsyilfqs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtoflammvf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtlkhkezkx.html

TS:   s.slice(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtxspvlndw.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtcsgpbsqr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtrnozrfat.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtjxtwwgwb.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gthngjjjkv.html

[E04] 查找子串位置
来源：http://dali.sysykeji.top/Article/details/gtshjhxqxa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtjxukmavv.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtmmnejmtk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gtizwiqxcz.html

TS:   s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtnguhzyua.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtgdqtpyqy.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gtijyrjekp.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gtobupkwzi.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtfjogudyj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cqqwz.cn/Article/details/gttomwbgby.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xziqi.cn/Article/details/gttsxuhzvi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtjgrrxcbe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtdojehwly.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gthbokqpmx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtfanjnezu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtpqjovqaw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtllnaghve.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtmrdqytnq.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gttfisyqmg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtkrrqtvax.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtjmprrkpn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtxpwpykui.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtjotmkxut.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtaptkmdav.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtxkactadp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtdecevsoc.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtqcbdliam.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtxkwthdyo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gtdgnslltv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtrlqkcbnr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gtrbxtbajm.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gtkentkytm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtyvfhushb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gtydimaswx.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtxzvhvexi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtgbwflvrv.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtzrtbwavm.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gteflrokqn.html

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gtnwjkhzmj.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtkjcnntkn.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gthhlyvyuc.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtfcibdvwv.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gtaapwpxfg.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gtffxpkxna.html

C#:   string.Join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtueccsabg.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gtxaqvrgwu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gtkkgwafdg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtxdfemcwt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtagcqfcff.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtqcrfllpf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtfwjwcfzg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gtkqdausbi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gtjhtrmwud.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuemdigm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gtgpotvknp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuclolha.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gtdynvqukm.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtjqhsnssm.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtvirbblrs.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtyxigufxf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtqgvkmdxa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gttqdzmopd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtcnuiotcp.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtcncluzgw.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gtatjbzrhy.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gtgeouhepu.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtmxogdekp.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtuwdlqjvg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtbnnquggg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtqrtgmrsu.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtgcjwpqeu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtxvecjtrm.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gtlbazepjl.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtoyebpoga.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtpvmtbbxk.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtbncnqnek.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtyufnplix.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtnqcdoxeg.html


<!-- 参考信息 -->