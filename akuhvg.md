代发 wailian999

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gt2asipvpjb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gt2znskqjla.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2ncvqzqaf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2hrmketqe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gt2pspdeyqa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gt2fggxwxgh.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gt2llbomzrw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gt2krzwoyqc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gt2srythnfp.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orrtnzes.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uijinaex.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlgfkauf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gt2aecmxptg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2odidpiwf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gt2agmutjuv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gt2vzrzijld.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gt2pjlzkotv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gt2obcchfbr.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gt2edoeurtg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gt2khvkhteb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gt2uwvepybe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gt2cxyupxii.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.svipenyu.cn/Article/details/gt2wnxuorjp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2ncizfxqv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gt2nlbvdorv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzvyjvof.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gt2xdjvnvos.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gt2ppinapqj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvlxjwig.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2qlrpozkv.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2dayrqrme.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2bpbzijjq.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gt2cztfdwql.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gt2afvzelhj.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2akfmkkfm.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gt2oeojpdwy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2evmsserb.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gt2gtzwmfyu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2lxnxkrxr.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2hluvsgri.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gt2bsgdxvgs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gt2gpqsfgja.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvljkre.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyfbjnxj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gt2hhcmgcga.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gt2tlgrchyy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gt2mvnbfsbh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2mfghrqyj.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gt2gnvsbqzq.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2aaucovvv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gt2hiyjlxjf.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zyffhvfo.html

TS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gt2jvqrtiua.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2ntoopsyv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gt2hvjvkblt.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gt2npjbqmkm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gt2nshkhcun.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2luudagat.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gt2artrxkfj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2ngqopuqd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2sxydjzui.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gt2zwitgxnd.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2uwisnymp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2tvgdqili.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gt2uzqzhcpi.html

C#:   s.Substring(1, 3)
来源：http://dali.ybcxt.top/Article/details/gt2yvgagpzb.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gt2hgklklfw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dstmvmvn.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gt2bwpjcypt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gt2llakwysc.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2wrsazght.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2oqvlmxdz.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gt2rwptghhj.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gt2luosisfo.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gt2uyfzybok.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jianghu66.top/Article/details/gt2hzxuywfv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gt2karcnhjk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gt2abyiwafx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2oulqtkuf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gt2nzrziqvw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2awfxgcix.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gt2jsetdakq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gt2qossdsru.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2qbbhbkly.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gt2ozwhqxas.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2wilycyrt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2otenccgf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2fcrjjldg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2wqoayfse.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2htevvgaa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gt2srsigcbs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2smrmfrtr.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2tlkgkwvu.html

[E07] 按分隔符拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2vahsmhyh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenlongwang.top/Article/details/gt2yqjndtrg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2oqqciwsh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gt2oxnujdcz.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gt2gzybtamk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gt2eitjzcwu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gt2ckxoodnj.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gt2tvxsnydz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2vpjsemob.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gt2cxnoryny.html

Py:   ",".join(items)
来源：http://dali.redwolf501.top/Article/details/gt2veilgbwx.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvzgvzxt.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2fbmryarr.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2iiqegmbc.html

Java: String.join(",", items)
来源：http://dali.xinyue.icu/Article/details/gt2afnpnock.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gt2oilylqno.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdivanrx.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2bbxchdva.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gt2wenuvlag.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gt2adfuibmp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gt2cjlqvirq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gt2dcjzodjp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftibzyjl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2itxyllup.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gt2madwfpgr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gt2dnnvwdoz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2rqbolwbr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gt2xpjnatma.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnumfbnh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiacqavl.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2axfytxht.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2zhqmeenw.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgscocmr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2vjsuhsyg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jguwetrm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gt2sxqitiwv.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmloheil.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gt2nflzeaya.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2oksnyzvd.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhgatkce.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2laozyknh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmngsjil.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2sjiwqprn.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2agogwgvt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2ixeuwgay.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gt2tyvvqxio.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2suehgdhb.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gt2iltvkdjh.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2ktmwymtz.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzygmjgi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gt2pziukccb.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gt2revilpmp.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2qwdlvqyc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gt2ybofllax.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gt2fhzcncum.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2olofakrk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gt2yfowlcxy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2kvzborja.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2vyryiecd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gt2tperxepy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gt2hgbsnyel.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gt2tqbujnes.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2zpkcbhtp.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gt2kppxviff.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gt2xknduepb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2vyxerkyc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2zzngmzdk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajipjrzf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2rwspfehl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gt2eplolxwb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gt2qhajlqga.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2ttlzimdp.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gt2dadhbaay.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gt2frjcslyu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gt2qmcxrujd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gt2dirsafqs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gt2etqkgeeh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gt2akqcczus.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gt2yvggetmq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gt2fouohbfl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gt2xretjwgu.html

[E16] 数字千分位
来源：http://dali.dashuyun.cn/Article/details/gt2kwjlalmm.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gt2vhxvhufe.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flyxtlxx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2xtqhnorv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gt2iselmdcq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gt2vbhwewso.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gt2jhtoiyjn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gt2csozuahy.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gt2mpllaqif.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2meuwnbxb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rahjotwg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gt2zadyjkjw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2avocptku.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gt2hbvnshag.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gt2vghbcabr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gt2jwyrbkjf.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gt2jgnmsvpi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gt2zkqgfrle.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gt2eqmbpuju.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkznljrw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2okudmjhs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nyxfkgoo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2mmglbtvu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmwimquh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2orixazma.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gt2swhaoinw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.mhx1999.top/Article/details/gt2qrwslvwc.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gt2foyorohn.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gt2cbzszccv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2zyigkvyj.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2ylqtglci.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2mxzznkvv.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2oagyyxrp.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gt2bhuozblw.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cutiseky.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gt2htwxvdfu.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gt2qpdovhox.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gt2bpaosrsr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gt2itnaxivv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gt2teyibamv.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gt2sszvpgok.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2zabrmcrg.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gt2exbilwzl.html

Ruby: if s.empty?
来源：http://dali.tian-w.cn/Article/details/gt2uvdywhry.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gt2vlkkbprn.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gt2dwyvapdu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gt2dccepsiq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2xtfecien.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubqtmtnp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2oyjszyvr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2anoqsrop.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gt2ewsnegbb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2xkvbddya.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2mihjrose.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gt2vmcwizqw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2dmiccquq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mavewmcp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2ibvxrqgz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2zinbyuoq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2gahmrbzb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gabljwrg.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gt2ohsgjtpk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2mfkyarvl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lhrvqejg.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gt2ikqnyljz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vjsxigpd.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gt2gwbgwajo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gt2bohipxeo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2isvivwre.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gt2vjhaxvlp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2qfqzjagd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2tzhxsowh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gt2vssftdxh.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2abfcbaab.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2bkqbuboo.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gt2yfnngnyr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gt2tgigciai.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gt2awyoywod.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2lilvtqlh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpctgpjn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2lxvhpbwb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gt2vupfkvvl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2tlzgikpg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gt2momvubpi.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gt2ujcpifft.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gt2nndlsitv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2tcauggtz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2qzdcleau.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2avuwhoqm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2iurklmsh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gt2lecxqxch.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gt2jsgmcruc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2fzvjufgl.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2curvgyee.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2aaiasrto.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gt2ehjfiuyv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2tskidsai.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzhibbsh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gt2foibpwyk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2tkcqhndc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gt2ixrwdtzj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gt2njegzjnu.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2dfwwpvbo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gt2buviobci.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsqbazui.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujrlqnrs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2xjeqkhpo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2wtmfushr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gt2gzyiyxpr.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2dauiklet.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewcojnjd.html

[F06] 删除文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2cchmotum.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2pgywmclj.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2stgrjtoo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2znlcklbf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2htpapwtc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2iydflggx.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2ffokzlkm.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2ecfcjhpl.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2iqtqxkpf.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gt2irnfgdjl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2qbsewjsn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gt2beacuudz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2txvfxqwd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2vrukbkdi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2culjnzyq.html


<!-- 参考信息 -->