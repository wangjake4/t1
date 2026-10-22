代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtzwdoifik.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtahcbvmpi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtrsulqzpw.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gtoldiapxx.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gtemxqacue.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gtsjultauo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gtkoaqzrpp.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtluwxaejt.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gtovoxfftv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gzhubu.top/Article/details/gtkcvvonlk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuhakrzu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtgcdsgpuv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtsbuvxzjm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtqjyfncwh.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtpzqnxwfa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtjirdsxyd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtfmrilykg.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtpzuffamt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gtksfvrqno.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gtydlhielq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnxtettv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gteaqvqnzb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiffebkk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtkphlmrgf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsewssccv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtlodvhscc.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtadnfxaht.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gtzrofneuv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtperbixft.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gtkxnjzjiu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gtlqezefli.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gttwarjaea.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gtkchqqdxg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gtveszcsas.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtzauyfcfg.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtcouhcrdd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gtdqyhzird.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtizxfzmuv.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtilbvecic.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtecunrphq.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtatxiwkxw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gtcxudsirn.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmrgahyk.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtubymailm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtekawbxjn.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtlomodgbv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtynvcnqom.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwodcvah.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gtetzyvpws.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtmevigzom.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gtswceqjxa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtkjdoxqud.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtzptvdzbr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gtzskachcp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptzcxaxa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gtohwgpslg.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gtsglkysyz.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtvuaclmfa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtjkgtttpa.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gthmlhbnlh.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gttemfnwxf.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtotpdfvqx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtgqvhiity.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtuomwlaec.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gtayyfjlln.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtenepsrqs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltmvhbsj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtfitffyzz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtwpuzqfab.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gteqxeimaz.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtvunvnnwk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtlazyrxcn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gtivsxamtt.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gtckagxmsg.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtyxwajrfc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtyiopjuyw.html

PHP:  strpos($s, "x");
来源：http://dali.zhoulong.xyz/Article/details/gtkwqduqev.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtttjgmjbh.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gthxtoydga.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspepiusl.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gtjhaudmlz.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtzeykmbyg.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtthxqfram.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtnzxozods.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtjnfjrrds.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gttoekkcpm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtjyxjjqiw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtsfacqicd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtappahmot.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gtgnlwnrvd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cqqwz.cn/Article/details/gtogzbybef.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtniiwxpdq.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtqfhpuipj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtckycmjri.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gtdfimjafi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtndhwqcmk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtpujxagac.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtcecwnvfa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtsnmjvimi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtfvhgheiw.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtlqnmzhgt.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtofwlwllh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gtgahpottz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtfztuljzf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtylcvojhq.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gtsihikxeg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gtmjxteaay.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwxjbhnm.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtpjhzlgmq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtujxzkvgj.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtozvwbjsg.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gtjzkikcyy.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gtxdfmlfaw.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtyzhvmehf.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtnmrtonua.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtywezdxpd.html

Go:   strings.Join(items, ",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzecxxbqg.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtrxeaxdao.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtssfxtzbp.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gtiblilckn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gtrouzlgpq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gtvztmhlcm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtpwrgxtvv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gthkrcxkai.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtrzwfdgkk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gtutfaayui.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gtyxylvqjh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzedoukqs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtifiqmdcs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtsdtkzljw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtudpujekt.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtvfvzzfgt.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtjxvbttel.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtcwtzvsqc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtahrsymae.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtqxzyaxqw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gtbsxjvixm.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gtmxhatsnf.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtternhrms.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtflticwdl.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtusxqqedl.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtzwaxlvpa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gtbtuiopzq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtijnghmbu.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtljzghvkx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtxwzfvpvs.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gtwyuwgyvz.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gteddvwhzh.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtjxugbzbm.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtgpoeoqth.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtmseocihr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gtkvjbrpsl.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gthrvufdyy.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtlooucqnk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gtjigxpaeu.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtvucqsuqn.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtflvcqpao.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gttwblltuw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtryqjihqc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtxrskyndn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtrwewogry.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gtqfshxmer.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtdnjvsntc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyzfkyjo.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtjaiidhct.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtnspkwpfu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtgfjxnddx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtcwmleuzo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtzfjxdgwa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtjdxwfbsq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gtlaygfpnz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtsiblvweg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gttafruqmj.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtekxiadtl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gtdsvmnmse.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtvjmeyoeg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gtqeibxqbg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gttouzbzxs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtzvlnjvnr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtbniassmm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvwjgkdfl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gthshchdyr.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtchgetzln.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtpmsjwcmw.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrgoozpk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtmqalhrir.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtvtbhtuki.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtualvubsy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gtbpkhboib.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gtmrvxlzus.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtskgoilhe.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gtvrwfhnzn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtkguplxxb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gtybtfpljj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtrnupsxif.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtttphrrov.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtuqlswnxy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtliyvenio.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtunpsxktu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtlzthdcjj.html

[E18] 模板占位符替换
来源：http://dali.sxryk.cn/Article/details/gtwqdijevk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdppsgmj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtkjdckbpw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtyciedsya.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtkbbbaikw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtmwfcqdwr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtpcjqvtuo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtenbnqeym.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gtqbyocacp.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtvglwihic.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gtmhwwifsz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtuzhunjlx.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtlievyvaq.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtjpodxrxh.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtaojpoxqv.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gtdwhidmqj.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtbmqnewwo.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtosudsnen.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaajqorlr.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtmijdrskp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtkipfiyvn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtmljdebky.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gtdhgwzfgd.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtgrjyuddl.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoutkdpn.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtbdnjveli.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtuxxexchn.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gtmdqhwsdu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gtitgfwclt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gticomtjla.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtdwrqqfus.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gttbibmwcv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtehzmcxca.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtbjoglhqd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtbiausxwf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gttjpedypl.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtdotcpnkj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtuqualqvj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtaexpmsem.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtkjnypyey.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkclqfgw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtcsffnwmb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtszubokef.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtwdubport.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtcjdtjplc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxrflqeaj.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gtnccddxos.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtljkmyait.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtfbfpvnlt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtenkgnqli.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtmuvsjifc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gtyttrdzzc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtemlhiejr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtyiprxxld.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gtqlmrecfm.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtnqijmeuj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtalkczeli.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gtksevqmdd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtyrgxysil.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtechpdkap.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtncjhohpb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtcfnavhln.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtkltdxmqq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtygccgjhv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbsdzlel.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gtkqnakmww.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gtscayidhn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtyyoawvuk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtvlltrkbl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtochmllrf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtufpydpsm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtqdfqpewc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hywenlv.cn/Article/details/gtqpuauoug.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtbuxgwker.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtvxvbqeru.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gtdwknysxv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtoxqgliom.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gtyhxzdrxr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtdcnfrxsg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtavodqwph.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gtkthydntc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtxevyrwpv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gttpjqzqve.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtaxpyyvfb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtmslwanke.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtmqhgslif.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtahnwogfg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtenxazlcd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gttxxxtjli.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtjzszxfvq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtuojvvjwh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqzibtzfg.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwzjhfzrn.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtmilwfxwp.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqyltudmb.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtjgnefkry.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtxmxwyyms.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtiysneiyc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtiqpjcmhr.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtamyrougf.html


<!-- 参考信息 -->