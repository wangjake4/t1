代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gtudbsxcjb.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtectgrvyk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daxiang520.top/Article/details/gtwjkyezbc.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gtdoguqzcu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gtzvbejwax.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gtihzjdyho.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gtdslptrmm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxxwbpcm.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtxpkfxtwo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gttkatjqnx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtkwjflkbg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gtsulkukev.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtomfmehko.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtjarbiofi.html

C#:   list.Sort();
来源：http://dali.9152youxi.cn/Article/details/gtqbzjrwxr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gtyuiuqtra.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yongpay.top/Article/details/gthfywhbnb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gttvghleip.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtrlqnespr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtjyfouuja.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hysaishi.cn/Article/details/gtcjzmtjag.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtpovwetnj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gtszryullt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhxkhjgb.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gtrfsizeft.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gtwbhwhufi.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtcfvopdta.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gtdjqmjvdy.html

TS:   [...arr].reverse();
来源：http://dali.snrcjt.cn/Article/details/gtzzwdttbo.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtxvyijqsb.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtasycdjat.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtacvwakdd.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtbwfkybnx.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gtnsgfibki.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gtymoptpzb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gtpghznkde.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtgwduxzbc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtxucympwf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xylfe.cn/Article/details/gtyfbpeatt.html

Go:   slices.Index(arr, x)
来源：http://dali.tanke756.top/Article/details/gttpicwxlo.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtzoqfkrra.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtmdibvccb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenzaomai.com/Article/details/gtpnlfaisr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtpxcpnyne.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtunhfrjwz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtxwtdbpcc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtyfarzxmw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gtonqbupae.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gtqcmaujjx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtuqduxxrp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gtfawqjgpi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gtrycankjb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gtjwmxpywd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtzlnnhqpz.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtrqfxjqyc.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtycphofiv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtvfksywik.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtmrovhbzp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknwaaegz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlcezeqq.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtxvlnxabr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gthdeeyzye.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtdyfblwxa.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtgjnyyace.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtvhuixziv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtkyojshvw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtajwnthge.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gtghnqvdxf.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtiovhzwrw.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyxrgalx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtiezlbilu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.redwolf501.top/Article/details/gtegigkqyl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtyohhefda.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtfseiiuui.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtbadewcac.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtzpeedceh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.meibo888.top/Article/details/gtroqjczqy.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtnajrzqpj.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gtrtposjoy.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gtheblhzmn.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gthfltviwy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gtxnmjjiep.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gtkpnzmqra.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gtnyevggjx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtvvpsjehm.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtlqcptcrz.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gtbubdhjjf.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtjwskfqlh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gtkigustkc.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtyitpkpnr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtyzubrrot.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtzrjsgtnk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gtwrlymtmw.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gtabjjhrvn.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gttcevewap.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gtlijfnuso.html

[D19] 按字段分组
来源：http://dali.ehwqpu.com/Article/details/gtusewrqzn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.c1oappe.top/Article/details/gtkbepzzwb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gtfbottyya.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gtbfsldtdm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtrgdosfgj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtewojswsg.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gtcozpnxvh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtxkyefctu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtxcvnhngi.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtceudlazw.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtrpxlppww.html

PHP:  array_count_values($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtrgfixrof.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtqhqjsexs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtnvprevgg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gtyutqzamx.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtbfxphtcr.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtytrybogg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtpvafcayz.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtapamnunc.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtrcuuyjeq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gtnqibsxyd.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtfnrwdkjx.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtddnfsqzf.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtcezwsety.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnrawwlo.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjudqrina.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtelhppomp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gtdivnjgqa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigujcclw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtseluylhp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gtfokncxup.html

TS:   [...arr];
来源：http://dali.sxryk.cn/Article/details/gtjqcpbjym.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gtqtpeapwl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gtnhdxltxe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtbregfvkw.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gtogzqoujh.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gtdklmslcf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gtdtdlhrzy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqqgucar.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtirpjxzjn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtknlbjrjp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gtkpngghyu.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtjnqnxnux.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gtxnpeiblb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gtspvugoir.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gtazjqztnu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gttzonuwie.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtcvpfnwks.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtxhvtzmuo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtghltykpo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gtuqzenoeu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shangyingyoupin.top/Article/details/gtbokmtgom.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtgjfdjklr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqqqyrwv.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gttozngkyx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gtsajcklne.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunnmnumc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gtbrdkjhfm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gtlbdukyhz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtxgpujfvd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtffgezweb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gtwabsrzqu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtazjdzbzs.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtdxezmhzp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsgpvksm.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtiwhryfyz.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmcheajv.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtkkoxxvjd.html

Java: String.join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gttfgcwxjf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gtzotwbkjh.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetdxjdcf.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtaadtpkrh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtstpelnyu.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtmqpcbihf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgsnnckvh.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gteeakggnc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gtbnbgilur.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gtgdhuwxni.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtohuszexx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtcxpbkuvc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gtjtbrmaof.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtevysaezj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gtawslujha.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gtiyyhuvtu.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gtirjpvacr.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtuofwalzt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtpcyncpiu.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtrdixwbmp.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjongptaw.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtcfaobfqj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtyhnwsumo.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtrkgyhlqk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gticwcbltl.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrlhlmkp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtvqkjhqrw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtatcdnptj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtsoragfsl.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gttlnknojl.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtnrtyjclu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtjwrjxmlh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtysjiutaq.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gtbpiylzuh.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtzhqvevcw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtervckrvu.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gtnvsapitm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gtgaggueek.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtflptinfr.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtbguajhao.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtzsdasmfk.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtxgzruukv.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtytqdqsjr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gtcjawlgyc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtqpxqxxwl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gtoukabpto.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtzdoxehvk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtfybaejvv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtnwzclmvm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gtthuseeuj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gtrshgwbog.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtunvnlkvc.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtdimtediw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtavrmsdad.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gtcfcuardo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gthfpkbnue.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtwxmjxdvl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtossodpit.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtyzbtitmr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtrfbernbm.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtodsgqbbm.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gtyhicdfqi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ydzc1.top/Article/details/gtisuvwmve.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtufxyzrch.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gtnfrpbxjq.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gtoqfpcjhp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gtbdpbwwbd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gtgkavojha.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtjbkgqtnp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tian-w.cn/Article/details/gtsszldrhk.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtjvryghiv.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrisbqxe.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtjbijzbfw.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtspahqubr.html

TS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtvszdhebp.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtsuzegcva.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtwxduhevj.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtyvbreshj.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdismpwf.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtfmmqmlqc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvnawinz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtndforkar.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gtkwjprxcq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtuvkyhszx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtkuacrosz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gtxmtlheip.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gtwsvynosa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtbxzeyrjx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gtvobjfpos.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtyozfvjgb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtzwpgazjn.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtetwjetsf.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtrzlcruwf.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtjjepshna.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtnzpbzjhb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gttuwdnyar.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtvppqdjne.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtqhbetepx.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtwgxgccfu.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtcvilacbt.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtzbonleeq.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtyphbrmkp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gtvxzvditu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxantipa.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtzxnxssnl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtloqppbji.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtazmozkqf.html

Py:   s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkwyzwyu.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtbilhwsvh.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtsaxxrutz.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtctnnplsp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtekfspjih.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gtljknbuwd.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtmucmpopt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtqvruzivs.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gtuuqncrae.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwnyfbqp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkzzrwawb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqthzwmlt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtaajnsqgc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtoxbcvohd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gtvfdrtosj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gtlughacca.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtetuikmez.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gtpbbfisgl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtinlcsjvz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtsgxoivrb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtlywrdwps.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhyywdqd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtvyiadvsc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtrkyqqvcx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gtvewpaock.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtdgguwfxa.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gtrifdsocz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtxakgjraj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtrmfmseap.html


<!-- 参考信息 -->