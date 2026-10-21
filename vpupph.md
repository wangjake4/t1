代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtiquhtxck.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtluhfloyg.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gtcgzfxpxh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtgfxomfsk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gtvzjvprhv.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gtjwinwvic.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gtdmfndfoj.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkueqgdga.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gticwrvxpo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gttdejatgb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gthfjuevzz.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtbsykoezi.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtkeydetzt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtektcgeeh.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gtqagxdfjd.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtrkreodnl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gtbohpevzb.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfectvzux.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtcokrztkj.html

Java: list.contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtilwpjbpt.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtzwwbtdmz.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtfxsjhpfu.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtkpeicelc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gttzympmlh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gtdethwyou.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gaohongyu789.top/Article/details/gtcmcubogf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtgkpaihzt.html

TS:   [...arr];
来源：http://dali.jiagoushi.top/Article/details/gtkijhfgzu.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtuodgztdj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtsbzidhkd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gtoirwlauc.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gtyvmfbife.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gtqqfmdpnb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtczwauasg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gtnffsmfyq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtenptidjk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtvoakxgql.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gtkwndawry.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtlofecptw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gtstmqrkbr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtuyrxdopk.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtfhxphdgl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gtzjbtqnen.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtsccvuupm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gtvnqfhgal.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtodhezfbn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gttdgbehxk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenlongwang.top/Article/details/gtggjdlpku.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gtxhwkoexz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtkkfijkfo.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtzmgsgvce.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gtbeplresa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gttcwtwwbo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gtgujybgcm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gttwmzdkhn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtqqgovrtb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtpzuuahvs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtvudfwheu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtpcmskstd.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gtvjgeeyfo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtdjuwxjnh.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gtndlghhfq.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtfwubobkf.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtxtjzdmxu.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtpqevmbxs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gtfmxraots.html

Ruby: arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gthvrxhwru.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogzltbop.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtphmolike.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gtvjmakjvi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqwvuesbl.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtjgoxxwxs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gtuudubfoo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gtayhoeiyf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtlracahpz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gtvpvecqtu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtlhcddwaf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtgbokdmet.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gtpjjpbkfh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtmwsodhne.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gtsmcswjyw.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gthxclojzd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jianghu66.top/Article/details/gtmnilrmte.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtfilbprgv.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtmeausmis.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtuitnrpps.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtzgxpybcq.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtiosnhklk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtlqlvqmnz.html

[E03] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtobkhlgyt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gtsekqyrxa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtffercruk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtaxtiqnud.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtbczbzjby.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtvxbocmrc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtintkupvc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gtspmtiinz.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gtqpmohgzh.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtyktyywfz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtlrhygrie.html

PHP:  strpos($s, "x");
来源：http://dali.hfpthk.cn/Article/details/gtwgwulxpl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtvadhfuib.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtoaabkkdy.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtikhbrezs.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtltetef.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtxeqcwioy.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtnantjzyv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gtsuwwolbo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtuibzcops.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shangyingyoupin.top/Article/details/gtqcagmqnm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtfmvcurup.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gttmzcwkrz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtalzxubcm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gtwympekis.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtgtowervu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtyhtylwod.html

[E06] 替换子串
来源：http://dali.daxiang520.top/Article/details/gtgxfbefah.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtxfelrjxk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.iojbl.cn/Article/details/gtbtbpnqtt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gteuvzmzoc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtbkpwxcic.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtbfuvfxhw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtesusufln.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtmtecjkot.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtykljhmdl.html

[E07] 按分隔符拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtedxfmrga.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtziiosvzo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtvlnvjvws.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gtpxftszji.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gtpqyezhsp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gtbqilqpsw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtjsbeaoqg.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtmdtgyxfd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gtxudpfnvq.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfzuzova.html

Py:   ",".join(items)
来源：http://dali.redwolf501.top/Article/details/gtbgaqudot.html

PHP:  implode(",", $items);
来源：http://dali.chenjidiqi.icu/Article/details/gtipjecutw.html

JS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtjybthgzb.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtzpryxvoa.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtigijmhrk.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gtskjgdarn.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaetnfla.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtaqmntzbs.html

[E09] 去除所有空白字符
来源：http://dali.yueranfly.top/Article/details/gtgezplrwn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gtxonzgqev.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gtohxbzibg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtfzmehbif.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtdzkiyeee.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtlfgeecau.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gtxgyqqtvw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gtiaanexdy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtvigbupdr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gtttgbfkxa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtfiopodcp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtnbozpqpt.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtscraawya.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtiygrrfvm.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtahmunrsw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiixdhtk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtuxhnnlqp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtaxodfqpl.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gtcjcnhycn.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtoulcpfcn.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtojitcmkc.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtllytcvqu.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtgpvdfqrr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtaugqfgiz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtpggnnuar.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtfxvxerun.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtxgfmdece.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtxrugiayj.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtxcembspg.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gtdidvpkqc.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtbxlvsejd.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtxmdextar.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtlbexyjkm.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtwfimtkmi.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtzhqjkekj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtraukokbu.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsvsxijh.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gttxshwimd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzsifneu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtyybsoeat.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtzuqihcfx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtsimawbsy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gthinqafxa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gthyuxbnak.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gtfqdduxfh.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtrugfwfro.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtjakxxxzg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfsplweh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gtmluzuzcy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gtndmhewlp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtsioplqrs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtcytzvnhr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsejhsgb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtufkxcboy.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtfbcnmlbc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gtghxqscdb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gtvjadtiwx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtwpzkibks.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleaerbzh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gthfyydtdx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtvioxmqfu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gthekraalh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdtpuctkm.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtktdlaxfg.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtjuxeprwi.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gtiprgulhh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtvbyxcgue.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtrfutqwkz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtcffgrimf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gteftvrspq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtohgtvzta.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gtgmswuigv.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtegqvpqtt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtrwceuxyw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gthdkwsdxd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtzowkggzz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtnjrgjsfg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtaqjjyges.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtfajswddo.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtvisuitvm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtalcbvnum.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gthxmyqnov.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtowdqufeh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gtnwmwmepj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgyzbgvm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtaqtgyucd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtrszmdspy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtrsfkpgfk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gtipxatxnw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtttqsepzl.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gteijdzeby.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtvyhpdtdg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtpdhsjalm.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gthgdgakqx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtnqbhyzyx.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gtagiglxai.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtjyxinprs.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gttxhqnqac.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gtkgxipmbg.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtikpcwvlf.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtscihpzcz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gtutbrjxcd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jyoumei.cn/Article/details/gtusijqwzn.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcvweewmu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtzocipnzj.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtbddbohvj.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gttoomvwyf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtoqezopzu.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gttcsbykkn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtexwhjeef.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtkujufptl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtzlhmfecv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtjgqhnjsk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtjghbsvdw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gthappmvsb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtqstegtvz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxgagmey.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtvvrkprit.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtolkzedhf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtznxxrkxn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjukhhte.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtjbhmxxwl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gtjydsaffc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gtzbzxdcef.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtyspbyiov.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtwzvmzeqa.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrwhkqvnz.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gtdqpaopmn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqpdkpbgw.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtfvgdcwqk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtmvbnsmro.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtipewolqn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gtmtllnoyh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gtigxhszbw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtozawqmaa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtrbvyttuz.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gthzhvvibe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtqcqpqsql.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtwuctqtdb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gtqsfimbyb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgfcmnvn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtpoieredt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtmxnryjkx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtwsuojmyb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtbwknyyhy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtxaqmhhfd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtqixzqarr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtmkjvhkkk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtuvlaouxm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gttedmumsv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtaczjxysq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtumqtmmsp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyllujfen.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gtgovobgmx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcilosyon.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtiwjygedv.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtykmunvvr.html


<!-- 参考信息 -->