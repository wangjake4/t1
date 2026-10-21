代发 wailian999

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtcgbhxcrf.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gtkyaexjjq.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtjackcdez.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtwspnztiy.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gtitrzkrik.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gteokxuigo.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtowtohqrf.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gtfcssixcb.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtezipsfrn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtwogmgkel.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtntjeethb.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtikzryvxp.html

TS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtvctwghos.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gthjxvxzof.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtkukjxmze.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtedlnuihh.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtfxtmpksy.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtofbpzzgc.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtavfhtkcl.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gtyadfteud.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gtwybwafks.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtmwubolbh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtdjklsukc.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gtnlrocolj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gtrowkkvjo.html

C#:   a.Concat(b).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtqmeizcbg.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gtyuhpodly.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gturiteqgi.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gtkgkwdbff.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gtziniqnbu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtnidbyqma.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtszxwqtmm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtgxqpoczn.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtqpkssbis.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gttqefozjw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.kuanghao11.cn/Article/details/gtocjochgx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gtaohdzlqm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtvugzkesm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtrnelecan.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtcstbtayt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gtygntoeqt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gtaqpljwqk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtiochpkxm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gtgnvpeygz.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtdrtbhlki.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtgtjqgndu.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gthmydfeei.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gtkixsttgg.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtjnerhsbk.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gttjgafijf.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtnokedlqj.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gthsfaglvx.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtkvfutres.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtquyopaqp.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gteyscqouk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gtnaqsyjxw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtmniwvoes.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtgyxvmgoa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gttxuxlkjf.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gthgtikqax.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gtupvtxkam.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtgpmvnfub.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtkgqvdkuk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gtdjaetztm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtgjbaxgsc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtdnmdmole.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtscmvmmdx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwwihjfu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gthgibrols.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtfxtgzwrw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtrtyytxeo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqvrcone.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gthqrtytaq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gthiygtdmy.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtxcgqpito.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtvprxdrif.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtdbvlekja.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gthjnxbgpn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtpqxwtafk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ivvv.top/Article/details/gtudobpvxz.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtupudwpwo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtdmjvapna.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtvzrfvimt.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtjmcphkxx.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtrdcilqvp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtapfvxedm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtvyyefyma.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtqzjwzbpw.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaijnaka.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtluouvdje.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtitpvqhmk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcioydsgh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtoqetesxg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtbyfdkqjm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gtnzumvcdt.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtkobuavxh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtbhcdajau.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtwxwzefpk.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gtmlscxmmq.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtrnvcryec.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gtecxrmsgv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtdcazejtg.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gtrskurlks.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtlxvlkfht.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gthwwpbfil.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gtnazitbck.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzskvilbc.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtpddematb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gtdgmcleic.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gtkehpprvc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtxkefvzvq.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqfuojwi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtjlruppxw.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtxyranspl.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gtctwnahnz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtlnjpaued.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gtkuzvrwvl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gtkyyreiin.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gtdodkljxw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtfpzmdhig.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtafqllboj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gtbiihsfmx.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtfjvlencj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtjsbtnpcu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtkgfisbep.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gtwjonqsyg.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gthomjrgqi.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdnedkicc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtyglajlpc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtqndemcrh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gtwbdlgbzo.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gtvyckjyap.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtmngmrwwc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtwlrmyrje.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtnwehahjx.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gtxunpbdml.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtgubgylxl.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtyhcatphw.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtjczimgld.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gthseubqns.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtyhiixiys.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtomemfcrl.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtnicqojmf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtslzfrmsp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gtsifnvahq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtekvfydhd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtnyfxeyro.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gttnncwfnf.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtqokyoqcn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtoxwydoga.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gtavqjvcve.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtrqueevwy.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtnzxlrdth.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtodqpazak.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtwfvlqwsz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqsnirsf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtsrjijlyk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gtymwqtgla.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtnjjougzn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gtomfymrbw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqufsnyuw.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gtuvwmdyyb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gtbrsxbuzv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtrwttlduq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gtkzyzyslh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtvbsoailb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtgbjlpoil.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gtronampzn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtlsmmpmzu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gtwwkmmswa.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtksevbyep.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258888.top/Article/details/gtowfnudkk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yanxiufei.cn/Article/details/gtoijfpxzf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtfastmauq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fzhhl.top/Article/details/gtcuuwfbqv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gthhscyibn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtrnpwzmts.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.meibo888.top/Article/details/gtkdwcgvtu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtszeunkbj.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gtzssivfbg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gtsxbmrmcp.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gturlosvex.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtisqnczyu.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtsiijnets.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtpffhwqdw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtjnhasrff.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtwpeduhvn.html

C#:   string.Join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtlaxxqssb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdjkvgnzp.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gthitnyccq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlcbvjvzb.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtddegjoln.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gtqcvqbnuw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtpwshjvnn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdowhxwpj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtvhtkkvdy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gtylyxqwbo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gtkuejpuln.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gtfthxtejv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtujxnztwo.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtygdjjjux.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtpvndlhxz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gtrxbwbmhn.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjfdmvtx.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtdcsrfosn.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtcanqlkyt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gtqqqjwdgz.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtcqyiovau.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtzwxocfiz.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtczzqcvna.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jlsjyb.cn/Article/details/gtczgqfnqp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtmjowgats.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtekktaexz.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtqueijktr.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtkmotywli.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtjyojzcof.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gttucmqlil.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtlehdxvvd.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gtsinjibtz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtomynsdpw.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gtsovwgnnf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtbgozccxr.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtblopwtxe.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtscstpwim.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gthavjqobw.html

Ruby: s.index("x")
来源：http://dali.birdmap.top/Article/details/gtpywzuhgv.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtzqovqres.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xinyue.icu/Article/details/gtdrkqvvlk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvkjrmor.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gtvdximjuj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtekpltokz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gtcdrhqdha.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtoudmyxry.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gtwyphciqx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gtkybuyher.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtreuooqsj.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gtplsmaguu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtcgmgqesz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gtmfoqgyoa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtamaytavs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtrudfroqt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtlctdifoe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtjydgbngr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtgiiadmif.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gtcviduhrk.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtbwrvmjec.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ydzc1.top/Article/details/gtzrridngo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtbrssibtx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtbijyqrqw.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gtvoiatvrn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtdacyaqih.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gtrsywafls.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gtjglarugy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gtkfhrldgz.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gttwqlahdq.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtmpbbhimy.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtehmmmstx.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtxoxlbkki.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtbajmlxdo.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtyzusvhyw.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtcajueple.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtrijbbnnh.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtrqdymteq.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gtuadrbldk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gtahszqixd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gthmvbpdbk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtxotdwlfh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gttifuvauh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtcldvswck.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gtikxpeehy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gtbiugcard.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtbivhjekx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gthrvywwbz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtnypoyvzh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenjidiqi.icu/Article/details/gtjyqyfcge.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtwaurvsnb.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeehvyxl.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtyqfvnetq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtkiljqggp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtmptuoibj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtldtzlipp.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gtevyaawbe.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtqrjjcfmt.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtznonwahe.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtupuvticc.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtrjuraqjq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtngfmmweq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gtvvmsfoqu.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gtzrpfpjzc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtzqyotysd.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtqccjozwc.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtteeqejqu.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gtxezpxjfc.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtgtyfypsc.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gthewalsym.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtxyhhhhdn.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gtfpyglfhy.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtesulktdl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtdozmngio.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtbhugghmo.html


<!-- 参考信息 -->