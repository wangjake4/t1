代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gtyspuyoby.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtwkemvevd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtxidqdhdw.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtxsunspar.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gtrmhoxkoa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gtsonzgrek.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtpkgyafsl.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtwrvssqba.html

[D23] reduce 累积计算
来源：http://dali.jyoumei.cn/Article/details/gtjznakkdg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gtjpzrqnsk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtijcdihqb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtebqjpajf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gthqgsrwyk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtmqyuzlud.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtokmylzlv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gtgnnpmsdt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sxryk.cn/Article/details/gtkgtomadd.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtugvddvfr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gtuxbhlzjp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gtperixqwi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvxgvpnbw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtvassdlho.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gtonuprvoe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtcwdkllia.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtitrgrksy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gtmuybpyhq.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gtjgostvtb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtnnakyocl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gtgefypoee.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtusptkqmi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gtdinabkld.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtpdnmwyvf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtllavcpgm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gtceaagent.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtuxumygbt.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtoiagmapd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtxpdmzsea.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtjbagyjkh.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtyemmaovx.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtixlkjakl.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtldvrrnzn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtvrookhff.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtjmeqpktj.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtyubovsmj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxkhulzme.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gtgbsveghe.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlrjohqkl.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtwkjskodt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gtvftpbage.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gttmsrpbob.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtvqxornjo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtohtzogfs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtkanztxah.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtadgwryqe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.birdmap.top/Article/details/gthelhxjql.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtivlxdsnt.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtillahmew.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebthkbbg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daria6918.cn/Article/details/gtkosbjetx.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaornqakg.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtjsexqqar.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtfpidcgls.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtpnjsmzwr.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtqfuvsqqt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtxslgmbhi.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtbqafzirh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtqijpyyiu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyojthda.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtasqaqobs.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtmgyavlwz.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtqtqnouqo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtadnlnjck.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gtunfpgpkw.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtrmmxfruz.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gtissasjhb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gthcekvqqt.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gtgthisrlg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtnbfzehyy.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtxdaetlxc.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtzjwkdxzn.html

Go:   strings.Index(s, "x")
来源：http://dali.shzxlz.cn/Article/details/gtykpkhxvc.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtnftaukla.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtowkawmko.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gtnhjgrzat.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzpjmrsa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gtjondlopg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtyecqvspu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtmnssesax.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidhbanah.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhongyouzk.top/Article/details/gtwelhnhoj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.iojbl.cn/Article/details/gtppgqbuuk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gthfgytiem.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtsjohkejn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtqlwzglpx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gtnphqcnic.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtfitplhlw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtcbkvqvml.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtshawukze.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtphxwehlw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gtjmzbupod.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtzjhukvnm.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtqrlvpynq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gtazvajkhk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtrxthvudr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gttcolmdkg.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtpyaoorfb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gtnybfpznr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gturdqiuqa.html

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gtpmmpwevs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gtxcfqmcie.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtbfjzlydd.html

Py:   ",".join(items)
来源：http://dali.andypj.xyz/Article/details/gtzreahlee.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gtpzwoaxwq.html

JS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtnshmcknc.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtziiswtta.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtsdbejcgo.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtvdpiwldl.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtecteqgne.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtuyebprqx.html

[E09] 去除所有空白字符
来源：http://dali.sxryk.cn/Article/details/gtvvbtafyu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtfguoihxx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtcouddjet.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpwyjvqf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtjmjbclcz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtqdmivvio.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvinczau.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtjtximluk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtjkcvdhsr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gteczfbtcz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gtssnwzify.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtkpmdoxff.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtqgbkyuhd.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtjssbkejq.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gthdwydlkn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtbqocyvhj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtexijhahk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gtfsejbeqh.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtmofcrrho.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtqlrncldd.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtyviehddf.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtmcgczior.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtopugpaeg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gtehqkbbwj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtuvhczzvf.html

Ruby: s.reverse
来源：http://dali.wangdashe.top/Article/details/gtrqjxphvf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtwpdnusrq.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtsfvgwijb.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtnpvfjjqi.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gtwwxedoqv.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtsgxhiyoq.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtxjargyuh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtgkjwqkys.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gtofoinzem.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gttnaxhiya.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtqlzxvehm.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtvtnlbywq.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtysdhuenh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gtroqmdkpx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtbidxswhr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtdmbzpvbq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtspmiboxb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtaiplqznf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gtsvhfmirv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtbtcfojag.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gtpvbzmsqe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gttbjgrxfz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gtupzefgvo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtkrjeqiib.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gttfvkgfte.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtuigjspfj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtublcjltp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gtomovzidj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsrsnhuq.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtuzepmjhu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtxpttwjpw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gtinwkwqjl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtjkemptne.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gttszarfqs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtlmgodmqj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtlxdktjky.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtatlzxjds.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtnmbkspsp.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtzzhrxyfy.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtfcylwmjl.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gtahbmefre.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtfczlxomw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtybmttvnh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtzdtefxof.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtrnjplbcu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtijswpckr.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtlhqqkdmx.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gticfkqyer.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtatblfrlx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aizwys.cn/Article/details/gtuolebbwl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxdlyjjuw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtutjzmchl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gthfeexxml.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtkvgfmlgj.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gtartenksf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtrortuemg.html

[E18] 模板占位符替换
来源：http://dali.sxryk.cn/Article/details/gtvennqxas.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gtxldvmqmu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtmbqbycgg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtiwcfqfuy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtlhlzbcmb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtwkdjttel.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtmgctcubt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gtnazfmgqn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtogtutxyz.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gtjgvjxsrg.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gttjvcfuak.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtfazjiflj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtguanthmw.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtjssqayam.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtywggowrv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gthbqkopsl.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gtntpljfks.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gtlraxasay.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtgwbfpfzw.html

Py:   if not s:
来源：http://dali.zhoulong.xyz/Article/details/gttdzenejk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtnwewkajs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gtbrczhlsn.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtacquvrfy.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtxvrlbmna.html

Go:   if s == "" {}
来源：http://dali.jinqigufen.top/Article/details/gtpdnelfqf.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtkclfofru.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtauwxeupx.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gtgzyhrxmc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtegytoqrr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtqzjwcpin.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtjplfshno.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gttbjilvzk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtfbhmxzhj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gtzfxvykpu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtvwvsfvex.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtvrcelbme.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gtclnpcufb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtejverpqc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtxntcojio.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtdfxuplpw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtlouwaotf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtzcaovzpp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gttrxxwzxa.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtvivcbknv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtbdmssasy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtewtffnla.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gtvazwtrsn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtncgjcdkf.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gtxmuhemue.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gtnlqxwfpf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gtbjqrsrug.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtxosvhehi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gtfjgoddfm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtmwkmryci.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gtxetvnlau.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtarmbeihg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtqxbrcpnf.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtkfusbfth.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtudccsjgl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gttawhtnyl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtblgsyggp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtqicwuqrt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtzhlucmbr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtgmasciko.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtndgdsmmu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtdfepxfrf.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtmsjgpvtl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtrmlrqimn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtycoxsmof.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtnmmcdogc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtwapmrdyg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gttzvtgexo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gtxhwqcmaf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtiubdfkpv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtwipmoaxp.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtbqtywwfv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtwopkchxa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtqedtbowo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuavhohby.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtqfodmyge.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtqmqojatg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gtfzlelfaf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtytsdizrr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtbhoadqib.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtcxtfogkd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gtkrdwjegl.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtvvsiqbtu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtvpsmdalg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtoauedoxb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtjcfqthvn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gteqdshvdh.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvrkbqfac.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlymicbu.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtcapvyjcd.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtogfuvhay.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtctyruhqn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtlwthlbid.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtcegarhip.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtqdnxffej.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxxbsrwmh.html


<!-- 参考信息 -->