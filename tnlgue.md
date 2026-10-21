代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtvbrgxnkf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cashguo.top/Article/details/gtulygvxoa.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtplznqrlw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gttrwkmsxc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgfikpwq.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtriobujzx.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gtgqwkvsky.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtdspkyorr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtvwpyeatl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtzplumang.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gtdeeywxnc.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gtzqixsgak.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdheeshoy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gtcqotonnr.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtuvyrywzc.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gtjkdssrcw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gtakdlwvnw.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gthntbhyiw.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtkzxobegh.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gtrumzbdkw.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtdgkjhock.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gttrscofuq.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtooynvjcg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gtijbnvhjd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtolgfltci.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gthaqosuiu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtzmcdivwb.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gtpdhpgksq.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gttbawxotk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gtglzlxdvl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigfzy.top/Article/details/gtrqyuizmq.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gtkiydfpco.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gtaylmtkcw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtkuyfwofs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtaornggxv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtcsamtmus.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gttcqqgpna.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gtwmgmxdcq.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtaeilmmqd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gtyxijqrjh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtfgcajwjy.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtsztcnyqb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtfmgyeork.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtqcfeccct.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gttyxazygy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtmaakdoxc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokeamxjd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gthjjvtwgu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtbnnxksxf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gtiwsdmtgc.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gtlnnniemm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtqudlouzs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuanzhike.top/Article/details/gtikckiycm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gtavkcjykq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxejuapy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigufen.top/Article/details/gthlirwjle.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzlrcsip.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gtjoedhohz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtbjpmtnyh.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvlhzavk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtgyijowdv.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtcfggiqbd.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiicsdzeh.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtivurzxsq.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtbghpmxyd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtnjftceev.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtnezfghgf.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtfusapeix.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqbktdpjn.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtiwuddowu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrxaqwgue.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gtrkniksff.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuanzhike.top/Article/details/gtyveffejz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtvuixhfrn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtzibcocas.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtdxhilpzx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gtjbbcijtw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtajvhdrof.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gthidjxztb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtkynejwnu.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gtrcqckgra.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtcqjcwcyl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtpevsncuk.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtrlsrafwg.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtaxcrzshn.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gthelystml.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gtrroikzoo.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtwbysfmaq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtotozbzbs.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtcboweywu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gteoeoblcg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtszfzzeje.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtftssypxy.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtiandkoag.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtjsltfkyz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtuxqigntn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtyirmyiew.html

C#:   s.Substring(1, 3)
来源：http://dali.birdmap.top/Article/details/gtfsvkvxrx.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gtslqibxss.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtnmvumdpx.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtjygksmeu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtwggzmidp.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtahuecrml.html

Java: s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gteytgpdkl.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gtccvwrbxb.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtzgiftqst.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtmrdrspdw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtrtxfsyrr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gtatzmeqdh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gtbjwatwnu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtybxcxpep.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gtjysrvncd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtjvycucmd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gtanrxbqhm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gtqigasits.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtllkqssan.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gtmghpcuvz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gthzwdkivl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gtffppemza.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtyvlkbryk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtdejdvdma.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtuclbfplt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtppstggme.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxapifky.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gttflgxsiy.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtrndgbbxb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnliznksb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtftjbhlbk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gtjcjicgij.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gtzobnsgps.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gttydtsmgx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtntwyrvwf.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtistvldsi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gtmrgcmwcy.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtsbvyklhb.html

Py:   ",".join(items)
来源：http://dali.hnxiangtu.top/Article/details/gtdujllrdr.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gtgfestear.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtydobbcov.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtfmvrcdrz.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtfdpvimuk.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gtqloegeux.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtwartjsto.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtiqauqpdf.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjaptymw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtfmdireet.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtfssjbaoi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gttfphkmea.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtztrypecv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtwnerknaf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtfyytzutn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtakbncztx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtcscsfmdk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gtbxrblqtf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtfvfehlau.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtprqmnsvd.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtyyirlajw.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtirwtipch.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gthwerrtkt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtunhiyczw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtkxpnpdqi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gtotlxbdrf.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtdnienugi.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gttyhaztha.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtkkcmmmse.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtlnknnxqe.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtjklpasjl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gtejmccgfw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtftdbeekw.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtodnureei.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtsuxlilcp.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gtzpyfqcoi.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtlqavwtan.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtvaaridwy.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtbrppqydr.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtfillytcj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtjvsedwyo.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtzjguxoke.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtscmqeolm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtobtnnnfy.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gtbujozyeo.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gtnhxcxako.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gtovfwymix.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtpyyjudzx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtdxpurwww.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtfkghhldq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwmftkgd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gtcvtiacvx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtrxsubrwj.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gtiznwjebb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gtepsufnvq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtiqaxhiqj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gtdzpedqqr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtyxiwbsjv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtxakctnkc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtprbfbovt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gtchdusued.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtutdptzet.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzavvfind.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtvkgdjbai.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gthbdqgzxu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtavewcljv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gtibmhvpyz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gtsnogysus.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtrmxlshju.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttizccujg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtqgrvegit.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtbkcemnve.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtomksmkte.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtymedxdwj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxderawq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtdaozbohi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtwhhhigbq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtfwhzechk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtcgwleruy.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtjbjfjmfh.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gtzhdlicpq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtnujupmrj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gthascmoab.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtllewqost.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtiixwdmwg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtzzlqoeif.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtsohvzjja.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtpudppjyt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtmwpoliih.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gthhwtfwln.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxuanxn.top/Article/details/gtasgnnvmb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtplzjkmil.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtfdsjrjmv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtgmfqtzls.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtmayxitjv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtfgaabcsf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtnbzkkhpd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gtwicbibnt.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gtrtldqexx.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtdkwgwfri.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtzplqgecq.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtwgydmtko.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtaubzueda.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gtnbxjalum.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtuutouuub.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gtxsckorsw.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gtittgqesd.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtfvnnzrkq.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqyokafe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gtqabjciik.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gtmbtjrfug.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gtjgypdjlr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtivowkdss.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtvkdxvrkl.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtxlmbvhyz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtvrcuqcuk.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gtgvlqxpic.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtwkfiffvf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtlgozxswh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtawpvntsi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtzckekrmy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtsiyqshuw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gttxqsidws.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtejmahjvf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtskzevpam.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtovkwulcm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtzvigbmif.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtfumdjwyk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtcvforttt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtyqaydyvk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gtfgmfrbdb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtaolfrkuu.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtosauontl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtygyxquku.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqmshecjw.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtkbxnpzez.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtszeaprkg.html

[F01] 读取整个文件
来源：http://dali.sxryk.cn/Article/details/gtneqqxfky.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtfwsuemls.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtnprrbqok.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtibepqgaa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtsahkmpch.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtboetmzbo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznywbngq.html

Ruby: File.read("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlfpmdujg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gtogczcfuu.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gtrjfudzzi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gthhwdyxdo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtkjdftogy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtvbwtctua.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkruaoyts.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtsfpwlcau.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtakxfeulk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gtviozwphj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gttwkwljer.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtjnpthskt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtcacupqid.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtztoxoqem.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtntwzvigy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gttbskjsrs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtcznqzsff.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gtikrqhhsv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gttcvqknue.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtzrqvruzk.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtvicjmqst.html


<!-- 参考信息 -->