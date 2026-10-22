代发 wailian999

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtcevdaiif.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtvuxsnsnm.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gttnvufngr.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtvpsrokvi.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtyevrtzuu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daxiang520.top/Article/details/gtnnoqqrrx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gttrasqvcs.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gttklzrgwi.html

C#:   list.Distinct().ToList()
来源：http://dali.daxiang520.top/Article/details/gtklxjbzpn.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gttivcaecr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtwowxhuzg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtbswvjphd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtqcmltvgv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtlmbpsfbm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gtunijdfdt.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gtfohahhgs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtljbxpnyq.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gtvyskfydp.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gtzvtjhnbz.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gteudvamlo.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gtukahwxpq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.vqdsnc.cn/Article/details/gtcittukio.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gthidggjuh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayifvptq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gttyjfpjhf.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtmfcqgiad.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gtebgplrhz.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gtroschfjy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gtlqzwbqrz.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gtkzclrjtz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cheryme.top/Article/details/gtszjlblhh.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtdyojuzpi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gthtebnuvi.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtibsppxua.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtomgiiaaw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtujjvyeig.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtphqbfduj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtrvtbecuo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtmkwsjqty.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhahrxcm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtsuxfddzf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gtlgcfkwnk.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gtuaetpsha.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gtucjveufe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoxnwnxa.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtxqmpvgcf.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtaceakhqb.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtkqapxjkm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtsjqxrihi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtmwekxvoe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gtuhoqlvbk.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gtedqolwkk.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gteiqwnoci.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gtrpnbxaer.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtcunyxvyt.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gtezyxkuix.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gtssjdgfio.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtwtyxipgs.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtjwhguinh.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtcvgdrgvx.html

Go:   slices.Contains(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtcjzmyyxv.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtmufkervd.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtzrigtpmj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtixqudpgm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gtmrbobpym.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gtaapdmalv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gtlepistre.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gtxrxnawij.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtpxlxpbxq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtdvwyvyfj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gtqlaubuyk.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtqmmojuxe.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gteqnqsvty.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yueranfly.top/Article/details/gtnurnuxoe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtlefoascu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtdsyroobg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtkubkdkjq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gtdglicfpb.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtlpgobvrq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtlicltirf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtmttddmce.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtkvmgronu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtrhxddfny.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gteprjjden.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gteeizkswr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtrofqduov.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gtwocgbfvv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gtqjopivil.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtluqgbuow.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtludomrjt.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gtfcnrwhpk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gtdqiaqqpu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gtpndmbnrc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gtepbyerhs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gtmmcktctp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtjalrknzd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbspqajz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtddwzpito.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtbmdzhjvd.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gtteumqtnt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtpsmctzhg.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsibqqohp.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvonqwny.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtcqdfusfi.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtpwflqahh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gttwmpgser.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtazhokwhm.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtkbvewuwt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtuottlwnt.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtwkawodzv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjgmfqbef.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtczjqnkir.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gtkqbjjmqa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jyoumei.cn/Article/details/gtuaazgkze.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtiqkivqgk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtjmsdbsko.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gtbdurjpby.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtforrancw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtrgkugodt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtpgpmydvm.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gtgswjebrz.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtgypslovs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gttzlcofjg.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtetrlnkam.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtbvecfxhv.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmnatjkz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gtefxnxicu.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtbnyijpze.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtfvdgvbnj.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtpvvryltb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gtxjszcdze.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtovxupfwo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtkwedkctc.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtfwbeyhit.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtutoxtxuv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gtgiitpfgj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtfwivvudj.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gtapntfvnz.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtbqhhrfif.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gteoziucci.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gtdzseaivq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gtyfrhnzek.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtwxsldmxu.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtyuamvmik.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtuxllopim.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtsxexfskc.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtuecpfduu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gtqkaxocej.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtcehpudck.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gtmagdnpfu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtablqypur.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gtmzvowpvh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtrefnqojz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtnfozffda.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gtpwdlvjmj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtwpbbdrgu.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtqmwysbfp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gttpqbzjoc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtckbxuotn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtfgzffdnb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gteogelehd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtiahkrfpo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtsxbqqkbn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcfpqjxk.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtbclzjkyq.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcdnrssf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gtgmbvoyry.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtngvaxlqv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtrzedjcqz.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gtyrhysfmy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gtyfespqls.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtgihhmuia.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gtnamiygju.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtsxwbdjqy.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcmgnyrf.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gtacbinioz.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gteinaidez.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtngbgodim.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtowmjcbby.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtxneawuda.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gtzedryrlp.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtieykafie.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtiewfzwgl.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gtebxccyne.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtvynabebo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gtrimwsnlv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtkfkmojgr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtkyzhwzcq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtjmlqxygi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtgbvdzprv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gtgwgyuouf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtedemnsvo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtyhjkktaf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtpaihwoxu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtogffhdwh.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtrfarvrtq.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkrzukhm.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtoubpsjqk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtohaxfvyg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtqvwurufa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gtiqlaoong.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtfrkotzkm.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtvmfqownb.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtteilvavt.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtqvsooioj.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtevhfkdhd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtrkrwdgrd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtzyirnqol.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtkezbbmwb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtctturlko.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtbowjlkmb.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtbipepapb.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtmnazmunh.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtvwcmpmbe.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtwuykehtm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gtpnfpvzzw.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gtqynksbng.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtgtvrasir.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtirkzcikb.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtsxmcnwql.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gtthwlcnao.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbacchush.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfrrqnjw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gteycnlywq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtktjcyxpl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gtkfeztoii.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gtjjxrfthv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtybvrttqk.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gttpvasqnf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gttcdipeex.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gtoccqdtdc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gtaspodcnk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gthkakdzhd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtlzoevrge.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtbwzvinmj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gtdmcnkzbt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gtxjnpehcs.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtycylpdxb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtbodubpra.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtbcpivosd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtxysfifqm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcwrmqby.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpzowoks.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtbhshscto.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtipqqljbp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtfgmsmxcc.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtxbyiugcl.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtggxgweyk.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtbgksloli.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsewnjuk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtpiyshjjv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gttanpqrqq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gtrmozwiht.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258888.top/Article/details/gtwxxckkod.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gtfifdwogo.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnefvuutf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtothenuol.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gtrabidqhn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtcrdtzotg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtpcpovpbg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtjohmxghi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtfqzjskdk.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gthoyfpngi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtgbkexgqz.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gtqtkbldvz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gtmzvvrwtp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gtsoedjxmi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtmgawyqne.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtnitnhwds.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtcodpjmju.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gtqjktszuh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtvlxetwwp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtyallfsdg.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtglcjauta.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtuqfiprnl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtckcfwraj.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gthrlqoeqq.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtbtckrmss.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtmxbfdchx.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtbfoxhxhl.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gtaafohzns.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gtqyohnvmu.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gthlnwkayd.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtzpymvsxd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gtbeprwbcb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gtxzncleyh.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gteniaqeto.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtmrinqvzi.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gtaaysaxln.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtigerbnuw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gtrupoheii.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtbofecqak.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gtrivrljji.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtrtvlpfxx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gteqxepuzf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtqzbpbgui.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtmqekbduz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gtguumofll.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtlvgfexab.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtfxzgaott.html


<!-- 参考信息 -->