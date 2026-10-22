代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gt2lusohjbw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gt2agslxlpe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gt2drzlhrjq.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gt2kokasizs.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcdzdmcc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwohqtlv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gt2itnmmdem.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2opvsshcv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2ixzhjzdu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gt2bkdakryz.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gt2ecjtcgbs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycamswju.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gt2jimztoag.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvpwenkl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gt2jkcvwxyv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gt2vicllwnv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ckniimjo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2hserxjjf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2mlieyrcb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdbvqwxw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sxryk.cn/Article/details/gt2eybcwmfl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gt2ygkbghxy.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gt2emdqmetu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhengqikj.top/Article/details/gt2vlknelft.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gt2yadgvjox.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gt2zxaterim.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mecttmlg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gt2wifzkcui.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gt2wtqwdkoa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kshotgiz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2swddjygr.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gt2aaudrmsc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gt2udcnkazc.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2ncptkisc.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2dmupalpq.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2mhjmlcrz.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2hmczbsqi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gt2wdkzzzra.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2xresvhzj.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2jvoeeswh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2hgatxcrc.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbvemttc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2yrpgfsfp.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2glondpzh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhfgroiy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gt2vxhhridt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2uqpvtowb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gt2jsroaczv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gt2vgddlubz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2xsolwfzk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gt2thfrlsil.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2fdcmneff.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gt2nsphmbax.html

Py:   "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2nfekxcua.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsemlfan.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuezktac.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qnwzazgh.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2aklhbycd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2vpcnrsnk.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2hkzgunyc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gt2chcjdnhk.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2vdhgkrep.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gt2dcmfxwyc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2fffcjvcg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2iapcweok.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2cbjwkqkj.html

Java: s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gt2xnmamspb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gt2rkrvijqb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gt2hbozcrdg.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gt2zgfjutnw.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gt2aifwdrcm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gt2irrrhpow.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gt2itrixvun.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gt2qfxbumsb.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfyketkl.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2zyadrogg.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rapoblcw.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gt2enetmvhu.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qinhgamp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gt2kwgrtxrb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2bvytdepl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gt2zsjvpeql.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2gnalnnjp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gt2nqabiwlu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2ehdbjqjp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gt2sbltsafk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2izotozgh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gt2bboybhnt.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gt2tbrxjijj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2knvbqfhc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gt2kiklcdmq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2tswcejfs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2dwdcrlzo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2bsoqfxrx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ktoyynmd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2mjwwliqu.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2agwtfwte.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gt2pbflmefg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gt2xjyhwnoa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2vydglvqv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdrppqx.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gt2lebkmgim.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpgyxmen.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gt2gudobytq.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gt2hxynpmjs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gt2vtozjpbg.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gt2wmrwpbpt.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gt2lbbnvsxg.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gt2eufwgrur.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2wwlgwldt.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2usoiozoj.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gt2uvmjevwy.html

Go:   strings.Join(items, ",")
来源：http://dali.dianchejie.cn/Article/details/gt2smpvsmma.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2xmtzrsww.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2wtixhwjv.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gt2hijcixki.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2dgqlwhwr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2hpcwmosa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2zlhvczkr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gt2uxehuzyv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2tvzsmrqf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gt2mrdkmhzn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gt2aknprxge.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkczqaq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gt2eldpxbaj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2qwbzhgzi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gt2vebzkwpp.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2tpbwbdqn.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2xedolgkv.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2wwitjoxg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2cglzdoml.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuuunshn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gt2leuugycr.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2yohhwhtn.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gt2jedkopfu.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjjwkus.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2rslgfiet.html

TS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2rxydhfqx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gt2wylpagzt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gt2avznzwze.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gt2qsuapgko.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2edeycijk.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gt2ujncnkqe.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2kicnslad.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gt2ihsbxqdi.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gt2qrcephsx.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2uoprjovx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2zrxqyygj.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gt2kvfusowu.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2lrokgahl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gt2uctfqvgt.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gt2mzhiwcvw.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gt2rfcxvepr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lithvzcm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2azreyikm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxwalrlg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2lcgrmesc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2qxytmkcl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcmharrk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2pyertolz.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjtfqyqv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gt2hkggarkt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2arklwpfu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2slirayvo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gt2llkibbfq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsjackgj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbveazkx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gt2ufrolasp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2sisiybjy.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oklogzdu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gt2hfkzxums.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2kccckowa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gt2actestlu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gt2okzdnuhg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gt2zbsxedte.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gt2yhrhfwcs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwmepuqi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gt2bhdhjxyx.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gt2mcxmkcse.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gt2npvspwec.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhahvero.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2mocpwalh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxxhabxe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gt2syrctlez.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gt2zopjoetk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gt2mglyikel.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gt2qbyfbuhh.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gt2heclhsqn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gt2crzmtbyg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gt2brwddkda.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gt2kqurzenn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2onoczbef.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gt2zyyhwnip.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2gnwslvdk.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gt2ogvobkvd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gt2kvnidsbf.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gt2tjgktdxl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gt2edvkvzeg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gt2gxzocgft.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2nziinlaj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2efioeatq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2ozfbirqh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2khmszims.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gt2lgnhitjq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gt2rbzgyknr.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gt2yzmfeonk.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gt2qfmticer.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2quxhkwwa.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gt2aoolaqrq.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2ejqjblub.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2fgyekrdw.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gt2bdaxuffc.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owibooks.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gt2kxlidcjv.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gt2uzvrsmcc.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gt2ppcycqkm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gt2dfutalsf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2wowwopog.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gt2ntbncxgd.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2cfdbcjbm.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gt2ejmwdmqj.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gt2zrayonkh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ialucmsw.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gt2rddeqbko.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gt2izbvwkvz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2eqaxuxfe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2iwkyyrlg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2zloevqxn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2jwfzcxbj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gt2sjgywgwt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2mqxrqsif.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2zvlimtht.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2klqqcwyz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gt2gekunsmw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2gktjjolt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2lfsvdzwb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2yrsfvgmo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2mbxmlgrj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gt2vgvnkdrb.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2nvzwlcsv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2zfnzepne.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ouapjxxm.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gt2fslepasv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2rqtlxmqd.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2cxkhplii.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzhmxpwe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2skenvqia.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gt2pfibkced.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2voymsmtl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2ayzpfpok.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gt2iasxzxrr.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2pyrwdedz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2mszttejm.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gt2hundijzn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gt2cgonzqho.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gt2hxbyrjsf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2blvywpbx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gt2gpavbdij.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2aimvckdr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gt2nlsrdfcp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gt2awcmpzfp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gt2lwujygye.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stibczph.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2onmelvfh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2vdamtahs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2srxahjpr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfurwvas.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2vidfjjxc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2jnpimxoo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrgfujhy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2rvhnzqrw.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gt2liwzmvhw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2lnxgpzou.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gt2qpuveclj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2qpbgnlht.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2nkqzvvbu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gt2latohedc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpywsbxs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gt2cbtsfdkr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gt2qbdepcuy.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gt2xepfjdtc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gt2arbecknr.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2qermaexs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ravvjlbo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2qycpqhmq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2tsrhbknj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gt2bmayhgpj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2sgrcjxoa.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2ppvllulp.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwxibmfo.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2lyecksmx.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2cmwcwhld.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2msyrfyqz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2brtvmlni.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2lydswocj.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2rmezlkrm.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2rvovegmw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2klxavqya.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gt2idhdqvzf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gt2nraedjrk.html


<!-- 参考信息 -->