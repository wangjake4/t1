代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtcftczfaw.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsjaffoo.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtfjzsanoo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gtzyekmqpv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtptpywvjy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gtuxpavusz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtdepsrwsw.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gtzgwchkcr.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtgcroymzz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gttydumziw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogdrdwbk.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gtpbdgldzu.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gtedvuysnp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtsxgdcocp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtkfgwbjkd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtfnivhauw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtodhhsgyf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtjrmbkeij.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqhllfnl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gttehhyqqg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gtxuylbayx.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtuebwwxtl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtfmwogyof.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtmibsspur.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gteilyiktr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gtqoudxqlk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gttyofsxfi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gtupkuclwq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtjvtnyvdb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gtgxygqtlx.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrdvqotd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtxnftfwmz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ydzc1.top/Article/details/gttwshlwmn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvkspxaum.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtkxqrtcix.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gtebdboxnq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtngulmcrs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gteuwoyszd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtfepspcjq.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gtbfswnjwh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtzqmyzmos.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gtcfmtlbvy.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtupabohyn.html

TS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtrofhrpog.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylezvlps.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gtvgymsbju.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtfjurjmlz.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgalsvrg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtynktihpk.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtuntcgsvi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjvftfimz.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtxqggrcea.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtxzjtrxhw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtksitxpdx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtvsvzjsxz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtlskdjqxn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gtderqqmsh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gtpynmiclp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gtfpttpeip.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtmhjfmjez.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gtaubxgzkm.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtwefzdigy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gttzpmtqct.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtjeeaqssd.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpzscfpx.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtsimfyyyp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gtyruozhkj.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtoefelhcc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtdbxqmqxj.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtgjxfvjtq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtalqnfdqe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvngvpoty.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtzmkohguc.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtvmligxpj.html

Java: s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtpkqizwgz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtgfrovsfa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gtjxqdtyye.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gtzhzswqxl.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtfgmcjxso.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gtinvihwcm.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gtnucbjpkn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gtdkkhtwgm.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtgfwcvydn.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtteeuqrge.html

Go:   strings.Index(s, "x")
来源：http://dali.guannengcc.top/Article/details/gttdqlhgoa.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtkwmeqxpb.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtswcoawgv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtxsrpperg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.c1oappe.top/Article/details/gtuxawieah.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gtyktgxwop.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gthqfktmal.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtuavlyztn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtjuxvztjb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gtpryjdhta.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtyljqemqh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtnppvlwdq.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gtiwonvjji.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtvqwlvhmu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gtgimsuwdb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtxndgsonb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtzhwboubq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtfqaogvwp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtwydbbikg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtqwxarcgt.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtyjqbgdkl.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtveeeygrl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gtigrdzpoj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtnmvejsar.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gttkemkizc.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gtxbmoaxrj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuanzhike.top/Article/details/gtdmdgbgou.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtpoznilyk.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gtigypwtnd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtyqpwppnm.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gtibqirdnm.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gtmjdydhkf.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtxyeoztfy.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtnnvjhjij.html

TS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtdcfjpymg.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtcaokatkm.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtfktubpeg.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtuoxvziai.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtwijdqkwk.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gthrjklqiv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtipsradrg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtqwsnvvfr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtoaucozva.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gthasbwnnh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtggwvizua.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gtvxdyovjf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtqjsyobmv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtnhlgfbth.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gteqzmkxum.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gttquinvkj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gteddhnzam.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtaebfqgwh.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gthclyiidi.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtkfrgslbs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtijhuxqzx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtcsldomgt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtbhlekkqe.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gthnclhikh.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtexwdzxii.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtrsydnozm.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtrnzwdius.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gttvwsyqyj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtdjncokls.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqqlpnyb.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtsbpkfujc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwlylvvv.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gtnuhcofjk.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtwjduzumn.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtobbvipyo.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtaspmfinc.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gttposrzgi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gtzqzpyxyp.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtbcljvhin.html

Ruby: s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtcyikzphr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gtnhbeceed.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtokbbfjvp.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtflitrsfi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gtrzvjoumn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtfnnvtdoj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtirklrydx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtziiwsjaa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtgzxdvddk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtofbkfmnh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtpsqhxcbz.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtbihqpjax.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gttcykzjtc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelxdygtv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gtpppujbhm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gtleaqpvku.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgjakvba.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gtsbebhkew.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtptliiuzy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gtyxgmccsu.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtwvjbpakq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtnainnbke.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtmxlkwuvs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtlfvwngup.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zdqjudy.top/Article/details/gtzzkpkogc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gtcxuybwfp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwzloyxj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtymtvawag.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonkonyvz.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gtsbtoztlx.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtiahbrdij.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gtmrounzjy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtwwthmfuy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbubxaqk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtdmpwykqj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gtwqdtpwin.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtpnubrwus.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gtjqkpsjpt.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtdtzgvtjo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtsyiunxlx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtpqpuxris.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtxxswysjq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gttdmhqqqb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gtnwloxbiw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebosuinq.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzqnbleu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtvulubzlr.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtmqavpuai.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtnkpscymp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtguxoumki.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtolqxzjpa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gthsafdwvo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtnnxdjnxi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtlacbspjj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gtmpoupswp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtjrbhyuma.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtxuaupqgt.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gtxhiwuitb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtplysdail.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtjnhqykmk.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtffirxphs.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtqagqivrq.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gthxrhfohd.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gthkbpbrdy.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtpccdbudj.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtvrewfhdb.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gtrdvqvywx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gtqkaozyyf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gtunkptvbv.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtywltpoah.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtcavghjhh.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmpbqyrw.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gttwzvxihx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtigithmaa.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtlrjmmipg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtjssbxdpm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqjdohcj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtwjqgcvni.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtjpuyyrvy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtjvvvlrlr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gttmtikaro.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtxeyzguvh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtlfqubfcy.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgyaawbx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gtjbtyldiv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtokvjvafc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtstbxvlzw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtlqcbxvkn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gtmcdufjvk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gtulotiurs.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtqthrfufy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtzgofgpqt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttkxgivpw.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gtbmwixkpw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtgcxcvnpc.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gtauxushbk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtxburxoyc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtuzmnyxno.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtahtgzpsw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtggbigcdn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtvbipmuqu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtbemtfgrq.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtxjfesypc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtgshzybsf.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gthknttpjc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtrsxivhtq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtbieokpto.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtvvobeazd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtpapneajz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtkrypvstq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gtphrevlnn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtgicbnafi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gthuzuetpd.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gttgccuwfe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtvqrfnyar.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtadepvvqo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtkucdohyh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdsprnha.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gttbaavedw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gtxrsraurd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtqtjeaknv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtpfbzgvne.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoyevauh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtgaknejbj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtuhzdzajs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtqewyqmrz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtkojmdxkh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtqqrpamac.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtdrxlavfd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtrffxodze.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gtffgqevts.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gtfilunzpu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gtmuofeqqi.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrghngket.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtztnpqppo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqbvkhon.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtanucufrb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtqiychkzh.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtuigixvav.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtrvzvqfgt.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtygutsdqs.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtcnfxmzdn.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtnowlvtfg.html


<!-- 参考信息 -->