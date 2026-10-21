代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gtsbnzkgty.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiegtxrm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtnymkeojt.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gtzfyrwtyf.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtmuthgntk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gtgijsxwzc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gtjxinyvoz.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gtrjopgftk.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gtgobumzys.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gtcqgggkuc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gtkgyutuzt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtkxqjcrxn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtdlycvgtx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gtqgvnrusy.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtsmxgyvje.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gtmfxoxwox.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gtprflchcz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtuzufgneg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtscyyvycu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtmjvvbwqv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtbimeeinu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtalnmrqvf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gtruhnrscw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gtpwfetyxl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gtacfmltjr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gtopbdpfsp.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gtapxgcgwz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gtihjjvrzy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gtqoisvrwq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gtehbvytxk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gtltumknri.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtipuviocy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtrtwgooux.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtoyssewqx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gtxnuthkej.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gtbovrpkps.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtzfubhyfs.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtgntdfoyy.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gttomfdexm.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtpvgolgsc.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtbzretczt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.havefunace.top/Article/details/gtqebstgsc.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtgbmmeayw.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gteijfryut.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtaiwnwrnm.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gtepxixatv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtyzwjpmwy.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtjjnrjoww.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gtwthhwxzf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtjfclmxpk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtfqfprkte.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtoeekayzl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbtzaarl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtfbmpiznr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtypznopmq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtzexuaqdm.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gtfohsdueq.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtjdyciyae.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtaxnoqlvb.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtbzfnchzd.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxpkekyh.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gthgedngux.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtwausxwnn.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtbycmoydd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gtichzusra.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtudkteoul.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gtzutynmxq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtyknxwjpe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtkpnicvto.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtuajqizfe.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtnpmwnfve.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gtjjjubciq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gtaqxfgcdf.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtxnyxghrr.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtbborecoq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtzogqdsku.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtdjlvwugp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtqgtddlto.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtvowgzial.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtjnzrzvvm.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtfgcybemd.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtpumuqjjo.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gttofmuydo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtfjvasgvn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gtwdpgolfp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gtdcwsrvbd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtvptcisem.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtmikskrui.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtpfiiuirw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtdgzsgsbh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtgkcvzpxq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtscdghwve.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gtjqtxxihf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtasrekssr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gthnjwuika.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtaqswlage.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtknvdbepc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtdarazvjr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtsjwugudb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtrfwcbhua.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gttgnzmctw.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gtajzmyzmv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxinkj.top/Article/details/gtskzkpdtw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtcynklgex.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gtpfyqokce.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtsrmnjixv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gtqpmuwoii.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gtddepwsci.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtqcrpvqpu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gtdylpaxpm.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtrrhydptf.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gtffacfuoq.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtehbmwfml.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gthchmjtrv.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtshcddahq.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtzytadtkv.html

Go:   strings.Join(items, ",")
来源：http://dali.cashguo.top/Article/details/gtzjruwiip.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtiwlytmwd.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtauuwfdfg.html

[E09] 去除所有空白字符
来源：http://dali.zhiwuduotai.top/Article/details/gtkjrxucdt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtquhdltiy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpxeupyk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtftluzevv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtlwvccpsv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gthjnvbrts.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gtlytemshj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gtoiuqlaxy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfwxxqjt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtsyzbgfgb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtginamsyw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gtgrvanqwn.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtfakaoutj.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtrcogymgh.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gthhqhcsug.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gttcojherl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtkgjbzqya.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gterncqfbu.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gtjlsmtbjn.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuosqtgd.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtngyssrrx.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gteblziqdf.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtzkkpbvwv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gtsyomrezo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtefplcgmh.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gttyccefpq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtsicgquug.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gtozmmojpw.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtdgpotcyz.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gtpikjfalf.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtjqintbkf.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtjpfjiwnq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gtinnlxrmp.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtcuelogpv.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gttlpbwmph.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gtnkkfsggc.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gtmbiavzxs.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtwokkydka.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtodgnkgdc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtjftuyobs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtrkebxmyp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtfzdqwdai.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqcesdva.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtcmezgalh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtannghvlf.html

[E14] URL 编码与 Base64
来源：http://dali.fzhhl.top/Article/details/gtmmlvaprv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gtaaowjsxz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgqmfzpp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtuwkerhnc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gttayfktsg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtefjatfel.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdqxliwe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gtfftstgtg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gterslabir.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtejeblbpa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtucmgqnpq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtikgshvuy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtxurzhjpm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gtfsxipfev.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtpcamgpgd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtdsdcnzof.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gtshlbjzgk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctvxuayk.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtbqqswaqa.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gtshzvlgmm.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtgaclqeau.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtpavmglzf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtrucacilx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtqxynaqbs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtuhuexrcy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gtlyvdepxt.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtevramamx.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkuurpva.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtwghdpjfv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtxchqpkce.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtpyguglgv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtcnuafueh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gttnzvunfo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gtswxtmfrf.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtpykpsoyl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gtdqxupckl.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtlazoecaj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtskwpiyyf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gtfbsajqkg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtphvcsbdd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gthwykispm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtwikvuqvn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtdhngecnv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtzgelehfr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gttavhfqbi.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gtixzwlufq.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtzhhxofud.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtidrxwsfe.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtonsfwvfn.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtvxzgjayu.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gtzsvuporb.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gtzqdzgbjx.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gtemfrmtcq.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gtburdamoi.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gttsnyerfw.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gtkiznkuau.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gtjepumxah.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gtlncyztpr.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gtsblfledu.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtbykyvrrl.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtxzbavmls.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmyigcqh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gtzwxwqnxe.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbnpeklr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gtbijauqap.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtopctbxmc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtlrxlumbu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gthamupwrr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtlgttlnnn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gtgrejddqz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtinrjkumo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtzkjnqbht.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gtiyzrcqha.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gttchjoqtw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtbuprazqq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtwktuzyhd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtauvbbimo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gtfbbblxxk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gtimpjbyke.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtvlfyhpgi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtcfkdihcd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtifrgable.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtohqkflec.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdeywrgnb.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtfqocpbur.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gtnhahjxtj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtjjscezuk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbteyfoub.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtshrrwifv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtctregupe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gthymshquo.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gtkbejjlbx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gthdgcvfbb.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gtwbhkncsr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gtyyeisjed.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtauijxqln.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbcgebgjv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtqxuwozjf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtgbmoofuz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gturvorxkq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gtzcrxofhd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtkmmmavxm.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gtcwqqxycp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jlsjyb.cn/Article/details/gtjtpkiobw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtkppeondb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtunwvozxu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtiiyqytcx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtrxqdfcih.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gtqjwauarn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gtnrkofkcv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtrzkgcunh.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtqgvdqabt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtrvefcyuu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtqfnarxvf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtqmkysnae.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtqhxhrzea.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtnjlgcxsf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtzsjrsjwc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtpbsmdxbh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtnjkbnilc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtvqbgljmf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtuzjtjajz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkwsgfoi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvjrbnhkg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtshdavuvc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtwjzrraen.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtympceuno.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqrefeehr.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzyfuxhin.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtcvyycvod.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtrrankzor.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtssjwewos.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvevoswgq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrqasetm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtjzxqecwk.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtuidjtsxg.html


<!-- 参考信息 -->