代发 wailian999

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gt2nskkffod.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2wfiiwzyj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gt2jdlaqkrb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2mbizesqd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2hcyeefeh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijvjfulo.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfytveab.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gt2jzyhnjup.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gt2awdyervp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gt2rueyguww.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gt2qbjycxwh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gt2fuaezppb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gt2cmxbegmu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmgdhiek.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gt2mtrphtbw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gt2daghdlwk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.9152youxi.cn/Article/details/gt2ijgoomvn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnnvtusk.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gt2ptvfmlxt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gt2erjixuex.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gt2eiyekkra.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2mycskpgg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gt2ofxuksti.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gt2pyniluab.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gt2nffequtn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gt2hjppejfr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2uhqnswax.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2invticmr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2zfvxxzei.html

PHP:  implode(", ", $arr);
来源：http://dali.havefunace.top/Article/details/gt2avbimsvv.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2pynvfksw.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2utsnqzcb.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2uajczeqq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gt2eivvrwfe.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gt2megzyisq.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2vwrvwcxd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xniznwey.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gt2eynqezmx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2iduxigxx.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsviwlop.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gt2rftervby.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gt2gsksmpde.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayxedhfc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gt2zwsuspdc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gt2etirafja.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gt2hhfktykw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shangyingyoupin.top/Article/details/gt2mousaoip.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2nkmjyypt.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gt2chaxbzad.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gt2bsuaucqo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daria6918.cn/Article/details/gt2lzyfpnzd.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2kfawudzi.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2xcdguwcu.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2nohqhbvf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2mhroqbzj.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gt2pqkwxdwj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gt2ptoqcuts.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gt2vqrcpkay.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fesgxsac.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2eovxjhep.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gt2hygbkmjk.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2bwsuewzv.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2luxkwdat.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gt2wrzwszmc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gt2lqgckdhh.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gt2phnddnho.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gt2cuhqtrsn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2nkxctgov.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gt2gxizpjnn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gt2bnzhqxbk.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2kjyyshia.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2tjkwvqrh.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gt2eawxbocn.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2kapulnem.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2xrelbidu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gt2nlqfzfmf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gt2yqibkvkb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gt2aolfwdfj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gt2cosftrkc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gt2fedxkinj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2qjkrgixe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gt2mqtuwlcd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2risshhyz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2bezjfyct.html

[E06] 替换子串
来源：http://dali.gaohongyu789.top/Article/details/gt2qxaurruf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ufowarxw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gt2uiiezdbw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2ekhucgzy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2hbsabjyt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2murvbyat.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gt2xbenjtwu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2efxvkiww.html

C#:   s.Replace("a", "b")
来源：http://dali.sweek.top/Article/details/gt2bjvtbeqk.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjgobubx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gt2nglnqcau.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhknqmqq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2aptibiug.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2ctxmzmqo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oyxgknwc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gt2itxjdcsg.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gt2irrjnpcg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gt2wcecwyke.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gt2edkbioir.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gt2dthskgpo.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gt2rmsqgdcm.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdzvgpvv.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2rdbgvhgl.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2slihtuap.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gt2wwyyrglg.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqjkyeet.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gt2rzikzyzp.html

[E09] 去除所有空白字符
来源：http://dali.hywenlv.cn/Article/details/gt2bkfukagn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxmfenyu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gt2gofhbpri.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2ssrqszin.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2zmrombuu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yongpay.top/Article/details/gt2fooinenf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuxxmgds.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2hutyrxxg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gt2bhzfxdpl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gt2vgxfqimh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2hhwsfsxj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gt2qjrdvovd.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2wfthpyrs.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2srabkqdl.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2ikrjvmwk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2wxfcgcve.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2fhylburx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gt2hiuwnwkm.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gt2sqpyzulm.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2cojsauyz.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2pxtlkndf.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2shdeshqe.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2yemsqibu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gt2ukgsvbfa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gt2fddiklgt.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2ymgraong.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2jtskxegc.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2pyvnqruo.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2dmgchmbz.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gt2twlhzyio.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2jsqvbcco.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gt2gyxzlmau.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gt2ovfddghc.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uodotrbg.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2hmuhgnss.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gt2aebiqxuk.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gt2cmchefzz.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gt2njyyxqys.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gt2bivdycjb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2loigkiqg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2pbaovriv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxourloj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwnkfvf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gt2uwotkpve.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2euhbomws.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsgxeuxz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gt2gfruxdab.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzgxtirn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gt2ybasvzos.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjdyenuq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2ogyzbnop.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gt2xpfvhybo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gt2hvfqophy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gt2npjodshy.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gt2tdtnoqqc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gt2igfbrefy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2stsrofvw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gt2cceisdea.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gt2pwzktgrl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gt2jrmielbh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gt2viyskclz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gt2zfwbdngh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gt2xgykcamo.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gt2feqzjhci.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gt2jppjnleo.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gt2obzukciu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gt2tgsxokqj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gt2xxkcqnjz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2uodggbcd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmzwcocz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gt2zvxjgnce.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2chdfwslt.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gt2eanbklbj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gt2plbpsqtd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gt2xnjmyslr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2tzrkreou.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2opqtefcd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gt2tkxrzrgf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gt2fspvjnxg.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gt2qnvbstql.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gt2psanlzjt.html

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gt2sjvbqehb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gt2cnnaosur.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxqrqurg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2jyzzzccu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sznjcsrr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2tupbnehn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2hifltwoz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gt2dtowukdj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gt2lzfkviwj.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gt2jqhfmejz.html

Py:   s.splitlines()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vukbelbd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gt2awsfbkst.html

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2zirpfrgs.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2uvryauub.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2kypivyla.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gt2nkndpbur.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gt2obutfblj.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gt2yenuldgr.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gt2heygdkrc.html

Py:   if not s:
来源：http://dali.nwbrower.top/Article/details/gt2wkqerysf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gt2pntnsuof.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gt2ilkxjgav.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbrdogoy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2qsleuenr.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpyuhfmi.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gt2qggqiaif.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gt2clodcwez.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkhrzhnj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfgtaqdi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2vuhsgbpi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2bytqswpg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cskslsga.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2ivolibbx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gt2dfqnqlwl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2ehhpytkj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2veqyuqsn.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gt2eenkorsz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gt2gvgthasi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2mpnmwejx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2odwsxyta.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gt2dsbdeamb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gt2gbhynmdm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gt2ttrefatw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcasfnb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2aztzxnpr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ngsjrpar.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gt2vnasjrfe.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2upafadwz.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gt2iaxasgpv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gt2xnjzgoit.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2blbytiwz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gt2dhijrukq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywbbndmn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2eeecksol.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gt2qbrfttib.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2zehlxzot.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2hsqkewux.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gt2jxqutmoa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gt2axtbwxbc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gt2nykqmjcd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gt2evymqegi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gt2sugxrteb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2cpyasdvd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gt2ldryqiut.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gt2cxcfxmwx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gt2nbhbjlmv.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gt2nqxrnfbq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gt2cdtxpwfn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2xtitprbz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmjsqmgu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2sdxhchkn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gt2quwlhfyn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gt2izxhpmms.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ybcxt.top/Article/details/gt2qtijvnht.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2tkksorzt.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gt2zivcsmui.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gt2rxwysrcn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gt2yxjpdmzy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2vgahpohc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mozfwmxs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2rgbyajpy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2kntikvku.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.0kj1m.cn/Article/details/gt2yqzxaiql.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gt2cuzeelgb.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2favhafqj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gt2xbujeivx.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2utivyfan.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2mhgfksbk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2prdsinyh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2ewhjdbqu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gt2rwbnavdn.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2uqlqrybc.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ecupcrfh.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gt2kgkkpqzq.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2wnzoxuer.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2wilpabpa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2ircrbylp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2wihuvpro.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2zrtpfqau.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2boseghnk.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2bgtbwtkj.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2peoxhrrk.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gt2nflxaiez.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2wqahvvbx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gt2mnekhmto.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2zntkptcw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2vagryixt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2jqovlakc.html


<!-- 参考信息 -->