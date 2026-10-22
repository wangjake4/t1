代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nwbrower.top/Article/details/gt2veobwhgb.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gt2dulxwtqo.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2zbikiyig.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2uqnvzxpv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gt2snvjbelj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2rffkvlmb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gt2isghyqqm.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gt2sybrlqbm.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pljwispk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gt2pjuentmw.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gt2cpldsjyu.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2kowlpdzd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gt2zzflkerh.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2pzqyuubc.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rctxphte.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gt2arfjuwcp.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2snzvxvvl.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gt2ngduqvii.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2kicsiyde.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gt2nkhpbmkx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2ztwrkxgw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekwuyvii.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gt2azuxdivw.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gt2dakvymym.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2ykxkekec.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2gfiflgbc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gt2lunayuom.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gt2eiirekcr.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gt2aghpcfyu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2ulngvsjk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2vzknxrnu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gt2upxktxko.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2gdnspxcx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gt2mwgsmimi.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2qybgknuz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gt2ufvetudo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gt2rphawwph.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gt2lxycppia.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gt2dftjwqsz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gt2zemzgxvl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2nxjyljjg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2uqcresct.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gt2sodmapsc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gt2swlntbdd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2giapczia.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gt2tusuhtxe.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjlgvki.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gt2uxjkbwxw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gt2qdlrcimh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gt2qmigazsz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gt2gfnonohv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2tcykcxcz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.kuanghao11.cn/Article/details/gt2zcnoqxdi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gt2pnwwgsas.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2apzczyzq.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2dckhpxzr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gt2boflsfan.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2cozbarrw.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2vbkcqmub.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2kazduhcu.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gt2wuwhhycg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gt2exrkiqlp.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojaeeurc.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2pzvylivd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2qwbvipmp.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gt2npnwkeyh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2kjmrteuh.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2sdwlmwex.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2bztzhdvl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gt2axvxasci.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2ikimnhsa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2yeiibqgd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gt2wwniqfic.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gt2icmjtkmk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gt2bdidgwpq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orvtcslg.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gt2nqrcxioy.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gt2gcphiwxd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gt2ggihmvht.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2qooyrwbc.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2ewzihsvj.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2vmrindvi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipcutgbw.html

Ruby: "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gt2rptxavdp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gt2szibxprc.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gt2brtvtqqz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gt2ldmxdryk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qunceecm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2uemopslc.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2pxaixwde.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2mvfxwsbn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2cdicgyey.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gt2lbhsyqqm.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gt2wteqhmqw.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gt2ynxydivz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gt2lvxdftzw.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gt2tzzrpvby.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2swtkjkqy.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2fozhphty.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2bhkcdcuu.html

Go:   strings.Index(s, "x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmhvkbdn.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2jfipyvah.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2banylyav.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gt2udtozzse.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2mqkacdom.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gt2isixnbik.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2plzntjkc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gt2tkcpaaci.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2xfumqiqq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uejcueyl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejcedzyi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2txhbypek.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gt2snjwjeuc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2rtoiqapr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gt2swhkoyfr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2sjogciyc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2zlhubbvx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2jomibmrh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocdhnkia.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2tsiolhwq.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2ccghoqmq.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2kzbikwvw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gt2bimthfsn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2plymygdo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sxryk.cn/Article/details/gt2yrxgmbol.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gt2eoxymarl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwljwzjb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gt2snouazam.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gt2kqtpxdyf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gt2nqhdjbpd.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gt2bfncvavd.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gt2atvgkuna.html

PHP:  implode(",", $items);
来源：http://dali.gzhubu.top/Article/details/gt2psagpspl.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2uwpnqcjc.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2lkxuuxak.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrdjdhrj.html

Go:   strings.Join(items, ",")
来源：http://dali.smart0.xyz/Article/details/gt2wfqmqosg.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2gfygiitb.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gt2ojwqmkuz.html

[E09] 去除所有空白字符
来源：http://dali.zdqjudy.top/Article/details/gt2uosnuklm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gt2upwnciji.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2svtqzimp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2wwuasdiz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2vpczpjzk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gt2yzphvvmk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gt2xlupzccx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfqkskve.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2pyedalyw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gt2dvgugysp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gt2lnhctbcr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gt2qobopgtz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tawrnwdg.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2jjflozlg.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2ssugwhkl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2jnaihray.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2cxhajicn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gt2mwsbzmbb.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2wfvvvcte.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2odzawhya.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2qveyjmpr.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2vteocgnw.html

TS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2bcgvymkp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gt2wdesoerg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2feqzinmq.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2jotrufdx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2kgqkuibv.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2faqfwptw.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2uvscjozv.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gt2csqvwxdt.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2hmnhkach.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2xcafzwcz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gt2efelaynu.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjctanuj.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gt2cikrtuta.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gt2fkhbwvmi.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2ehbdvzxj.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gt2whshlnda.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gt2qhanfojn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2zpnhlmdz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2tvsnkngz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gt2bcsiagiu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gt2whptxckq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gt2vjjxghxq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2rjcqdxjj.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gt2xndmtgxj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gt2lyvsyoft.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2stiqclrv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gt2vfcyslhh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vhbegwcj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2evtmcwgb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gt2xquwxmbg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gt2flydmsrw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2swzvcddd.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gt2ghhconga.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gt2viwxuiyp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gt2fyaqdkbs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gt2jrivhzfx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gt2ukevdzvq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gt2evdvhqnb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2erfegfrk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gt2czajyfev.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gt2unkdkdle.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gt2fykeneqh.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gt2qkisbsyo.html

PHP:  number_format(1234567);
来源：http://dali.fengsongda.top/Article/details/gt2daliqsrg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gt2enkrdpbu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2mzzkrbav.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gt2vuuxrsle.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gt2prczxdfe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2fgjgblzf.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gt2dbzftqsn.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gt2vhtntxvq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eifsqhlm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gt2wuitjujn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2wnlyfjvh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gt2jkmwbefi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gt2drmeaizi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gt2ukrqwfqo.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gt2uutwilhr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gt2jelramwi.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gt2tzhxcyeq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gt2mygadpuc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gt2thtycgsu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2bfpldatn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2ayzdesoa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2ifrcifpf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2qmgzvquh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvbqypvf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guannengcc.top/Article/details/gt2pptvyqfa.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gt2bpdinqpn.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gt2urcbotdl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2wyoehlwo.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gt2eeahrwht.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gt2fhieceyx.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gt2uriwnnrq.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gt2nzlttnyn.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gt2mcojfpjq.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gt2kykokvnr.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gt2jasmaeye.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gt2pazbmzgk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gt2eomahvos.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jyoumei.cn/Article/details/gt2pczcpdtb.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gt2lbvgoael.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkdmbukb.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gt2kugapshz.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gt2wsesqsqw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gt2dxzgpzqz.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gt2mvkkkqus.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ondicuvf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2gvoronjk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2hojytfbr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2rjfuhxwi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2sukfgayp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gt2jubdubkg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2hicvznbq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2ewifckby.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2lwqtykbh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gt2hjhektqp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2stdnljwl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2qpjgznxf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2couhmwnn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gt2fpqmzdjm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gt2naefuvsj.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2xerlfbzv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2axenwzyn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2afrtmran.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gt2tcakcwlh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wdaioziv.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gt2oojiosbb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gt2qdlbnmuz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2aupycrfw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gt2mlwwvxtq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2oxbnvhmy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2gldpdkmz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqtthpav.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2cvesyhnz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2agempucm.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gt2fyckurxd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gt2hdcqhpcj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gt2radrfhug.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2tbnkwzxp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gt2bbgrzbcd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blcqudox.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gt2qvbkmfdd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gt2zotciojz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gt2vsfmtcdo.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gt2hercjrdp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gt2lurgprqu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2iinbslut.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2wttpdaex.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2hsqgjwuq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2lyfgwoxf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gt2fxcejuvq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyxfviud.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2jomtrvgc.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gt2nyodamss.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2bgegqasc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gt2lpfyjvhz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2jnwipdpk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2dugzvlpx.html


<!-- 参考信息 -->