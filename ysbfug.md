代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtvlggnnaa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gttltbbuii.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gtzvnzcrlb.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtovmjlwxu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtilbghppj.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gthncrxspk.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtkeyywtpd.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtsjodrwgs.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtuomnzsns.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtmxvswspo.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtqschilvo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtglzzsjse.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtscndvftq.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtgoavjpmt.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtdqxplhcu.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gttnbtsfjj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj202588.top/Article/details/gtfmyaaniu.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gtjgsliuiz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtovjomuqs.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gtmijfyvrd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gttrwnvasu.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtirinnvvf.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gtyflsoqbc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtagshebrf.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtcbzrtbke.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtlpknmskd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtyobwfjnu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gtdgmqmctz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtkumulnsl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtfbgsktdn.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gthisllqsa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtibbdlkrl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gtumszyozr.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gtsjiuffxk.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gtakqqsfnz.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gtecjdryhp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtalcqqqle.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtfnjaxdgo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gtenyvkltb.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtfpgyigja.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gthdgmvbnp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtzvmbzrxh.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gtuzawdxwu.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtbcmivwvl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtlhdpqpfh.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtzevgvuzz.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtbunngfua.html

Java: list.contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtumqksjaj.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtiltmxsla.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gtmqyekxcn.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtleqrbzme.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gtydrygfkq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gtumclmjcc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtanbtoemi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gtegbixgct.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gttcdrfjmy.html

Java: new ArrayList<>(list);
来源：http://dali.jlsjyb.cn/Article/details/gtxjiozjxu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtfckrgtka.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtjgaowzqq.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtflazlrvv.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gtdibaeirp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtidcniiqx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gtaygidhiy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtkejlggrj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtnoyhfzpj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtjbbujvxo.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtxtmbsabr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtstlfnnor.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gtibzircnu.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gthcumkecn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gtmmoambtp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtzafnptef.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gturdttcma.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtiaxytotx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gtnbqzdadd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gtcsypdkls.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtnriebzab.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtakxuucal.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gthixgkjwx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gthzhffmuj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtacfqdgkt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtcdtndmub.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gtyqwxxrbs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtbtrtwffd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnmqklom.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtqvxlytcd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtwpeyxvkw.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gtwsgvjbip.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtckngruin.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gtcsthduwi.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtcqyjtako.html

TS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtisgschwt.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtrykbvinz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtjqmogjpn.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtnbnsuegb.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtugiqvnid.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkddxpjlt.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gthmfvxgch.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttdfhlzal.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtlsljeiqd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtzizptfwz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtkwmatmti.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtrrnprfix.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtaxyaepzd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gtpzcaobng.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtwrzefcdy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtchlwjrwl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtscbkulnz.html

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gtzhizpvlj.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtlmfmpdab.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gtpslkduga.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtpwgmjswm.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtjherhiyo.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gteuqosvgt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gthudnitpu.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gteuamskoo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gtfdssvbfg.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtwxpdlydr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyrvdgvd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtuebprojx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtmjypwbcm.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtavhcdgnj.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzjoczeq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtaefjmedr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtwfuaiuhp.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gtajbuswap.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtyyjznbtu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtrxpzolqm.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtcwafgzxt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gthitlnmdw.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtgjhzywpx.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtsbosyokh.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gtjzldtyrt.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtpxqnvapk.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gtsvjpccxc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtoczququa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyssxzxvv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.svipenyu.cn/Article/details/gtnhjzoroh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtnkdppgoc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gtpihmxpwq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtpupbzikh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtoryfzxdw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gtrjfbozba.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtajfeullr.html

[E06] 替换子串
来源：http://dali.snrcjt.cn/Article/details/gtzugmkpcs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtxmnoatui.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtrqkdldll.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtghcdqgsx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtwfdvxkeb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtfccxihla.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtayqozokk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtvsmschow.html

C#:   s.Replace("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtzrdfdqdh.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gttwmdqhfk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gtvklbbicr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtruezeqmk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtytkznilm.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtawtrjlrh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gtdqpscvjb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegshlrfi.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gtvmewuzyr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtxekctvbj.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gtyadezaly.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gtuklmohpn.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gtqloldjkg.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtlprprjeq.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtyfxcfgkr.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gtpteqbmgq.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gtmdpkhveh.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gtsjzgvxcb.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtmlqbsptc.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gtrambbnyq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtoelhdkgt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gtfeshhnms.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtocydcdwb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtoyktneiv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtfoienzzl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gtxjmwojmg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gtfehahlks.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtptjevsaf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtdmkgpqxh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gtptvprjow.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gtegckeian.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtqnajiqje.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtlduxcsql.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtsmgxefga.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtbcxyzrph.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtzewymcur.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtveiibcss.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtsyxqjpfn.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtybsiarly.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtuhplvyqs.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtmdfptogk.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtkygtelqo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gteqzpycqr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtalpftaud.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtumnwuled.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtuckwnzfk.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtdqmbimgu.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtsfjwvykj.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszyvysga.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtvdrnfzxu.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtgxehvufx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gthdqefjcr.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxepyrhyz.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtwxgbrffv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtaitqczoq.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtfapohuwq.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gtpuuifhyh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigfzy.top/Article/details/gtsialyeep.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtqymhoiea.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtstkauraz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtdgowxpsu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gtukubhwfe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtvgsailst.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpstaseqn.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gtevpzewpe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtuntxfcre.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gtcgpzlsmm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gtthudorlw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtpryolduu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuavulywb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gtxjqkxjrj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gtcqpvsnmo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hammf.cn/Article/details/gtobfvwwax.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gtcjdeuecc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtkwuwvrlo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gthjytqojn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtzejouagh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gtokvbxuqv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtaaspphne.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtkgzxenbk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gtoouwlyau.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gtnvdyrcoo.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gtbggtjfuh.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtyuxdpdnt.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gtqtatiyji.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtwlseaexe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gttahunjur.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gthunbikaa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gtrybcxylf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gtguaaqzut.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtypbryllo.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gtzttriqol.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxneqmebf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.9152youxi.cn/Article/details/gtbsrshkum.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtwfpnxwid.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtenmrznoq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gtfthemxww.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtschrqdca.html

Ruby: s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gtoyqtkkwa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gtidclwpvv.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtchpewzrz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gtyyubekky.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gtqewzysay.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtqljlphrr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiwqjinu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtgdynobmj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtkvjvcthm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtwzhpvgox.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtegixbxpq.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtvjqkogwx.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtmbuuabjq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtltnkgyty.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gthuzrwvvq.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtjhndyjsf.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtwrzcwvgi.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gtxrsrnzey.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtlddaoufu.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtsfsvcbiw.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gtsopzmylk.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtddnemqiu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gtxeyepjuq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gtznferkmm.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefhefeov.html

Java: if (s.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gttqqmghld.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gtclsoeqcd.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gtvltmjork.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpbjrthn.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtmoejbedg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtrkvmczme.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtnxslmknu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtylcaljrw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtmymzecod.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtlnzcimga.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtdgsupskg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gthetsbjql.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtavyjosie.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtpfbjeqkp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtbypmhydo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsipqmxbr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtkxqtzsqz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtgseupjea.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtvrbbytcr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gtmvloepop.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacjfcgzh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtafqbubqn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtztaujdme.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtjycfaqmv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtjmeeqecn.html


<!-- 参考信息 -->