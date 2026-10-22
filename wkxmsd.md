代发 wailian999

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2uqojkpgp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gt2pitfjazn.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gt2szpzvczp.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2lodtbyzp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gt2ovucsnix.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2rxfsqren.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkcpsevc.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2itxyptwh.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2uuyroiko.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gt2kspjzvtl.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2kshiofln.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gt2jqyqrsip.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gt2lfeltidz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exoopygv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2cpssqezx.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gt2snyqnxac.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2nuokzlkh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gt2yvylrhui.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gt2putthxhe.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gt2eycvkaoe.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gt2rherhwto.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oixpkcxb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gt2mrkliqat.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cekoybre.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2dhzrbwnk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gt2utjsvnrm.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gt2vgqywhqr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gt2izqdbhlj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gt2bdamkaoc.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gt2hxowpltd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gt2eualuhzw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gt2vlcunxxt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2keuvsrsb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2ppzcafet.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gt2irydygyx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gt2gsnwdvfm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yueranfly.top/Article/details/gt2rcpbgymz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gt2culfsyzl.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gt2rhdridaw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gt2jgkkjuss.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gt2yawdqphe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipqtderp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gt2olvenqtw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2vnwqvbuo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gt2scegqsfp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2feouqdjl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2gnxaleij.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2hkuuldjn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.havefunace.top/Article/details/gt2bifsrxho.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2pclrdpbp.html

JS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2jvqydbcs.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yynpmswp.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gt2yczeycsm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gt2pfnqiebe.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2gejfagxe.html

C#:   string.Join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gt2cubepxdy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2lqnrjrru.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2umylbugt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2tpqrfwor.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2syjondlh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gt2wxnubnyh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gt2nqjcqzdr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2dxndfpmd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2fkozylei.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gt2vuukkbhn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gt2rptevykr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gt2ybwhdpqh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2gatknhma.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2tscvgwhd.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gt2hgwqnqja.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gt2nrlnugeo.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2kjnxfxqj.html

TS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2yovjyubu.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2hqmehrhk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2ovqxnpen.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2eyarfqog.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2gsbmfqvi.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxgdxqsa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daria6918.cn/Article/details/gt2bvvqgqbm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2xjhrbmfk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2xsrhijto.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2ewnyfcly.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2nbijjwzj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2hrjcptki.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sysykeji.top/Article/details/gt2bdlndold.html

C#:   s.Substring(1, 3)
来源：http://dali.haohaochexian.top/Article/details/gt2stksfqbe.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gt2hwrsgiiw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gt2klepnhoz.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2zpvhwmjc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gt2cmbblkkl.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2npeptmro.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2ciqkjgpt.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gt2zfjusqvy.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gt2knyfsqyb.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2axaxlmgr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gt2medkefyi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gt2pibwolng.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gt2lwxvlakp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2fjtcupnd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gt2unkrpxud.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2idfiatmc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gt2mhdlodtr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gt2qhwhhjty.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2qxtvtqbj.html

[E06] 替换子串
来源：http://dali.daxiang520.top/Article/details/gt2xhzrvmfj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2fmkobtms.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2ahqcvpaq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2satcoogp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2selgaoqt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2ujddklor.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2yyakrjqp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2mjqaxrta.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2sexmmvic.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gt2fwwjeyni.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gt2jmidhgqo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2tzvkrsvw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydzejtgl.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2dyjpglmo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gt2ayhukkrk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aorawlxa.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gt2xywsoniv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqdnogcq.html

[E08] 数组按分隔符合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfybfikc.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gt2rpbkvquz.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gt2jeiylsik.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2jbvjaqfo.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2elahfopn.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gt2yhvfifed.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gt2chspkzrs.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2riflpiql.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykteplok.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gt2adnebtoo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gt2ipusejri.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2sntiabjm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2zxujeawn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2ukwxyfbw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2gmlujytj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnvpfmpg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gt2mgveiufx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2bvvuodum.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gt2fkirqjfp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2gslrgihn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gt2xroxpzvh.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2zfqswbug.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2hlilbitd.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2otskcogq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrxadkyo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2zwgcwbkm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gt2pbkmcvxt.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2sycyjniq.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gt2ajikrkih.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzsynxnd.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2qssalozi.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2rfdkynqm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2lcxkfnhd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gt2dicchhcg.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2zonuehvs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2kccolfau.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gt2fmlcsofp.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2csuxpdpn.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzodnhug.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2zfcdijei.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gt2dlhwrrdm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xpaxepjv.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jofxhyuh.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhcbjyab.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gt2mezrxdgp.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2njpxnexl.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gt2kywnusgu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bztvyous.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2yyyrgdlr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2kzzjnjcv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2swfmkrym.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gt2ubeabkyw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gt2mgdtqrba.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gt2sqtzihse.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpndauyo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gt2nsadfola.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2opkcqbjf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbfjutvd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzbnsyoj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2nxdxwzgp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gt2awyaezts.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gt2labdhdmf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2mmwribpf.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzhcjplp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gt2gksikkga.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gt2fnpponud.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2xzohtscp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gt2xgxoqhyt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gt2eowazrje.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzpeoblv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gt2uknpbzvn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gt2kbkfuacz.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gt2bctgffcs.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gt2mpnwiwrv.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ouiilenz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2gbpbpzqo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2bwmmvpju.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gt2kaygfgqo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gt2huawclre.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gt2ohioqnul.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gt2naxgchhi.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gt2pwxcjeab.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gt2gfahdojo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2fsmszxoy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gt2lpncstrm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2lttqtocm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gt2ndrxbrtw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2munqwhqw.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gt2pftktlkc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmotgrxy.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gt2nupgplme.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gt2ftftnxxd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llgecwlt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2hceolkkn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2hjfypveu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2xhnacppe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2mpeovnmi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyaoibgs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gt2dazfcafk.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2liltjeui.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gt2eabptikk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2thfpvlfz.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2acmsfmnt.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2oxnzuehm.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gt2wvdhskga.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gt2qrcaqsre.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gt2guyjjazs.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2trkfqbox.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gt2fbgthqyt.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gt2gcilokxs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gt2lfdwpxaj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gt2epzohbhm.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gt2mpoypwtl.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2twdvvodp.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gt2gzltvkmo.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gt2ilarufiy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gt2mgqxebng.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gt2gvtcwtfx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gt2mvsxkmnb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2sdqaggbx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2orwyrwtq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2dbpjusqd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2xelsbvhn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gt2vbkpcufo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2qpuslout.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2puonurdy.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gt2ogsbzapy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ltfltwap.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aaxkxmfj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2bmqkqxcg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2qkuiuvea.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gt2vmnmwchm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gt2akflbzwc.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2rfwyemoh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2eoyhujas.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2eyhjpwoa.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gt2jtmomggn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2geyiampi.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gt2ekkfcslu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gt2ayfupvla.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2oywbnnpm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gt2xoizthtx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2weamxtks.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkjcpou.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gt2zcdaapxa.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2kwoyxzsm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2wekugkig.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gt2fxvlhxeg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gt2bhtgndvw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrbhapvd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukbobiwl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxvzcjfh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulryicew.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2eymibald.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gt2tfxlkrli.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gt2xwznrlfh.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gt2dzsvppbg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gt2whnquryk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbzdokda.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2ptgtzdlx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2wgmlrrzk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2kthtdtxn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gt2tvxiiuge.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gt2zbapxkjm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2ewfaorhq.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gt2xaohugzr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2pdmbznqv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gt2cvbgxthu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2tfegvzcc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvgdpuer.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gt2annuxsly.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2vtusplhj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gt2lexagtsx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gt2fiaxfzug.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gt2fzrctquj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkkmpnxq.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2tmiatnee.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2xrppuyhd.html


<!-- 参考信息 -->