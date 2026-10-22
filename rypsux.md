代发 wailian999

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2anmjgytc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gt2rtvvupfn.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gt2ynseeloz.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2sjxfowdq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2hiiazhdj.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aknaqfvu.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2epydglnv.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2urwtsryn.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2pcfzdqdi.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gt2rqiygzui.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2egdacsvx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gt2nrywxkli.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gt2mdwohceg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gt2wupshzku.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2asgjfcxn.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gt2zzjnjwln.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gt2mlwrnbxl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2vuyilegc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gt2haedyarh.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gt2zohwzgyl.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gt2mifuqylo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gt2jqdweach.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gt2djktuoji.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdefafil.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvnrofws.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gt2kdicflul.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gt2vbwignph.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gt2ekdwcthn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wuvdnxpm.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gt2wkyiwrhq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gt2apxweetf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pogsgibe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2kgqtdgzw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2hbxsmegr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gt2wlphtnum.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnssejtg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdzpmsst.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gt2unkbxrga.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gt2yjemsybl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gt2soovmyxz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfmtvmig.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2kbfshwmo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gt2nzijtyys.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2jlkuxbkm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gt2iaighjjx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gt2shcvmdwh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2vxdqxovr.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gt2pxsqyezt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gt2mecwehkw.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gt2vkjdqcsh.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2jndsnkvy.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldipsepl.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gt2amiooffp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gt2nofnxkoj.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2wdzkxgnf.html

C#:   string.Join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gt2zoenpkod.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2dvrgpfpr.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gt2pepjesvv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2muwmelke.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsskmdst.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nflhvwzk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gt2olvzjold.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gt2oejkbitt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2kbgtlgbs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gt2khlhbpsx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2wkfcrzdg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxinkj.top/Article/details/gt2xqeoijzy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2bmoitzvo.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gt2buthmjpj.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvpeoquo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daria6918.cn/Article/details/gt2byhynhte.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2eqiiwojo.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqyzvvjh.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2zvljyiqr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gt2azxirwgn.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2ellasrhi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzzxstgr.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gt2dalyecwb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gt2vzdferdf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2ywgxsawg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2wmsxkgrw.html

TS:   s.slice(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2apypdtzl.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2iiagyhlj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2cpvsbisq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gt2sgfjwjhx.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffernpcg.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gt2wrbabztw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snudbine.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gt2yaqqjibd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gt2ykyjiwkl.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2vkckvexn.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2lcvspxaw.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gt2pplkzoad.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2eeqtzqjl.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2nqcbrani.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gt2yithmfim.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgsxprit.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpopcpi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2qyfjxpka.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gt2beodtnwi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2maaqcvav.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gt2wyhygiak.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gt2rsfqwpwt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2ftvffdpn.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gt2ufzxqqao.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2hqujkuyu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gt2wwsrjbyg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2ucjpkobf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2mxudhyzh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2ifzjdfkt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2iexjslpn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2ovwgtakn.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2sectuvas.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gt2qazytsuc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gt2hkqfagfi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2urshokds.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gt2mvlafnua.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gt2jnevuwqb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gt2ibdxigxu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gt2njhsijxm.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gt2eoywmysb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gt2oijqksme.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gt2zulrtuli.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gt2kfnlbjht.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gt2pjiwhqbc.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2yixakuzx.html

TS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2kuhrxdxi.html

Java: String.join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkojjpyz.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gt2vdzziclj.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2mrzrfyly.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2kvuvobws.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gt2qtxjbsrd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gt2dsivopye.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcszijav.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2fgupqmfr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2rgbveffi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2cemnlxqd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gt2cegsbixh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gt2noxjhaaj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2vrjjeqob.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gt2vbrhldxm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2bfzoyxys.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gt2vnsmwgxc.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2xakztmeh.html

TS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2snjwdcqx.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2altzopfr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2keofqlsz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2gserwoza.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gt2wpdqbghp.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gt2qmdulrvo.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gt2engpbrra.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gt2smpjfmfh.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2ufddoubq.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxsmukxa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gt2apyvqorw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gt2sauiqkcp.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2jogomggb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jptchcvz.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gt2hurwjulr.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gt2sbpcbhgf.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggzvnqpn.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2dtiyoyck.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2hyuyztnh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqdgjogp.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gt2pevkxaqb.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gt2auwrxmvt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gt2wtrrqarq.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gt2rpeuakmi.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gt2wvpkjwkf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2wvraooxd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vufpaflj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2ndrdokcb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2vrsrvnwl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gt2fisvvqhl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gt2agvnlkhy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gt2qdixzhev.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gt2sianbgcc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gt2ilbdzhqz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gt2hyjntund.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gt2vncumivy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2mdtupybw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgcsmtyk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gt2umhxjuyo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfhssgrk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2neirfqvw.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gt2exhgottt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulhqhovk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gt2wugkfqkx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gt2lhylfpwr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gt2oxmbrvss.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gt2bzlwbgjz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gt2qvfhwgkj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gt2nfhhshmx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2melyatqg.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gt2qjgbhijv.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2nzrlfcvp.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gt2wmmjafdh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2nzcfsqvb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gt2ktthmbea.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gt2znxysuog.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gt2drdouccb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gt2imfixkjn.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gt2kgtlqajs.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gt2ylcuswkp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gt2pxjxhxbi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifjlmzmz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2vfwgmeom.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gt2dtqjrzkg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gt2qefgfmgh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gt2iaelfkhw.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gt2eomatugh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gt2ujslblbj.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gt2rigsejjm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gt2roztlnua.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gt2vnbicfiu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2rwvuinjo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2yndnwmjc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2axzqpbrb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2ixokdfon.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gt2uxjhrbrc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpspgawv.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gt2dmzlsbvu.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gt2uigmzrkn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2nohselfl.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2ryjjqgdx.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2thvndgkp.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gt2kypnaeeo.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gt2xselabbs.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gt2btzuvsvr.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rragrfnd.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gt2yesrwkdn.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbcacuwu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eonqjtni.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2fqrrlkbp.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gt2pfzuijuj.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gt2qtozxzsq.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gt2ynmekxtl.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gt2azahzyez.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2tmmggctq.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gt2whfyltrk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gt2mysfqtej.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2mpbarrpv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2sarbmsuq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2mrzhjbin.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2bwebfgqs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gt2zsztevrb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2mmsaruhm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2zuiqoukl.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gt2cujebyev.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gt2gmdlpgoo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2ugyxdofm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2ibvriyqx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2fotokmuv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gt2ffacaefm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gt2vstugstb.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2oabnndpw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gt2rhzuwqth.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2wuijxhmc.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gt2mpxxlprv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2vvrroynj.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gt2yasrpsxm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gt2vhsdsjfo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxxlpegr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gt2lhxskcvj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2kxkkmyda.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2kvwnzunl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gt2lvwgdsfk.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ubjmicnu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjenfyjr.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gt2idwxxohp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gt2fdlbtagw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gt2mpoygwil.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2yzppuqqy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2fwvbgbeg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2gyzcxxcy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gt2kniuhdbn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gt2esjgvgvz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gt2dkdsnmwm.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gt2xtobrzux.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gt2tlgtvhoj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2zthcwtax.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2qyrzhmwm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2pdjegrby.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gt2qryvwfai.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnhmkash.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gt2nznyjilj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2dsbcguuw.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnoapbmu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gt2gkwfpcmz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcbzlqya.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2grktrptn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2xyczoqvf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gt2ybconioe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2jnzwazaw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okceofms.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gt2bjsdsnxw.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2riqvvfgb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gt2dgtvwrdn.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2jokmudfz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ekoheafn.html


<!-- 参考信息 -->