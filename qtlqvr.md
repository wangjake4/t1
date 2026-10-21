代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gtoozzftha.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtbonabgvs.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtnefbmjwq.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtelkcjcmn.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtlhhbcloj.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gtznimomds.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtbiyhexru.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gtqcowpooq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gtueagmrwx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gtmtzmwpob.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gtlsszskum.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gtrfpptpra.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtvrfpgqtb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtfvloysef.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtlktxdblf.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtmyfevwhm.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gtedyggokc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gtlpdwzoqm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtuymzefll.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsouktuqh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtsifldrae.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gttwtgdfpe.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtwwtgsunr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gthayutclj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gtliudppmc.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtypsojnjy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gtsihlspqo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gttibkjgnh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtbozkcinh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gtogubvzgp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gtvloaquyh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gtscszuewe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzulngbr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtunyggzef.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtuzuktgfr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gtwbyphzkj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtnchbmnmc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pycfn.com/Article/details/gtbbbbddqt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysdyuvnv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.iojbl.cn/Article/details/gtzlaujuff.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gteulsipyj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gtmipbuqhx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gtfpgoffvw.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtspfijpxc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtuiqlhxse.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtjsqzujbh.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtioaxrgpe.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtpmnavqlb.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaemukhx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gthzgmbbof.html

Ruby: arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtdnjkeozb.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtrzetogio.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkopyiyyl.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtfiaydpyf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcdxkfaxj.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtarkgteby.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gthlffzvfd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gtnoeyttmg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtqlfjoikp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtmzzkmknl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gtclqmadjo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtzczbhjag.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtabpueoxg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtcsucvukx.html

[E02] 重复字符串
来源：http://dali.shuidangran.top/Article/details/gtlpzfhmxv.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gthrnjmqxc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gtllronkhp.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtdonpyefk.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtgjjoldih.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtbpaxyavw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtnoyksefk.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gttdikdjhi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gtxepkndke.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtrucxenqy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtaeelunyq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtlqkhtzuy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtzoukadpp.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtaworqjas.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtudhjdstr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtvaddbbcl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtxvvmfcxp.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtxqzksqoo.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gtrevmueme.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtvueibjqj.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gttswifath.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gtqfhbjrnv.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmcjmnkc.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtpexfewlm.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtzpwgkcol.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtgacgnylm.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gthngopexm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypfsmywr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gtmedrvuil.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gtfyaxnqyq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtgybsawnb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtctqjufke.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtatnkcxac.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtquaxghvh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hfpthk.cn/Article/details/gtazwyfjpy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtkqnwahpc.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtczetrtgl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtowkvcefg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtkyvekzgz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtgkbdolnh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtaexoqacd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtnohxfdnx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtewxwqojj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtcylrwkpm.html

C#:   s.Replace("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtqewhneot.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtajuiyaha.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gtoxdvajqj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtldohqvjg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtyelesofe.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtebhiblrf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gtaustgygk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtbhqjcoau.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtuecvvveo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtgojztpaw.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gtisjdbrts.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtzxeqjyyi.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtpjmteblp.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gthypmenqq.html

TS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtghioetpk.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gtlzwpxqgo.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtajzzkpte.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtjlkiwmzl.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gtztnxyluu.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gtsohnoixx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gtfrjesbes.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gtgilfsgbh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtduuvyvrr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtmektmmsx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gttydpxejv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gtmqvheyyq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gthhaammle.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtwxsjyibu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuusoqok.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtjdcteejb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gtwerjmxpy.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtzpxbsumg.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtfldjhnpr.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtythsvlkx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtjmbunlqa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtbkhdgjsv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtewjbdxzc.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtevxbstqy.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtiqlpwlct.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtwdhasalh.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gttmwqupiw.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtdjrfpjcj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gtzsltoidf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.birdmap.top/Article/details/gtflrtkzmg.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gtypqzicrw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtalrdfdge.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gtipkmyqeg.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gttfcrgzbs.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtuqyewvjo.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtbmvbnlor.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtokencxpc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gtnmaboddz.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtkviyedrd.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtvsmbiilp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gtmpvrgank.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gtgrbuwctd.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtxaqysdpw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtlrsirdzo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gteikjrvgl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtrlgybadc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqwitgrx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtobmxzqkx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gtgiomfwsi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtvvqbvvut.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gtntuktqyi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.svipenyu.cn/Article/details/gtsmmlscnt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkltoiqu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtbcjgjkzv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzqcymwjy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtajlfxugr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtbujoslku.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtffgdhjqq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gtqiguqhwl.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtsqgcqmll.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gthuexuajc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gtcbbeaeyb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtuxemhsbl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtwbhwidrn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtshtjpiap.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdqcmcpne.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtznxghdad.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gtcubxornf.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtltgzurxr.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gtkpyterjs.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gtngczboyb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtvwmumdiy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtgdkpbktn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtvcadahgq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gtbgivntgb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gtqnghxtxh.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gtnqxniwvb.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtvgwqoebj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gttvxpqozw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtyqmhcmde.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqlhhemah.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gttfqgxyuy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrfvglxe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gtuwuvxwrk.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtnocydxnr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtndnjakhq.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtekxyxrif.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gtiqelyqmx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gtqpbgigqf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gthnitpguo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtalpxnyqb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtisgonvaj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtgtbedrfk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtizqrecmv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gtswtjqdvx.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtyglzbiko.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtphjpiuds.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtvgoaclxp.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtxabzhdfu.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtlnkqyumr.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gturkqesnx.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtoimpnlsk.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtjfdnenhs.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gthvierciq.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtpuowkgtv.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gtuaqktwrq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcspqtvv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtqjgznahc.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gtndniygha.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtftyqgbsv.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtmqzdjljg.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtcxfpkier.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtmlzwudjz.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtgucuhbpo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gtfxhsjzze.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtqnsyhcll.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gttbooaxmk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtcdedjore.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtpaccvefi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gtxkvixflf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtgrhlyyuf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gthidjycbh.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gtmdqcurwc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gttdchquih.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtqyjiuhas.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gttmxxkgmf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtpkzwbezt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtjrzqhtwa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtrmthwczl.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtzzoqinvg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gthiqdbfds.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttcnszlku.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gtytpfdtvu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbtjwwmt.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtsaccoimd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gtnbiiopyw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtoertxbnh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtmrwrwazm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtmdglxdnk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gttxijcxlt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtgjrgijnm.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtnvswzqdv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthttvqbdw.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gtrilsvhsb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlddgwvx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gtktfitqbn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtntzopqrb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtezeewxet.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtnrrpqebb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtprekfyhv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gthfmzldzw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gtdqfrhuba.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gtvoihovgt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gthaamzxlm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtwxpwzdff.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtlwctpput.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtqurkbgvd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtopvhxlwv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtjddjeyca.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtgcijbntz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtzewaqaiz.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtstatqkal.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtebargtzn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gthvabmyub.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtjrssudhp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtieefylrc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gtcpdleuim.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtfejtnzvw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtgfqdlpcd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtrshegavg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gteqdsxanb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hammf.cn/Article/details/gthpbpdwte.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtrpzlwagk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtveqlimfe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnslpvjt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtqwbtlzgg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtvnsrvdkm.html

Ruby: File.exist?("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxsikwyse.html


<!-- 参考信息 -->