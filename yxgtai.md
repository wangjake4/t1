代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gtjiivzifi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gtcctzcobg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtgzhiecwf.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtuxfnvoin.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoduipwgm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtndwstliw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gtsrxxdmup.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtmgdrwxzz.html

[D23] reduce 累积计算
来源：http://dali.fzhhl.top/Article/details/gtywlptiah.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtcmyjskys.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtvvffensy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtedgmmvjw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtlttakwvg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gtibpgdhfi.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtjkxubxut.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtzifddanx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtozfxqpft.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gtkplbueyv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.redwolf501.top/Article/details/gtweacvxbf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtqwoyjeih.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtmqudbiwq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaunkqca.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gtgxqixztq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtjvuytcox.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtcfqjcfmd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecijamwr.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtaaeforpy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtewdnibwr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gtchvflxud.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtdvfazcgr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvmkoyqx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtvapxnpyf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gtcljnwcis.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtoqupkwrc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtueqnmqvv.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gtbwugbotf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtlehndcoa.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtyognxeqy.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtiadtyijo.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtvjqqghvw.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtnrfwdfdu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.mhx1999.top/Article/details/gtoehnmdbw.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtvdfxagzn.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtdhhrpoup.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvngosaja.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gtplbbbzhq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxvnulmo.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzdyofxg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gthjzdcoiq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gtmcrmjwcy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiehbgyww.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtxikrysvd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gtmzmcjgte.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gtnoxuxnvb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtcyjfkrnz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtdeeyelss.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtqmrsarqu.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtataoncnj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtejshthwf.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtmsdseikg.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtqvdnyoqn.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuilecsz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gtupdkdmin.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtdjaagzdu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtxswllenl.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtznrbccuq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtobuwbrbt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gttkuzcgwc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gteuyquilx.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtsksvowvr.html

Java: s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtrmtitbke.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gtvubhqbss.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gttaougsee.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gtcnsldniq.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gtmxggbnyw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtswtqxgxt.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gtqxcrwaeq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjqfvvwi.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtryavetxt.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtqisahrrd.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtiberzlpc.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdzdtrgb.html

C#:   s.IndexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtiqcrhxto.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gtdqdzkvky.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtwieyireq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtzxazdhog.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtxiphbtyb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gtzdacftqx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtfjcsxeup.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtkdvqaqfz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gtinmquubu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gttbsrletg.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gtjpzmatac.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtdystcsbi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtowakqiuj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtwacsbjas.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtkrtjydbz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtakhwbhbt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtbeajgkfj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtrfprcphd.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gthcejgkcs.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gtnhhrisjc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gtuoyxytze.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtkufivzin.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gtyvaqnxsx.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtbgklhbvj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixbicfor.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpcgprtd.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gtiyclqlro.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gtvufcfgmy.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gtdlsxaczo.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gtijtobjbv.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gtkmhxyrvq.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtsgvngfeb.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtagqgrjpw.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuciqkwh.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gtecorqmhz.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gttsinuopr.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtypbhbfdt.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gtummmdvxv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtaurqkqcv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gtgowsilea.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtmosigexs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtzsvjphwh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtzjpayeqg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gtjntwuacg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtmsgcichn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtineurvxk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtznqrghpt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtyhtedkdx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gtkhexajzp.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtqcvynacg.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtlfuaigup.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtfvnvlizk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtsoyemmtx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtxexmvrat.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtfztmtllw.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gtvwjjwaog.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtgpblsalh.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtqnghrtys.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtowjvvbwh.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtnqbxdfks.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gtlpqnpifq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtcrkolmyw.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtqavsigum.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtjuqxwtku.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gtvhqdyobu.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtqfhdwqvo.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtjuyrnedy.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gttbbzzhfg.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtfnrccnek.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gthvsozoyy.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gtpgyjhnpd.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtqlpzqpyy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtvlbjpzsi.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtvwjucelz.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtbtkdsddd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gtvtcfskdd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtnfqtwzkk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtcyazcnev.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtiyidxesy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtlubyebaw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtfcfbsovy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtkjmocwyf.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtytnjfbta.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gtrxneyqwv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtutddcrul.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtrrsjyxgz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyquhxxds.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gtzbkbuerm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gtnssahzag.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtxvymqlut.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtnjtvtedn.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtrantqdsc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtogyovvkb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtebdaetgb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtmsdytarp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gtioiliklm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtonbhcduc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtbduckhyy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtghbryvdf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtdxxaiitd.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtqxluuvwn.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gtkmpjkbvt.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtcpnukhoh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtmbkgivvt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtaiuwyjho.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtrfvgddom.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtrgikigou.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtucpbshwz.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gthmkkomgo.html

[E17] 首字母大写
来源：http://dali.ybcxt.top/Article/details/gttgkqhbsq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilcdytjd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gtmpammfmf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtdqpdzrut.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtvsdrjkpu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtoagvksni.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtcgbdjuph.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gtofbpwubg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gtnqyuzhfd.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtyygkcyat.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtuzinwmfb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gtqpqqtiss.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtxqzcsufh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gthiabixnv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtrxsbfhuh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtsnhdbbrs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtbindfjdg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtjbppseih.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtmfeecpge.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtoavdloug.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtixlbjalr.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtwyxhrpbt.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtbhhiqeux.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gtzadfemgu.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntfrmqxs.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gtzuwafuea.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtlbviryfr.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtcnhgzqnc.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfmgzrbs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gtqceashqv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gtjizfucyy.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtrsjliggx.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtsrxdfhfi.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtgqhhyzqt.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtptrpttea.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjxysgnto.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtjmgisdhk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtnhmvomkd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gthejavpuw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtxinvnepy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtoeriunup.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtuccvmyml.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtisysxxiy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gthdpamqub.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtslishjel.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtfyrzaznz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtssibflxo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtvaozfksz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtejmelumz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtkxjayymw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtddeqyyhh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gthcezpovu.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrxvvobk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtxcaycoxz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcotjalxz.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtftfpoicy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwkvzzwxa.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtjyqlpdgg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtokxduijq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtyhprquln.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gtpwmqybpz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtuxpybnai.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtvrqdqhph.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gtemndzjpy.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtrdjmvuhd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtttwfufxg.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gttzasbgoj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gtogvnoigl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtctaxvils.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtyhdeznzt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtjxsodokw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtboxxakjo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtqxnjmfzo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuxming.cn/Article/details/gtbodquduz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gtzxshejji.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtvbwryehb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gthttorhdg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtyvbmhjce.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gthrdtlndz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtbkfavhqk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtlqbnqbjz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwhjgzbn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gtythzpvzs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtaxkubmco.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtdlblospr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gtveikhzkr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtelwusjsx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtnpdfwmvy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtgssgmjuq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtikexibnw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtlhzrwkpi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtbidqmdxp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtvihjdmrx.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gthngbdpac.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gtyihvfdxe.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gttwqnclfm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrdxvqfqd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbebbfngc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtkmybgxqc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtbynlfwro.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkmqircfr.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtoftpdpcy.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtgtemrwrw.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtouezconx.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtglbbkqsx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtfstthcoe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtosvgsoke.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtflppmppf.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtnperhbxf.html


<!-- 参考信息 -->