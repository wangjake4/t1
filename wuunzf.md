代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2cdycxkbk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gt2hrcsjdfp.html

TS:   Math.max(...arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2wzmizizc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzsxggbe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gt2jmzzsppm.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gt2fpjpehsx.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gt2yabgaldk.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gt2ztnmaxqk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gt2cnlplqcz.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gt2vswjuwmj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gt2ijbxeqhy.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gt2lerusuqb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2ycbfrrmg.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gt2bckziemx.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gt2ozvuktog.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2sbfanjho.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gt2fqgajypu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2innhyygm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gt2kwcopenv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2uayjsqqd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2idfzhrzj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gt2rynsleqk.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gt2opzhsjms.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gt2fzvcxaxx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gt2butvjffm.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gt2ahljfbjw.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gt2xtjlgbxp.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2ahzjyvnp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gt2hpekbuha.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gt2fnvghodj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2defktcqt.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gt2fyowoxsu.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2sciwijnf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gt2soaacxni.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gt2unvaqczp.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2tephojvk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gt2nsetwvwe.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbdyibdp.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2qinurlfa.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2rrqvphny.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2bsiwoull.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gt2sdcgeuur.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlxcegcp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gt2lxvybcev.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gt2sxpacfmt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gt2woobrbym.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gt2fstsywsn.html

TS:   [...arr];
来源：http://dali.zhixingplan.top/Article/details/gt2eqixvvzp.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gt2vtllvqrg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gt2fewoctdv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gt2jhnzdeiq.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcrjvchp.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gt2fkruymcj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2vgmqqbvh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2zimtpzxh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2bxcqouqf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2bpztyedx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gt2bsibspng.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2nsssxcso.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyltavlx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gt2qarzqhha.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gt2yhrdmgmq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gt2wirqtakm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gt2uycmrxys.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkwzpenn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2wxswbgfp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gt2tpielztb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gt2lxbelpdp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cheryme.top/Article/details/gt2hdzeupzk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gt2pzgdfurs.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gt2knhnqraw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gt2pxokozql.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gt2tvpykomr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gt2dykubwiz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gt2tncwenio.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gt2ncdfbsch.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gt2tjahlhls.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gt2wqdxulfe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gt2parutoto.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gt2qkiwnvxr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gt2uxtuomhf.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfojcjfv.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2bmfnjjpt.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2rfvzqclb.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2hgzvrdpo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gt2sbxmivfv.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2lecmcoez.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2qqvopgbn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scsfsugj.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzyxyjvr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hyejdxrr.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2bygvzmxf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gt2mufrxxbk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gt2njyrouom.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2xbbclezg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2zxcwcckz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jianghu66.top/Article/details/gt2wrrnyijp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gt2cudgbbmf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivezvokb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2bpghxqak.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gt2griasdfb.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2smiolefs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2wlqbdkss.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2wwwlnvin.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2sjkpthya.html

Java: "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gt2rpcnzenu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2waiyxycj.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfnjalbn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gt2xkhzeuoo.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gt2oechftek.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daria6918.cn/Article/details/gt2zfvhygbt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2vnlveitm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2gysxvonn.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2uvigztxs.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2zvdtckmu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gt2boimhzxr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gt2blmsjacz.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gt2wmwtbuhk.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gt2odprlxgg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gt2jerjnnaf.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gt2swddylvm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gt2ibsouygw.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vupzxspe.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2qgmtjjnd.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gt2eyghwakk.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2sshbnzcj.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2nmqqomnd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gt2joxyxkom.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2tztpwsnv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gt2jvkuqoos.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2mbmyodrj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gt2natyxtfj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2mtawntbx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gt2bwhzggwg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2voipxnod.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oopajvxn.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gt2zqmhmonw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sweek.top/Article/details/gt2ejlakpxt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwypjeal.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2agjrktcp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2jwazaidc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2syijsrsa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2eomnnpph.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auimdhac.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2hoixkbyc.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gt2tzdnttnx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gt2zpwdtaru.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2cmouutzr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gt2fhagsfsn.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gt2euotgpch.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gt2zswkelxb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gt2lxutolbz.html

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gt2bfghigfk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gt2cnqgixux.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gt2kdgvxhfj.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tizjsgsi.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gt2eujglhuj.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2wmiajzix.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2lwomczso.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2tufruayk.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gt2hznqgsaa.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2vjzrorfx.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2gapvskyf.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gt2awkovujo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2drwwmdup.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2iukzbqfe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2hcccyqdw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2gjxpxekj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gt2axivjfcu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gt2gclyeglx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gt2cwfojnnt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2raiquxhe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gt2nmecsrvg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2yxqrzcbp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gt2chzxrxns.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2qiloelqn.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuyucrrg.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2klpjfddh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mixtbtes.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2vjhkcvtf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gt2ibfvxliz.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2adjeqqix.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2eqvyntfx.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2xqhzfprr.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2krdbnfxa.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2lzdmxfij.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gt2jegcgies.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2pktavdts.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2cizsslhd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2dduqeyyb.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gt2dlrxlczl.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2osujajzm.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gt2jubbeplt.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2dbnkpfpq.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfhuwpgs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gt2iblipjct.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmmfhxfq.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gt2kfwkjcrd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gt2qaajlkpd.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gt2rjfgnvdm.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gt2gaefaiqs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gzhubu.top/Article/details/gt2gtnxrcwf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2iqavlxvd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2womfdxnv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2pcojbksw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gt2wrkrqnxp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahjobbay.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2gqqkolpg.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gt2xdycnrqm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gt2sdgynowz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gt2krhrngvo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gt2pcfrhtoa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgyfrmjt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2uyhycqqi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gt2pifewqtq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gt2rcuodrva.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2toxdxwyv.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gt2riajhvxn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gt2qelgdxco.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2xpygxrqr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhdvvqvx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gt2sqpdggpd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gt2pfszsfks.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gt2ytsmydza.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2rwapkwav.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gt2hdihsgii.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gt2syheeuex.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2imdhgouy.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gt2obbefqyi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2gpaeyacl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gt2xuijxqyz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gt2gqvhaiwo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zgozzpvp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2sxjesuux.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gt2jnciejwt.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gt2xgzjlzbx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gt2ybjsgoev.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gt2twbuxkhm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdjzpvsc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvzqcait.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gt2iginjolt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2nctthyku.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2talhyopw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gt2dnllndmo.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gt2ovswczpv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gt2sohlumeo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gt2menehkde.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2mumozuyf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlbllvno.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2coeixqik.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2usvwonnj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gt2kidzaknx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gt2pswbcckm.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gt2maljwugo.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdqfhomu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2fbrtmfxd.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2wwziyspi.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gt2tbhlzjcb.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gt2vomrvqhf.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfubgwso.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gt2bonrdeau.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gt2lclsdnmz.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gt2tvdwnmuf.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gt2dcqaqksd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2kneqhbzj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gt2eifmytvc.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gt2jellvamo.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpyoivgc.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gt2umyknkmj.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gt2lftsrzvr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xziqi.cn/Article/details/gt2zdwmopyw.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gt2ciwgakcq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gt2vqbcewng.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2prfqvhzs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2mpwfrxdh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2tjouteac.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2ktcdlxtx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gt2cbxdialn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2okyufath.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejqvxdov.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gt2otxzjhzi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gt2fbljwtfr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2jzhutjvm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2aieyplja.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2zbwpnibs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gt2sxntanlj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gt2fvubqkfz.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2tqkgsvqg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2mcfjhsmh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2gaozwozk.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxgszwzy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2oddahgpo.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gt2pzppqutk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gt2sxulssnv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shtlenvs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2yilvqyzu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2lwgogbuj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2qtzkcjtx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gt2gppojirl.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2twxnkxkd.html


<!-- 参考信息 -->