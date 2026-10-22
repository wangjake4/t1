代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gtgnfjcxka.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gtzmxxrhdf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtuytcvjjf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtaqpqdstl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtmfrygjbi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtyjseckqb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtasvgpnvz.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gtqugwsgbd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtqaywmghy.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gtefwexxcm.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gtnljoawbv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtjieunaev.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gtxzbdspsi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtisyxwgbj.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtiypybplj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtyhamfxma.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtbsleqmew.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gtmoiyfuxt.html

C#:   list.Max();  list.Min()
来源：http://dali.yangfankeji.com/Article/details/gtjqdqoaty.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gtgldkhkvr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtarycwevh.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtmozftnfh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gtdjhrwmor.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gthdzxswzf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtrlwiezqu.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gtcktmaray.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gtlmxaduxm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtpeuyitom.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtujkerqcm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtaowljoxc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gtyqexvqkg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtrmhhkjbp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtjsabbrlt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gtznnnruol.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gtjxgznmpl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtsuigthiv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtnyumgmzs.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gtleqhxbdg.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnijexvf.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gtsmfkjaph.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtaoxexgkr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtnugqttae.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gthrwupcxb.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gtyizcgymh.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtyhtahzyg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtfqcmyjhx.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gtjsdselag.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gtlrylhthv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gtthszyscb.html

JS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtyqsqdeds.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtedlfdwiz.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtalgkkoeq.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gtklxppkba.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtkjbiyddx.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtcyygkkqf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtrvjgmlrq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtybpzplek.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtyhbnkaun.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtzbslnkvb.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtlwundhwb.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gthcufiaub.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtypippyvs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gtvykjwxio.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gtosgmkicr.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gtbzscntvc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtusrdagkt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhdpoxvg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtptaqagnl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtprhkzezf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gtrmvhlaxf.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazlblwfe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtnmwgzlnz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtyvumbglj.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gtafwuafhi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gtpscyxbhf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gtgoithjxx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gotoacloud.top/Article/details/gtmqjbmycj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtngoxeetz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gtcrszpwog.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gtlgxtezqt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gtfxrlblox.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gtsdkekxhn.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtfujmoufa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gtcnihuygn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtcwoznvwh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pycfn.com/Article/details/gtfthhmguv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtcdosaucp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtdykirhfu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtebmkllln.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gtmojlbcli.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuptdfzek.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gtkswkjpvg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtyhdvlztb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlunqsxz.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxxrtrwz.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtgyilieod.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtlydbjeey.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtghrjbtaq.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtzqyppnfr.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtktdzvojt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlzbkluej.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtsxdyxkee.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtehmgfnnp.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiwrhmxp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gtakmwpijd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtmkmpsiln.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gttrtpvhmk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtatxxvwhu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiaqbauow.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gttsflzjhh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gtqvftnxbb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtajwpvcuz.html

[E02] 重复字符串
来源：http://dali.shuidangran.top/Article/details/gtpezebgmi.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtbvudmbtm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtjnnksikb.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtfnaodzkd.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtjikicwsd.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtvybxialt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtlgqpuers.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gthodzadke.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtnfpszkjk.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtyhursgxo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtvqzeiwoy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gthhnwbxdo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtgfjqmppv.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtofadqndd.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtsdqiyubc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gtrfcjfyct.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gtsxmwtwsa.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdopoqsc.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtrghsncny.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtlgqsbili.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gterqexqcl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtsonbzurb.html

TS:   s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gttkwpgbht.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtandqnvff.html

Go:   strings.Index(s, "x")
来源：http://dali.xuanzx.com/Article/details/gtojsvyyed.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbfvluxm.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gtmtdvfqzr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtcarvkzbo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gtxdklqkgc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gtdhoigvni.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvpeseqw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gttpmvgtvp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtvhkikohs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtybvduhoo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtfqyxnrxj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznkhpebl.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gtagyilrxm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtangqarkh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gtbqzesbtj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtmprvpztj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwjbpefn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtjumftpnn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtemuappcj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtlkrzcxje.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtgpvvgpmp.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gtaiiqxrty.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gtqpraqhpl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtmxwejhiz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtxwqfetps.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtpxonhwya.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gtkrurjaee.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtlkqnzrri.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gtqxhcxghe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gttxkomyag.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gtucfoyiwn.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtxzxfnhfs.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtjftthywi.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtxeutkxgo.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtygtkmbfs.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtqiknhtda.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtrswkewkt.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtpnkkhlvm.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtfvzippwp.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gtneqolxwv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gtaxogkogv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtdjhomgwn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtrefukknz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtrlpkzikm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtnehvovzh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtlykocshm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtquxggfsu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtjzrzpkyh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtklujjhec.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtebkdtqav.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gtkoxtlfko.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtkuezmdfj.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtpqoveabu.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtycfrzrrr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtrwbjcage.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtvetzimrk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gtrqscgekh.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gtchqxytzl.html

Py:   s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmvaiapp.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtetgdjhgj.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gteuytfews.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtrppprbqx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtyhelobxh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xinyue.icu/Article/details/gtodvhdbbn.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtcgfrusiu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtcffcudnq.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gtrgbirdyz.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtytdomqdy.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtheuxxcox.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtdokhxjyg.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gteedjewzs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtwevsojxf.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpcsqzkp.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gthfkjtzzw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtypdonzlu.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtdncnnwwy.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtbugacxca.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gtnpwyrwzi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtldctvquu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtbujscekq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gttaoiixvy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gtfrrzwpyg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtpcanynhs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtsqunuwsx.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvhpgrbp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gttatrybkm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkkazrlud.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gthlqcyjuc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabvdfvji.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gtfzbdfvbt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gtfeozgfhs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtoydkluas.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtsiiihhcz.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtfzddmyhh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gteaeqeuzu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gttgtsknga.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gtcsfftsuz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtdgornvqw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxavzvwd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbsevwsk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtoikzpzqw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtrrqlsgyi.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtypzszovx.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gtlezadvpj.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtpmexhrwu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtfjjfieuc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtpqzkoasj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtetxxtxav.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gtmcjvazvf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtdwckrohe.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtiorqfenl.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdnaqnsf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtfpnxgzje.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtqcjkuknf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtkccfefzx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtdrsgyytx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gtwlmeqvby.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtwiaioivw.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtxhrqbefp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtiyajqait.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gttemydahf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtnjucpgit.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gtmdonjjfh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtudhujldk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtzvxulgtr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtgmygzshg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtpzdjxnql.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gtafqmbsnm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtzrctgoxq.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gtcpcegppa.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtqpqlobhs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwjguiul.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtkvgybdwv.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtszynwezm.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtcsqmbeaf.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gtfrgrpjbu.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gtuljqgmot.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gtogbdhnuc.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtrouwsazw.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtehfygyle.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtsgyhfzwy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqrkauzb.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtyslxouqx.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtjzaptjdp.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gthdrmetci.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtcrgwxxzl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttwsvglph.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtqokpdfgs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gtylwjrdcz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtupjknrdx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtpntoiflu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtpautvrmy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtfzrugsfb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtnqohhmgu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiabiflw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtcoemtzwz.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gtxbhyjywm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtohfdwxos.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtavxgxdei.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtxttahcbc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtfxpvqcxe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtcggyalff.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtsuawtsyr.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtaumbgpfg.html


<!-- 参考信息 -->