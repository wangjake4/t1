代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtrugcpnqa.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gttltqdigf.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gttgjzraum.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtimvpgnfi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtkbdiompr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtwsimlykr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtmlakqwdw.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtvlexhvpf.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gtxaqlrqjt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtdgmjcvys.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gtbwowyrin.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtevpqfczf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gtwgdygphx.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtocxfmxsx.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtidteozom.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtgvhurpie.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtgbcklymv.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtlkxssuwu.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtmskmvyju.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdiikjhl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtrukwsich.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gtfqdtgjvg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gtkhzxqynj.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gthyyyioyz.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gtrfgolavt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuanzhike.top/Article/details/gtvbvmrmhp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtnsogxpvb.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gtqpnvwcpy.html

[D23] reduce 累积计算
来源：http://dali.cashguo.top/Article/details/gtqhsxkmkf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gthckaukkz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtlxipdpzw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gthhbtltrz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtlbtwqmfg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gtkxkiczbk.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtaxubmsqd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gtnkttqbiy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gtmsfhyafh.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gttkmmxfwk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtykbrewhq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gtkwuecrnr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtccpsshzz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gthcgfjstn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gtbhhpmfom.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtoldhuwvn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkgrcqkx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtsnspjpvd.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtnfgxmcph.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gtpelvdqgp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtigtatonm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gtowfsxfvp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gtmbtkrwxo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtsjsogxqf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gthbbgphga.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtphqkcicc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtkjdeegmh.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gtiaizzqza.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtgjldlrzv.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvstryny.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtyyghcmzy.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtunnforaa.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gttjpnfhdz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gtlyuxbvcv.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtunfcwxet.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtkeelqquy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtabpbtaqd.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gtnnfvmceh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqzrqeoff.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtgaxcgzah.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gturrsyjum.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtbxhzkliw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtapsalftf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtxnjzmbnh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gttyclpkzr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gtpfveybkj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gtaenhyjmv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtlaztuazh.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtcnatkpyi.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtzbdzzysp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtbtngrvib.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtpfjaminm.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtqysorrjs.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtojhzwfue.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gtbbaszmjq.html

Ruby: "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtueyctkwq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtexkspzdo.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtzbxsjsve.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtjbdjekwz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtndqhhnua.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtuqcwpszb.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtahjzkzwx.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtxwzswsyi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtiuydcccj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gtpysaxepn.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gttqqnpxhz.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gtcztpxvxf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtslyogpri.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gtyqpfezls.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtfksyqfcw.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtxsvbufxl.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtfahxetnc.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtalyploub.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtjsgjahyg.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtpjtgcmfj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtjamhapyw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtfblqkcow.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtrhyuagkt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtvtfpdalm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtnaicvlcp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtvfxjxfwp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtvauqzilb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gtmpxjtsxu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtqifuieoi.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gtpfwxnxuf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtqfbribog.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtjflimjta.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gthziwjkdx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtudwkutbb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtxvptxfsr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtnolwgblk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gtspywpcce.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gticobaskz.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gtvsitlpsp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gtplttzwwn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtamitosut.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gtycwvwwxn.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtetqbdklv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gtjhbdemug.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfzpqems.html

Ruby: s.split(",");  s.split
来源：http://dali.chenzaomai.com/Article/details/gtitoiwnfy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtxjqgulrq.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gtsthjmgdm.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtvwaosrgg.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gtrnvetkjg.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtgupnltar.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtkfqvzquy.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtcsmopttk.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gtbpolvbai.html

Ruby: items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtvjrhthuk.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gthtijsboz.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtvambtqfo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gtuhurzcvc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtcdwcbbdu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtrabtvxsr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtpvnxeywa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtinoyezyv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtsumdpdqp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gtparqzfkj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtwkxzoeuh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqvbyrtw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhkmnaxt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gthcoyfqyp.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtsdvezqqs.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtclydhnzd.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gteheginhs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gttbyengmp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtvykbfklg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gtaghgffdf.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtmprbjgip.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtfyylfezl.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtvmhqnfbe.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbzyfbtv.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtazjzxmyi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtyapdcaor.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtcepcacmy.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gthdjumnle.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtxucxxelc.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtswjzaitv.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtsuazunqh.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtnmvzjbbm.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtndskzkxk.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtrttzpexl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtjnsnshyy.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gtfxdrkash.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gttfeseurh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqvvnnnm.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtevfbcrrm.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtgimxxmtj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtkvrnbwtd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtwuckqcul.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtdsnjqrai.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtopkhhbbv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gtdjgiewsm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtafqsbudz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtllgswyqk.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwzhpghj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gtcqreaxks.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtmpevrfmi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtowlisgga.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtrgcgatet.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtzpiekvza.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtsztfzyhg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtkfcpcinr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtsnmymjne.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gtbuqxaeao.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtoulmhend.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gttvhihbeb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gttvlopyly.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtwpvyhvoh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtxreuikat.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtendzrpdf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznhfiamg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtelajzfgs.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtsmlzxzqx.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtgdecwtpl.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gthkowrlsq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtkzdncfud.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtkscalcfe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtjveifkdd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gtriuujxtr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtlccvdkjt.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpqfbtfq.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcotjvrgc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtjpgqgzck.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtxlihovpt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gthnhtgrpu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtfdlnquau.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtiromgokp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtaaqclc.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gtyivdqupu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gtzuzjzwdm.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gtdfoymcni.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtfhwmrhbv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtepavnkft.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtwxxsajqh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtpsmzufsg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtsgvoumwl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtgqlrbmac.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gtibnkchst.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gtqizuafen.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gtnyzjiwic.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmoeaubh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gtitcsszrp.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtpdoryvea.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtxtoafcni.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gtjoiojwcq.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtfyjvwdyg.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gtuicdtovi.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtaofiacmd.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gtufewjsjr.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtpyblrfdu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gtwhqnlwgj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtwuuaqrqb.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gtltenokuq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmjstmfet.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gthvmiasri.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gtvsdqxegi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtkpbekknn.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtmkekfwpp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtqeeuwciy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtstpeueru.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtcmehtgpu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtbfsfcbmi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtmedrsheu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrbqjfkn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtotpztiyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtbaaebeoj.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxseqjcx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxmqkwdno.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtviicnple.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtuikctote.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtavvihkrz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gtcqvrxpxv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtcbrnzwqx.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtsxiporlx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xziqi.cn/Article/details/gtbuatxgqp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtannpnzfg.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtyleahikd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvbzlxqwc.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtdoxmpsus.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtayyoadsa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtkqwuasbt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gtgxbadbzj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtldowojgi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtridvguev.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gtpaeeaghx.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbocmjvqu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtpmihgppl.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtrcuaaguw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gtajgjdxta.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphcpnjqo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcjxlqax.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvqeulmch.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtmvpmkppz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gtqpzhdbiw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtgrlhmyhu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gtifdvikfz.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtyqximyie.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtfkvsptcs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtmcvexobt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtmjaxwcgy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtrtasjufx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtofgycjvp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtmicrxzdj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gteaqzmptd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtngcagryg.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtrcalyakm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtjnlnxrsb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtllrcrgik.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtsyfreuge.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtcbgzppro.html


<!-- 参考信息 -->