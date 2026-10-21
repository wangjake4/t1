代发 wailian999

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtlpcwltzf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvyhvorf.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gteurgjxut.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtzmmcmeur.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtmyahbhms.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtlruztgtf.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtsxbjozgu.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gtbcfppopq.html

Go:   slices.Contains(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtlqqvkbty.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtxvciiqjh.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtqsxotxal.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gtncauxugo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtityoxdyz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtipsjegqc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtedicwabl.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gtduolgzph.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtiwmggnbb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtcgqgwaiy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gtkauopvdp.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtkpvdkgmu.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtzdqzsgbx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtrvkuazqv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtvduxhakv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtsswxgfhg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtzpoxylcx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gtjtffazpt.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmjxjnyl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gtyiqbqpas.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gtwoqxdvwr.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtddccjqox.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxinkj.top/Article/details/gtnsbcpxuc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtdabicuug.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtrcveyhlp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtqahbcpdj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gtknzznoew.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gtnkdahezo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtniynqnfj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gtpewodpur.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gtgczlslyv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gtwnetrzpi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtiffpflhd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtdefgbqjh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gtbrpgwghg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtzrfhvfaf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gtbrvvzenb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtuyydfzub.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtxkoxrhfs.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gtqbhfdgag.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtjajfecuy.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtmvuutbkr.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtyqybahbu.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtpdgavtuy.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiijgktg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtrhedqisi.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtsiixodvf.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtbbsadczv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtulrdrqjq.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gtxofokjio.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtidfzmdia.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtrglqxpza.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gtzluzcbop.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gtxqepnxyu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gthbuynhem.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtkymrfhcu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gtlvqlkzqc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gtphveyazf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtpgjswhes.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtepmvclqy.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gtxmkplpcr.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtqtmeteyj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlogipxc.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtmnbqochi.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtumgrxbwy.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gttwxgvumx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gtmwcfubzo.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtlwvzcnox.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtryjemxfr.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtkwlgftjz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sweek.top/Article/details/gtndvfjwca.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtvbjxyzbv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtxoecikru.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtpjmhbvhm.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtrzzjkyfc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtjxjadbzs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gtcpvfleyb.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gtitbxbrwe.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gtqpotlmao.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtkaibbamw.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrmyaukx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gtccejlznr.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtkmywsrur.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtmflqjtpc.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtfqwdfyiy.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtvehorcou.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtouuqhfmt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiieehpbk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtrmhnzpfg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gtdwykaqpf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtphrpxlrk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gtbxtiwckr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtlhsvxbvq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gthlywtayv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtkbfogvlu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtnzgohrcl.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gtzhzqtcaq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzaqznik.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtngexuand.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtqfgbdhvo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtubnfpnpg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtuhgkyktj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtfbrweuvp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtfdcnrocm.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtwpofvwnu.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gtzkhfpevt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gtkzbqbcuf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtdlypbdek.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtpropbsnq.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gtauluctxq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.meibo888.top/Article/details/gtwgtuiecp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gtosliacky.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gtfgbeadrm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtsrqvjtau.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdleoejl.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtbttabteb.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gtdhdafzwv.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtyraseeib.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtvtcabrpo.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtezbwrpui.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtsdwbrzpc.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtgowmgnzx.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtqvkhmtef.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtjjuvljnf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtfwpmsjzm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gtmgqkguai.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtwjwqtxpv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtutbqsbae.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtilynaqzg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtafrsygej.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gttfoaugff.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtmmowfkvs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gtvakpvgvz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtaqexospa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gtkwfcwyaw.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtfehnjiol.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtyleyavpv.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtwpoborye.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtrvkgrhiv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtkecoabpv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gtxckqyuzl.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtijgspaej.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtebwkjsst.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gtubsyhefh.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtrvxrmhhr.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtlotnvhxy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtdebiwnly.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtievkpvag.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtlrlbdpwn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtnwxfcvtg.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtngzoibsg.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtlbbhyois.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtxaipcomr.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gthrnfmkyi.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtniddavgh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj202588.top/Article/details/gtmeowwobp.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gtmpcrhdxn.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtyfzczxas.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtlbxwngbd.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gtudaqyfjs.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gttdakjwtr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtmwjgmgas.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtieuenprx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtqchxgltc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtgmoibxic.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtcddyfefp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwxjlelh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gtghloydhr.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gtihwdhffw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtcytvymnz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gtumhpqkkq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gtkleesayp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtamodccqh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtnvtzuysx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtyvuztptf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtspthrwat.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gtsbsjqczx.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtdezhmuax.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gtqslusvmr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dianchejie.cn/Article/details/gtrqsignds.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtvqjmeprm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtnxairkog.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hywenlv.cn/Article/details/gtkjxwagyr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqypscci.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gtwsvrejuu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtgpomymmy.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtzefpefiv.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtwtxxodvy.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtguhizpsn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gttkaardko.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtkfifjfbl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gtaonqfrdp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gtthcqrbct.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtsxziiwwd.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtveyupkhe.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gttjccsxzd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtsmgrkiui.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gthsfualdq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtkjixgbcp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtoyodflme.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtcjtzcwfm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtguwixcke.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtjrcmoaqu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gtieasnvol.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gtlotaeiel.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkayyonej.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gtligmzecv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gteoeawiif.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtadkehfdf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gteaywuhti.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtfqiaqdai.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtnoxrbezx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gtgglcxrqj.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gtslnvjfre.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gtkoknjtjl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtimgkmukm.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnhvqtxg.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtaegiogzq.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtdygbsomd.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtonnpysua.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtcdjzuujs.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gtwqvnlwkv.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gtczejydjp.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gtqutfcmmq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtkqvpoxxs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtyxspflqv.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtrfvlruxd.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gthzcjxevx.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtwvloepek.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtaxiebdwk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgiiqpswp.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gtouhqczfm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngljhwjy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtlnewfsic.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtretkwbek.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtfdqfzftn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtqawfpqdp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtrhwohcjv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtgiienquu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtvdxvgjom.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gtichdngzo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtfxzpxtph.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtqfhpombu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtcejjauav.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gthyjkbupi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gtdfrwxdru.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtmlqjyigq.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gtywsbtvxv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtulmaulwj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdgagwjpy.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtcvbajtww.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpaxftrek.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtashvpnzg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtpxmrhevz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtqxpdtnir.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gttsbeqpnj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtmxhuiqth.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtijptiksj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gtotmgassw.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtaxbfijck.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtthpxfabr.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gttyqzgkjl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gtometjcfm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtjabqsmkw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtpfariewt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvtcmgii.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtzlwxlqev.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaamqfol.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gthvqteiir.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtugiflpau.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gtqrxrocbk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtstmcoynr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtrxxpprgt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gthsidmosq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtwhkyfgze.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangdashe.top/Article/details/gtzdjwavoz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtflvdzqji.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtqncvacxd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtmyqoszwx.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtqqlddals.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtsucogaoz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gtkfwbprfy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtkkvddhbd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtwwsirawh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtzrkjbook.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gtatrskfen.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtctxxejbv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwvosfef.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtznzvievc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtlzswblvh.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtdidbviyj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgdprbznd.html


<!-- 参考信息 -->