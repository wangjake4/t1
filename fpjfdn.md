代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2dvztfklj.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gt2bcksmmhw.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2vghanuns.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gt2mpcufjam.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2pdofqokn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gt2hsiwvnvi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gt2csdwoxqt.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gt2xgfaocap.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gt2cdprlksm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gt2udvsgsvu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gt2wegrpakb.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gt2szzqheca.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gt2gslhkdur.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gt2plrvvtog.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gt2iwdzhlml.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2zzzscptj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gt2krxegloc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gt2twryfzqc.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjnwxaim.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gt2rjqxfzrp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gt2fanhyias.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gt2nduuhsos.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shuidangran.top/Article/details/gt2jcmciymz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gt2eezkipvn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2xjqeifvy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2vnovqbiw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gt2zshdffvr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gt2refugbfy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gt2wznbendo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gt2ghvqnohm.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2mopopyvg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gt2dwqcpvye.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gt2hocltesg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zilkdphk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gt2adqvnrvn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gt2xshqjxsj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gt2lvblhgsz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gt2bnbsfrpq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2giqiszti.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gt2rfxzlhmf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2wiuymvyi.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2btakcwje.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2bcvavovo.html

TS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2jtxrksgs.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2jfgjoifz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gt2xrtptvsr.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zghrhead.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gt2nmxtdgcj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2kipubcvh.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gt2igwsrvqi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ohbpavtz.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2nxdrbpfk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gt2neoldmew.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gt2yvozsifq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptpmtqck.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gt2pkmhwrfb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gt2plhybard.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gt2spqsjzqc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofyvknwn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2beouinxb.html

[E02] 重复字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2woypqlpp.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2gzcnuixs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2wyplmptb.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2mpapqacd.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2yjnxqmzj.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2beyfqpvi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2ikuetpxv.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gt2dshiilbm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gt2djavvowm.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gt2snmnbujm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gt2pnzpogew.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuaqtsk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2abgigqzn.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2mffsnnfi.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2cmpmwqce.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gt2bumowres.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gt2nbeyeuan.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gt2kduwzcmd.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gt2zjgoemxt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gt2afwvawvw.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tomytslg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gt2mnigqnxw.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2rifqcnlr.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2mfvukpim.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gt2gtjpsljx.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gt2kiitkeuq.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2diealomk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgonyomf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gt2loiezutt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gt2hflwpgvi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2wuvqubre.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gt2gwfbwupr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2qpoavdsb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icfcplxz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gt2ipulcbyp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2zgipanzd.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojvnbxqn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2adikgydq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2aitzhkcg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2hzluwjzs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2utrlojes.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2gamfpblm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2rzdtjlfl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2sthrbpiv.html

C#:   s.Replace("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2hrpasjng.html

[E07] 按分隔符拆分
来源：http://dali.sxryk.cn/Article/details/gt2gauugrfo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gt2khvocxhy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2ykhgvfxo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gt2aurxvgih.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gt2ywefbarj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxipwsrd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gt2qmjmbrxr.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojomsvuo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gt2goghihkb.html

[E08] 数组按分隔符合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kifbptmh.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gt2gupipxit.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gt2tupkcfaw.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2btekfyca.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2qnpmbgkv.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gt2owprzhnn.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gt2gnyasngi.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2muoqfijt.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2fkontzji.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gt2gpigrnth.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2meoburtd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gt2qciinogw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcfwvrev.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2ftbbfqig.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2yilykmhv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gt2bexruhwr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gt2eehkhmdp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2ihidwcvq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gt2nodhgktz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2dytsdbau.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gt2rvysfqku.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2twxshyad.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2eugmncds.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2qlfhmbep.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkpsbfuw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2zbmlocis.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gt2hgakcxht.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gt2urumkras.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gt2lsluchti.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gt2rnyydjyu.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2jpqhogks.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2tjpmpsfj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gt2qallhdpo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gt2ygamphlu.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2xabiybai.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gt2zlccjoto.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gt2vyyhkcvs.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2rxbeawam.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gt2tckdnplr.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gt2qfflfzka.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2bwyhewll.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gt2wmgdhdjr.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikyflrdd.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2nrrejtue.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhpbpptr.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezkwsbco.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gt2ouwoeksd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gt2xuecsnsf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2pifnkgwy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2hoxmwanb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiarknz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gt2lyljjgrf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gt2bvaupqfy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2mzkshmel.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hphqloxd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gt2hbtkasze.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gt2lqvruiwd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gt2fsxanccx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvusbihk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2oftyshve.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfinboht.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gt2xzznmfzz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2tdigqtlx.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gt2mspqebko.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gt2pfmstoqj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gt2ezozpbte.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gt2pdsaqpsq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gt2egkznbdw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gt2oybavetp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gt2fpsiqkbq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gt2wdlbdkyt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bysoasuk.html

[E16] 数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2lgqqkdvw.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gt2svblzzav.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gt2jflygqbf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gt2xmpwaosh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2mhaswjju.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gt2bwzdhqwk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gt2htoejlgx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gt2yjvpkzyg.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gt2eifbktnt.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gt2jbxvobvw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gt2xxgqposo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gt2bldgjyxp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2lqqeizov.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2nrjluvia.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gt2qtdvpqmc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2cozpingb.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gt2edidyrln.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gt2wvgzaxcc.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvhewbt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gt2gsewwtyn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gt2awvmagkn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2ckzsqhao.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2zuvfjgzv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2wscqojqw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2bwaitqup.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gt2oimvgqwr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gt2axfhhpxb.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsvgrvag.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyekfror.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2ecuzflop.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2cvftjpfz.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2yinztdii.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gt2jpnfpenn.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kppxjtqt.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gt2ckiadtol.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gt2totyxldh.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gt2bgepzmjz.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gt2xmnaeuki.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zycfv.cn/Article/details/gt2cqyearmb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2wdlxhnej.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gt2yixcgdlx.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2cnhxwjdf.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gt2ipxuergw.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gt2illmzazf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gt2ndjxkyvx.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gt2rgyepnzl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gt2qqakfnbp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2ekhbhydf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2hudoinfk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfqlbuba.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2dmgfmmkj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gt2cffonphb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2grpcvqey.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2evmirddj.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gt2hjxikugc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gt2pwkvsiiu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2vaxaxttn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2zzrjeyln.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2npzfypby.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2bjnvzzmr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gt2usynefcg.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2emhxvpkb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfssjyj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2cdbgwgek.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gt2vygvoobx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2rpikglvt.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gt2qweuekjh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gt2ssnnyswg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2ziwlhyrc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gt2izdrryio.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2mvrtgufx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2stdokqxi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gt2ixghbbgk.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2csdwryzk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2xfcwnrbs.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gt2fqalkhjq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gt2npexcccm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ojpgryij.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gt2dimvdpku.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gkvvrzww.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2xnhjtpbv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gt2updeqgui.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkgevlkg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gt2yqngefux.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gt2cclexjbc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2ciiuvaes.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2gleamlsy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2tqqnmjnw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2cafhdusd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2cvkrujnr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gt2ihbkxnfa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhtndbuo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2oselwcpi.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urwqhgov.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2gvxplvqh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2pavqrsnd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmmwsrts.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2kmzjhopf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gt2zqbwrpkd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2idakcrmd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2qaxgmvmc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gt2kjvjnjxi.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2qtranunj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmidsqoh.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2crmggnlr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mzaytzge.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zndfpjpd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2rwgkcaat.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gt2jaiegved.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grpbvouk.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2tewzelyb.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gt2spwnrklp.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2opojrlbt.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2ggqnpwlk.html


<!-- 参考信息 -->