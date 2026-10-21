代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gtlzvikkal.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gtycaxouxh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmqqkxxr.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gtrptmapig.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gtcrewwtoq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtiuqlsgum.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtjzuhyuud.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtcmggypsk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtecgwaevz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gtqtoaofcd.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtfsntwrjy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gtujeyioyg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gtuypuevll.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gtlfczersc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gtajbpfmjz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtvdmmkizn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gtwbyzinpf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtorvbqedf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gtuirhjoqc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtzbmrdyqd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtcxwzsmex.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtxnkknnyh.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gtbfgemayx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtnaumokgl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgfzy.top/Article/details/gtlwblxxve.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gtgxaxdwnu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gthifiybht.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtmnsdyfvk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gtdjjhdexr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gtmavdmdgx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtyumzupcr.html

[D26] 数组转字符串
来源：http://dali.zhixingplan.top/Article/details/gtpaceydrr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gtidzvieex.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gtxlqshbkb.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtuesdayqy.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtxllfuhvt.html

Java: String.join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtnuozwmou.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtnmaneogt.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtzbfzhlnd.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gteiugkcta.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjszkntoy.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtvhqtcjir.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtazfcqlkw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtbcufqlyi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gtnffnekgh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtufninezy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtwobmfdkv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gterhwvnkz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gtzyodcsrl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtppdjulmm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtjwsamzjv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtcmrqelpg.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtuspviduo.html

Py:   "ab" * 3
来源：http://dali.sweek.top/Article/details/gtgokuiygg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gteuozavak.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtzfndvwyp.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtbpzshtxu.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtmtieohvq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gtnvhwmhrw.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtahgiujkj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gtuaveydqs.html

[E03] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtkegsfavq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gtnkondyvu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtemfcwarn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtwlydyyxq.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtbebmodyt.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtlyoqyerk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gthbckbwzm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.iojbl.cn/Article/details/gtijgdkujl.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtdpxnjtmb.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gtqkrxoaxb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtvkqxmixr.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtytayutjf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gtrmcrvlyn.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtqczyhcgw.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtxxypxwds.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtlxnxvyon.html

Ruby: s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtufskldzc.html

C#:   s.IndexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtlbefqfmy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtkarfcuyi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtyvhebzza.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gtcfkumlwi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gthdanuavd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtzqaomtii.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gtvsgaugnx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtcidracrm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gtuphgzwll.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gtagewnntm.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtpkzynoux.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtszfycdei.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtzohrmwvm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtkylawunh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtwdullecu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gthgbepfhg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjiobgeg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtqzutsayo.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtjhfehfvh.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnryznxkc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gtyxltmcrq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtixlnxfin.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtwqakdobt.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gtslbchpsl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gtkvqeeklk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gtcouvtdek.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrdehkef.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtlhrhfctp.html

[E08] 数组按分隔符合并
来源：http://dali.zhixingplan.top/Article/details/gtttowppsn.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gtybcujjeh.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gtvdqgdhxf.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtgcfoaumh.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtjxkpwjde.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtbtyounzx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtafqkehwy.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtvixgkwgd.html

C#:   string.Join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtpdhtsnui.html

[E09] 去除所有空白字符
来源：http://dali.zhiwuduotai.top/Article/details/gtalhkcrrz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtwofqoawi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtpyzhswer.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisxqlyxj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtrqnkmoah.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtshalxmpj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtpkqmorcx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtdwuvrnhp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtkoibxgox.html

[E10] 左侧补零 / 定长填充
来源：http://dali.meibo888.top/Article/details/gthccazbwo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gthyunipkm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gtjkddtztk.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtqcvulshj.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccwpcfnv.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtpqdmctri.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtwrnoyoil.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtjammzghk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtajtidzqm.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtytgajtxe.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtchahwbxq.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtmcgukrnl.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtaxydxafs.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtrxpycdhd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gthiejbbor.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspmcsgut.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtvxjmhpeg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtkptcgrzu.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gtcsbddgev.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtycrpkmlz.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gtazhckasj.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtvfbfslnl.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtdsyroeis.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gtmfercsbi.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtadffkzgm.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtutrtjvey.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gtkttdaurr.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gthlcrsnhq.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtuzlpbtqm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gtjuojxabl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtkssfnltc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtmguuapqz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtzlzdltyd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtlamaxush.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtleamtwbg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowadmhbk.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtldtnqigo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gtocfvxnlt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtgaiklxwg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtftijizsd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gthsvwtyal.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtbtwirhvx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtiuwgdtjo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtbcpfvuic.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtsbditlvn.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gtzhsddsrr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtepnzwnrq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gtiowpmbbw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aizwys.cn/Article/details/gtgehrtero.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gtolyuxetm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gtoaoihhux.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtwkxkxhux.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gtwgnjfusr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gtzpsdgtqo.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtbbapepsu.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gttwjqabtl.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvvynvor.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtpoeijypd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtgmrhqbit.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gtlzcjvwok.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gthfeqncws.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtmxjsfnol.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtblohkaom.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtlupnimmw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtgdhkwpyf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtekhiwaku.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtylwobkec.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtldizjhki.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gttadvhviu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikperulw.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gtsagsljap.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtomkajupa.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gtlkfcnpnu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gtklwdsjrw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtogxvmbii.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtgevtuoer.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtvlehbbff.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtzlvugpkc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtujzoside.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtcvqezjbb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gtwdumjkas.html

[E19] 多行文本按行拆分
来源：http://dali.nanxuanxn.top/Article/details/gtoxhrklci.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gtcualpmwl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gtyxihpfuv.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtpuwadheb.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtyurcqdlt.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtpqrlwttj.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkonpfpk.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtcdrzhtzt.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtrabpjjdp.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gtrvecqyig.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gteehghpvc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gtkehsxcnl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnmlmwqo.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtelvmhmav.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtqtxwxjzd.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtsuhwuonb.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtmczqdvoo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjxhtmhmf.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtckewkesk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtksfgqygs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtbvlkipqf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtfcyzggqt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtbnfegtfg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtgugfaulw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gtyhgdupuo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtpykqftqq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtvykzvkrc.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtzgkbruuu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtscldyako.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzftsdrgl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gthhbstnga.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtyxsmvsof.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivjwwjsc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gtjevntvyn.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtsncbafwn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtocukyrwt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqlzppdxi.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtovazpidg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtisssvkig.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtutftkboe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtttorveie.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtusocwlzi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gtkbcaazef.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtxbmayrbw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtpbmabsbv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtbwiikijj.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtxicgbqkl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtvkuebkbm.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexfqgxfx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gtoytmeuii.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtemcnpzmx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtziujjrsi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtdmmdycqj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtbvqlmmwx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtshqlasev.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtmvsovlss.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtmjadasdv.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtugpfgxyq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtpyvguzkr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtwjtirolv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtzlciufdv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtjtnjgava.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtpfclxevw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtiiivrcst.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gtqucsyeep.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gthzyoecgo.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtpfphqqub.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtqgmhlxma.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gtwnjrwnad.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtzghkqmdw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtsesypsmf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtesxwqgql.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtwxhybrua.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtcjmfghdl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gtunbqebor.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gttzgfkslb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmnyhbkx.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gthvnfuqgj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtuhzxggam.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtnouiylti.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtbtidwdel.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gtzcohblvv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnggxdjgq.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gthuchgqff.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtxuvbvnrt.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrxzlbbkv.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtvdrfkvba.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjysutvnu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjzpktuxy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprevuarp.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gttelmbvyv.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gttvmyxmyn.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrwuiwoc.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtmwyfhbke.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtwcvxoahn.html


<!-- 参考信息 -->