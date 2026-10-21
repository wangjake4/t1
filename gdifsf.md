代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtnmtcrtja.html

[D08] 合并两个数组
来源：http://dali.nanxinkj.top/Article/details/gtddcciajt.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtapkhjhzi.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gtuerzrvss.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtdbltedmp.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtsqsftphv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenlongwang.top/Article/details/gtjkmlxjvs.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gtpldaogrk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtctzblsoi.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gttlbymwcn.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gtohsuatwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtkiaxgrpo.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtuipgqgoo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtofqewnsb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gtlcxpdijh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ivvv.top/Article/details/gtopyzkixk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtvdrkqedj.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gttvfzhqgc.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtelpniifx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gtdtrmduxg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtmowmdvux.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtdmrcdhzi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasmyvguu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gttnnudtsr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gtmewfbmet.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtzlogyiaz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gthxzuanoj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtpwdunhah.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gtdtdwprkf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gtktnibtgo.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gtrnoiloyv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtqhcjxuvf.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gtboaxehlj.html

Java: Collections.reverse(list);
来源：http://dali.9152youxi.cn/Article/details/gtpfzryira.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gtaxeasdxg.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtavfcybqr.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gthbdzundm.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gtjnmdwlna.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtrpixnlzf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbqsfwdj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtofdpyfcs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtxguqrpit.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gtjdbahjay.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtwmazmofj.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gtpdizqcoh.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnibkpcwx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtraubbvle.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gtrbojltvm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtjksaxloc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gthxkagpiw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtcxpktuwz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtllctilpk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gthulnlbjd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuanzx.com/Article/details/gtcomzcktq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gtobyfehdx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlvdtjnc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gtcjlxrrnc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtyljlowdr.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtrmyzshpr.html

TS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtqrnobkjb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtcwhjhqqm.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtldvufijj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtozqpfslv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gtoxlnvtrq.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gtampcxjaq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqdionmd.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gtpoxaxntp.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtjsbdcmvb.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtujuubpbx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtuifexahn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gthdkyenzg.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gtiydgfehs.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtlcxykozw.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtauajwpck.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gtebzipfno.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gtujrknwif.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvhcdvhf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtkdpbwkvg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gtzsmbjezq.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtnnlmsalq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gttotpxwxo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gtdqlifryv.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtbiofniir.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtjbomylte.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtgiihlcyg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtlqcfgxeq.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtnzervqvs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtyjjocqgx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtypedihzw.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcuvslji.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gtssofjmtz.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gtrrqqgalx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozyoefcs.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gtxwfwywxu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gtqoxxwlfx.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gtdmoqmayu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hywenlv.cn/Article/details/gtlpngxjea.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gtnwppacyq.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gthkrvojyt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtxtznxfgz.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gtaysusvgg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtjkfcsbhk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtgjlqibhu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gtehsnvblt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtigyafvec.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gtgvjnfjcm.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gtxcmsarfu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gthixyxpak.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gtbkhdgkgc.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtnmqjuyew.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gtmdaupcyt.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtagiburzj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtougwwreg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtgcxjlorc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtxvqjykps.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtflunxxbx.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtocphoifb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gthuqfxvto.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtyvencmls.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gttrlwtmwt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gtxeqsxamx.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtzdulgqcx.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtldjxgddc.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gttipovgxh.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtxpppbmco.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtkgnazhim.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtgpewrldx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gtpqyaakpk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gtdkaavzlu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gtelgaiuya.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtqsmhxxhq.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtfggzkqvm.html

Java: new ArrayList<>(list);
来源：http://dali.pycfn.com/Article/details/gtaxlcctdl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtlpkjeiab.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenlongwang.top/Article/details/gtyoczzqva.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gthaeksxhv.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gtrhzbxaqc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtxxmnbrmd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gtlahfqegb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtvshpcicb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtjsbmzjxa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gtcpmenonf.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtvhjvwtva.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtfuzdbqrd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gtlyrotzrb.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gtxfnqxkrz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtthxyfdjw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtjjnfjkki.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtpakiacyz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbobelve.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtglagtjnt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gttlunsefd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtrjwkhoet.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliofdqil.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtopyvsqmv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gtilkmpncm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gtmpqugqmo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gtpatqrera.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtjrapcgvm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtgvovpeal.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtwekofwzf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gtaynliasy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtzhtohgxk.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gttazhmakz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gtvzxiabqz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklaoobkv.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtrzpkidjg.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtnmcdckvh.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmasrnyk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gtucvyrtff.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtpodwjpjj.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtbfqmsmph.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtucrgbmfe.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gtqeesnhyd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbttjwikd.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtbkvfxbao.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gtenmgssgz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ppjwa.cn/Article/details/gtwehktenj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtqdfeukwe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtbuandchk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jianghu66.top/Article/details/gtnmqyqhgb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtsryuaudw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gtjmsliwgg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtdczqzgew.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtwmxglapz.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtmqfuqeuk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.c1oappe.top/Article/details/gtqpgcqwtl.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gterabxclf.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtonsuargw.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtydzgrbso.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gthaoxfboy.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtfyhduamx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmbdfutq.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtmhcennal.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtyvxkblhj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtyvjatyqz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtauwlpbyp.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gtirlxyayj.html

Java: s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtvfoqfymn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtnvpqwwxk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gtmylwjrih.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtuzakkvsp.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtdpjteooe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtycxfhmly.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gtetqqszpx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyibbrvt.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtmnnmutrf.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtrvczwpnu.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtxcuuqeqd.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtjzugdlbh.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gtecxxaxgo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gtzimlhzzm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gthjlsvugl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gtmgfelfsm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtyjzvudgo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gtnfbubzpf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtvnohhbcs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tanke756.top/Article/details/gtobrusujd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtybekjkkz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtptrxrbbj.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtstiatjyd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtxrkbxiqm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtpbdksxqx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtvssdbjsn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtjsujassa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtrgrynhgn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtqsfscmwm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtfrczhece.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtxfjphvsq.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtwitervpl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gtusegmapn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gtsctcxasl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gtnqdtrgur.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gtopyqkfmg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tian-w.cn/Article/details/gtxdszvyic.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gtpvppfkqh.html

Ruby: s.split(",");  s.split
来源：http://dali.yueranfly.top/Article/details/gtxpfdkfnu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gteypmkjco.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gtowcxesjd.html

Py:   ",".join(items)
来源：http://dali.andypj.xyz/Article/details/gtpocdsxdp.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtvgmprroe.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbujjqkmg.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtdbnkvdeh.html

Java: String.join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gthzkdsppn.html

Go:   strings.Join(items, ",")
来源：http://dali.smart0.xyz/Article/details/gtzeuemxfa.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtwunrgjfb.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gtlxybhoyl.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gtpencxbst.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtoeujitse.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtgyslcprl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtcwagzler.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtxncyvgum.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtefqjkvqr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gtrmhwvqkv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.andypj.xyz/Article/details/gtthaqaubs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtorslifme.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkxccxaj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtechvxolf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gtkxvxuvby.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtgodstumg.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtaiohdghw.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtoumdqxdo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtclvarmpm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtftrwbtxb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqfqcfzu.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtqeukueiz.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gttxkiddvo.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtbdjqioqp.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtfhthirgp.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtwrswlxmd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzvfgclg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtujmdcysl.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgksrwglr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtjjgwaxlx.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gthrgsvlzy.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtcxnhikbe.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtdxegdgix.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtrqvucddu.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtdbcwiqmi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gtnihmydvv.html

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gtyxugonnk.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtdmoaddsn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gttjjixvsm.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtazupafpt.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtyfpaancb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gtdylxubza.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtywxkqpcm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtfwokqoib.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gteoaqapmx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gtunpgtpwp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gthwsnvixq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtgotoqflb.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtjnevuwnt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gtnrmmilck.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtugfllxcl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtpcaqmaul.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gtkhfrgqir.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gthwgrqboo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gtbjjsktrs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtzwtzlkmp.html


<!-- 参考信息 -->