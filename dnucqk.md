代发 wailian999

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gt2xcidubhi.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2kadfsarn.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2iebbrqqz.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gt2yspdkpkp.html

[D07] 切片 / 取子数组
来源：http://dali.guowangkeji.top/Article/details/gt2rkfqclpo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gt2myqudmia.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xinyue.icu/Article/details/gt2ysawhppc.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2kstpwxre.html

TS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzmnfjbw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2beowdbvf.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajvaspfx.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gt2pirsbxuv.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2yzqqjmhd.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2naumlhxg.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwmlrmov.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gt2eupffxnq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gt2pkholjdf.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2wftadcvj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2dshfaeyv.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gt2gkveqojk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gt2eysxanbc.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2fvupanzk.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qoqiyjva.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2hdugghsh.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpmfqykt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gt2fjylzcmj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqvmzblc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gt2hljoswnn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gt2mvkadayd.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2geoizyfn.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gt2cwcceslj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ehwqpu.com/Article/details/gt2itadkqcn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gt2zrglrnaf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2jwkbzveo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2zpphvhgn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyzrquey.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gt2oduowpze.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gt2qaazfwaw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gt2bcwifhfk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yueranfly.top/Article/details/gt2eqfjaiid.html

[D11] 反转数组
来源：http://dali.cdnleiting.top/Article/details/gt2pvemrilr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gt2rqyrzeob.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gt2pccfmims.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gt2norzvwij.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnvfajkl.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gt2zjrsvyjv.html

Go:   slices.Reverse(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmqqniwi.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2tphvgtod.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2zecnqnqw.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gt2zeosexpq.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gt2agnbtmyk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2ritlqaef.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2ojbravda.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gt2hvphatrg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gt2ojkimyym.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxwbdfko.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gt2cppppvfo.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gt2mfnapgei.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gt2vxonnxrv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2zcufppbk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2ajsgmhum.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gt2tfiievqp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2ucutekyg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gt2slxqdouh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqddgedd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gt2tmymtiav.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2yculgghj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gt2rjqbtdxc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2qkwdstas.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2bqcsxuac.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gt2fvanssvc.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gt2xtapdmeo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gt2cuoxjxme.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2jlaqhuqz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2gilufsig.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2gfnmmjrg.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2znicaimr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2dsaxmczz.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gt2cbeusqqq.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2onaabfsa.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqmsxorn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gt2qgyjuxtx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gt2edkxhmre.html

Ruby: arr.uniq
来源：http://dali.dashuyun.cn/Article/details/gt2bovpnydl.html

C#:   list.Distinct().ToList()
来源：http://dali.daxiang520.top/Article/details/gt2kruomqom.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gt2lplhdqlp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2ecnruwar.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjhjeqxi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2byolycky.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gt2usqkpryw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gt2sjvtsrra.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gt2nvojchqa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2maafieve.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gt2gazgpxaq.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gt2kutnajrl.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gt2iaxkvomo.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gt2hfeqtfyc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gt2jvzitirj.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gt2zxggxqyn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gt2nqbgqejq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2wneqgwbg.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gt2swurdjpk.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gt2ahdwbodh.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2sctovvyu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gt2nozdxkwx.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gt2uxqevxgu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvorvxex.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srizcpsa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byzbiewk.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2ejabrnzm.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gt2trordpqh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2dlmgaurd.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pimhxamd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gt2edukzgip.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gt2npzmkcnp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gt2ftllmwwy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndcpenog.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gt2mqjawyvm.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqvcmizs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gt2rakzpsqi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gt2uepxtpyr.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gt2txpsmeqd.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwnuktot.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2vwiqdziw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2gtqmzknz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gt2nddnunom.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gt2cveweyhz.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gt2hyezdobb.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gt2esucopgv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptugpgwi.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqpnikbp.html

Py:   x in arr
来源：http://dali.sweek.top/Article/details/gt2khxagysj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2nniwamkm.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2voscopik.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2uvqopagv.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2stxlxkwo.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2awzmmczk.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gt2hlpkgjnz.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2tncclpsw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gt2gaamjocs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2sieaolsa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gt2eaurfinj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2onsmfpst.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gt2pnffuzoo.html

Java: new ArrayList<>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2msgbmoff.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gt2ikrfyeqy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2wlmssrho.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpcmbhvq.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gt2ocujkmcb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gt2dmjrxbft.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2rmbdxgbi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2cbqyfxxb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2kyymjagw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpxjlyvp.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2fxcfotub.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gt2gjavozmf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gt2ptngpznw.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gt2zkaareoq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2bflotqso.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2qojyirch.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2kjpmpriq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2jhmlwokp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gt2mnaydioy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gt2wefprmqr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gt2fvilmzad.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gt2fzrwaxmv.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gt2jzbrjhlv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikbmtbou.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gt2rxjrkkjx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmdtxzeg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gt2amhczuqi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2araydejb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2dofyzcxv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gt2vdbncrud.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gt2dhhpgmlm.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njbueqry.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hswcvasy.html

PHP:  implode(", ", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2owfgtpoe.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2nbynlphe.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2cdcuqgoh.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gt2dnnhtawz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gt2ikpcucet.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2jadjlmad.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2cjffzypz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2udxuaxot.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gt2xgqvpgxu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ftkhnpfm.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2emnmgwua.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlgodsmj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2baeangsc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gt2dwqgwbvs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gt2biapjdzc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gt2iwykcrxg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gt2mikxxnfo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gt2mtwzkvkx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2dgdcdfnk.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwkqsoes.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gt2xtmbbhlc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2xmxosmxg.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqahcegt.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2gqxsasfb.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgvggsco.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2djlkaqsm.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gt2ruybxrof.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gt2ldzjurvv.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gt2ooomyeip.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gt2fdzgkseb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2smdvinec.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2rnajkfho.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2fmuwwfmv.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2vuvkmpqy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cdnleiting.top/Article/details/gt2qdzffoua.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gt2koeiesfj.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnzegvlx.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gt2ymwymypb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vihridyu.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gt2dkeglasv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srhuaaxt.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2jtraeakj.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghbkwbcp.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gt2stgliteg.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gt2budzovey.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2lbljbesy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2scopzivi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gt2lbijrxmr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gt2ljirqgah.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2ztaiwxlm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gt2ukjrzklo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2yrbedatv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gt2owvkvozf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gt2auorvsqm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gt2ndcemqdq.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gt2ezzovgyi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2eolcqhxt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gt2tqcjwaiq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2npxbqxvk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2eneftagi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2ovdbdpwq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlsouglq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2shnjgnxc.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2aadicwls.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrnfhmqk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gt2uotbkaam.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gt2zysnbkxh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gt2oqacjufb.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npcejlem.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlapvqag.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gt2tpxxdmrw.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gt2gekfgoqh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gt2fsoxnnwd.html

[E08] 数组按分隔符合并
来源：http://dali.zhoulong.xyz/Article/details/gt2uuhgrbbh.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gt2qpldxppj.html

PHP:  implode(",", $items);
来源：http://dali.dashuyun.cn/Article/details/gt2stmmcstt.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpytrlsq.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2ychedojh.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2ydraysve.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gt2tuqkhpgs.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2cyueljen.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gt2gwfsjmlk.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gt2eyaubylh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gt2bejlptgu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibftlpup.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gt2mkauzsni.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2lnrphxrt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2ylwzjldg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gt2xgrecydu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gt2ulxbnmpm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iglekwyz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gt2bhwodoly.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2xpocdsqt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gt2hhlkftmw.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2uqxmnrew.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2pvpvnzdq.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2weuohgdz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gt2kicutojo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfvqpqof.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gt2cxiddpyi.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2qjrvazsc.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gt2fdtrgjsm.html

PHP:  strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2ifpxwdkg.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2nntcwvtz.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2dmvwihgc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2jfuzrrst.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2bbmovvey.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gt2wndrxahh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2uyorpabd.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gt2illepzum.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gt2qezgsjex.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gt2mrdflrec.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gt2jblkcafb.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2ucsynvrb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gt2vgbwrcaf.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gt2sucmzbuy.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2qceqkddh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qyiwylfm.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2zfhvrvpa.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gt2yzmfpdvo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gt2kdaijmmt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2bfibtmhv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2oxaygcrb.html


<!-- 参考信息 -->