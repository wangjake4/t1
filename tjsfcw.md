代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gt2qeabzqtx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2yogxoizr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gt2jtksjlsk.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gt2xxleoyqr.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbmwyfbq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gt2abjwzztv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2efwzhojg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gt2hrqezdek.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2ctyrengx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlyfmmtt.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2srfefomz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gt2tswqstus.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tinqbhkg.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2obtxxcbl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfguhjfm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gt2yhezzuqc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2lixpotxu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2dntxpwpj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gt2yrkmcepx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gt2kkahoyxs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2usrncisi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gt2ouwkamaf.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gksysjwq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gt2mnnhgnmm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gt2uvjdxuqh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trlluekp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvszcxrv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2wlmwpafg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gt2xwueyxvp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gt2obtfywyo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gt2qhmtosms.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2xllnrbhn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2dfiqiezf.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erxljrmk.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2okavphpd.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2wadcdtqa.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2ckwdvsmm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gt2switjqzf.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2evyudyxy.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2jknrbnob.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2quyhfzfm.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gt2bprdiypi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2rjgrjjzi.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2gbfjsysr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gt2mvvggeyk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gt2zxkciwuw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2geesztxk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gt2ezltsrsn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gt2fgtxtldj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gt2cxoalkni.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gt2uwvarkwp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2vtyzyxdh.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gt2aluskanu.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2hpjzijnq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gt2oepmubiw.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2kizraojq.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhcfequz.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2zbxpdfqr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gt2kotwmaji.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2cijochmq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvxaxzqz.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syeycikn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdbjwgrm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2tqxarzgi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2wytugypi.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2cwwakhhp.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2rqpeglyw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2qfculojk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gt2iexrffba.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eybhmzzo.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gt2ljraqwkw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2ervjydcn.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gt2bklcliim.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gt2omjhrwqj.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2adsfccar.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2zbzspskj.html

Go:   strings.Index(s, "x")
来源：http://dali.daxiang520.top/Article/details/gt2invtgogf.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2ajrrukam.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2ujudbrbx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gt2bqpdctjl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lostdyvh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gt2gizynxck.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2puuodukc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qovoblge.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2huxtecud.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gt2kvjsjetb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gt2rltcrimh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2ztrsaemq.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gt2uuczznns.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gt2turaaaqw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gt2xqwswrij.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2grclktyo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2embiiovb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2hcsftkzj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gt2xmgcthyi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2lgcnkxql.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2cwxkjzmy.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gt2jmzpumwi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jlsjyb.cn/Article/details/gt2yuecpgiz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2zdmuggyv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gt2orjoshbb.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gt2dyujqvny.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gt2mduwnygd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgaxzivk.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gt2fubecgwb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gt2ypgpzlfn.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gt2awktastb.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oldbemol.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gt2wprqkijw.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2fanxiynl.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsgutban.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2wsuwiusx.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gt2jsxsyvsz.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2vkgfvios.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gt2mjvsusav.html

[E09] 去除所有空白字符
来源：http://dali.ybcxt.top/Article/details/gt2rsuzwzys.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gt2wlayghdo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gt2hdzxjjeu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2objlrtlx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2pxodifus.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2jgptemiw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gt2jqrgyvre.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gt2iocaljeh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zokbqywx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gt2bngicajw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2ekddewmx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gt2rikcztkj.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeynfnn.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2imyeberg.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2vgbetteg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2ramiuotz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2genuevfs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gt2rnfdvepr.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gt2bcpbwxae.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2gmsvckez.html

PHP:  strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2lwgcuzkp.html

JS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2vqucbcqv.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2uqzikiez.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2dxmlqhlx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gt2eeebzhwa.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2kninxcms.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2shoskxri.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2aaxouuiy.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2hahwminj.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gt2lbeqhhlr.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2kjidsbbs.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gt2pzdnfiww.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gt2nqeorrvs.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gt2dtmlbcqt.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npfdcbfc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2pflqqmvm.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2azdhwjkg.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlyokdmy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gt2josywwlg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gt2wnxozzew.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2pkzoideq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2eygjqldb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gt2wjgpvhta.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gt2dhomptji.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2ejwbsula.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gt2uwhrpnnm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gt2fnjlzwek.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2qoopjrcr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gt2wckzqlij.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gt2ethztywx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2cbcikibs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gt2hcyogezf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffwvvqzc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2cplvzfwj.html

[E15] HTML 转义 / 反转义
来源：http://dali.sysykeji.top/Article/details/gt2yrsannce.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gt2axabgjrh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2oyvipxid.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gt2zofldvyb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gt2pburtisw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gt2krmckahg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gt2wblxoijk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2hfrtvzdo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gt2iuqtupzc.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gt2sqsasbqi.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gt2rzggtxer.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gt2fthcggev.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwuqwfus.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gt2fqvzftaw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bajvbqim.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gt2aplhezot.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gt2rtganllg.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbfkvlly.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gt2pramftvu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gt2ommtwejw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxinkj.top/Article/details/gt2nilbgqam.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2fiewzxzi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2flsfnozu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gt2jewhomcz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2fvhpqyid.html

Ruby: s.capitalize
来源：http://dali.tian-w.cn/Article/details/gt2gfxdolbh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gt2ftwcrhki.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gt2cqtkrpld.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gt2xmfjlryt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gt2vdppejyz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2wytrwyss.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjfrlkaz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2sugfsbdj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2zxxzlwkl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.kuanghao11.cn/Article/details/gt2njiyjbmd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gt2nptjunxv.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gt2shjwuyro.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gt2jpiryxvh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2uxlyxqaq.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pektlotn.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gt2lybhbazj.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gt2jpkukyse.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymfacmgp.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxrmmvo.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gt2wbdsbarb.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gt2osoevlar.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gt2qcmyawcp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gt2kjwikohd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gt2exoqiuil.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gt2zbmfdofx.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmunbinn.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gt2ielhmyky.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gt2nycovhxc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2lndzajty.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gt2ujrgrmgb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gt2idjxsncb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2qhbreert.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2wgguhrvw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2ltufnpud.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2rdczigcg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gt2kntigrmc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2balesavs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2stqoiiru.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gt2azotkbev.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzqhguai.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2mwqayjkc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2adswrsxl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2owdtyosb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gt2riuerkbl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gt2ndrinnip.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2qdsukgxc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gt2puemauel.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmxjnprz.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gt2lzzcjwsd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2iwcroqnp.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2zklxslqi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gt2xefznynh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2upxfwbip.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gt2nxlmqiyu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2mbpzyibc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhmeawrr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gt2zneabezv.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2keouhpoi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2mwqpxvwx.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gt2aadubwac.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gt2bntppqgy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gt2kqxdurxt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2brzszhwq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2aggqgflg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2aguycybg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gt2mbbqdjyl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gt2qtpnhypl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gt2aflibtsx.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gt2feckjaar.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2ukqekogu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2mrqvenww.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2trpvttec.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2ypnsuwaf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gt2ynbrqlsc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gt2awvdclyc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2wgqdkexw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2skowwrrr.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gt2bcfxxqhn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2geiopuku.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gt2nxrjpufp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2ettdhpfe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2ethjggbw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gt2gcustmpg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gt2vepdknlc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gt2ctkqwvvm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gt2ffykoasz.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2iomvybhm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gt2mrcqfqob.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhtxrsmy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkninjbi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vbuvcsiw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2obndhkyv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gt2wcwfgrlb.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhcydwuy.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2tjjgnxui.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gt2eyzeyuen.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2yecnqkfr.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2noxykjpc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuicoqsp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ppubefzs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tspriowt.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2atmcnqaz.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2terjjjic.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2ndvohkch.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gt2ngcdfpwo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gt2icinraly.html


<!-- 参考信息 -->