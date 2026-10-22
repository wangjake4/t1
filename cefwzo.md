代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gtroymhkch.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.9152youxi.cn/Article/details/gtykaebpik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gtxuwomgeg.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtvysbixex.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoauyheyx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtqoelmacf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtpiyjlmok.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtjdbunicy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gttkzdzssv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gtasqxmlkr.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtckdqyefz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gtvzckdajc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtulzjstkp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtvtqemagg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtyfokpfer.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gttvpraubf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqqszrdd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtvnndyheq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gtrivemewc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gtvehpfpzs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gtacvmerko.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gtkuqdwlqe.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gthtchblje.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gtwsaqojyk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gtnrfpimyu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gtwrldhzcb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtfqlljbuq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtlencwbxj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtdifacvjn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gtqklkgdjo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtqzkhrtte.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtkbcnovgy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gtwakfyhtv.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtqwlqykda.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtgltcqjdt.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtrlewjidw.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtwjmrvrny.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gtcufeeuhp.html

Ruby: arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtlnxwwahh.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtdvvhxmkm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxmetijpd.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gtzgzyxlam.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmsntsmdd.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtzugenozs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gthezsjknx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jyoumei.cn/Article/details/gtptbecilv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtvpdbipoa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtboqibatc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtxdhfuzob.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gtdnecqmhz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gtvqbbcetg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gttueypdmw.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gtqqtbsvwr.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtcxpmvupc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtfhmvuojz.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtgfwetrvq.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gticjeatgt.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtklgiznoh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gtbxhqikfj.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtfeszffql.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtsyxembrt.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtbwswuhlr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gtowfrczrs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekdjixgk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtnwnvoywo.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtsouuoxpf.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gttdwuylfc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtizizsacf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shzxlz.cn/Article/details/gtccwenkua.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gthvjlomte.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtdjpwmsxk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtkchpyiwu.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtztwtqnrk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtyocwpgcn.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtzsrhiabg.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtndxughhe.html

Go:   strings.Index(s, "x")
来源：http://dali.yueranfly.top/Article/details/gtnljuctoz.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtnzasscdv.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtatbqlfqg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtmqyuvtgb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gtpszxngnv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtxyczcfcn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtyfciqnth.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtvmgajbfn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzfdogqv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtcdgshixc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gtyevbblrt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtciaxsuri.html

[E06] 替换子串
来源：http://dali.gaohongyu789.top/Article/details/gtigdqxgmw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gttwvumdrt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gttqxcxthz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gteehnxggj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtevstzlot.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtbqavwjwn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtvaqnmxxx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtkvspwycj.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtkbyrlqtj.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtnixizzha.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtyeaweiaw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtywycclpp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gtetthqljw.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gtwcoxxpmm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtsnpoveau.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtqdgwdhao.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gtjzfbkarp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtiakjotnd.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtpnnykpri.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtibjhaqsb.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtdjpccwts.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtkktkxaqc.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gttqgicohw.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtonrwqicx.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gtkadnjelh.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtydmppjjw.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gthemsfapb.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gtxcagtupf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtttpuiouo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gttmqbvmin.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtnmnuxoyw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gthgfzimpq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtqrszmlfq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtftztnjqc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtcfjzthdf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtvidtrolb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqzfwlzv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gtdvasaqzr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtbddlbuwi.html

JS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtczwraybg.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtygeqxnhg.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrddhwpx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtkyxawjco.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtyvnicumw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtkjdojtss.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtiqdsfjsg.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtkimhdvzo.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtkepmyxqe.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtujsoeylv.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtjwdejnxp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtxktgqiev.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gtufhuoiwq.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtkxxxubpu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmhhgbae.html

[E12] 统计某字符出现次数
来源：http://dali.xylfe.cn/Article/details/gtodqwjfsd.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gtpzfytrpf.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gtdjtcaqrd.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gttjutbtqj.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtsqzaijul.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktumrqyy.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtbbhcsfax.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuydlhpes.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlvjhyzn.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtbcuwiier.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtvsapqlfd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtuownergx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnblzcgbm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtttduljks.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtzublcsay.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtivytmsyh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gttjmjfuaz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtsbdusbct.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gtlswkoysm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gtfnzefpsa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtkifqdxba.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwziwuiu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gtbbbsmwbn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtxjlncddt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtaptmslpl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuxming.cn/Article/details/gtbsqxwcfl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gtkxzpxslj.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gttpaclwob.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gtyrjvhfbg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtofvrddex.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtvgvtbyrq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gtvrhezmsn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gtsnpsesiz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwgvvrnvr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtktyohgmf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gtvzgevdes.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtthupnsno.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gtajeqjvlp.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtnlindrec.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtebmpnpyc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtkhylwets.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtexrbrxzv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtkbfrpiqj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gtsoczjurl.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gtestzkzfm.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtyvqgafnk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmgbofyz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gthlrlmatn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtsqnonmfz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtlkbqkhdk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gteqksuxaa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtxwzeodvp.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtkcudnqnb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtbqinptfr.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffurdbjk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gtqjaqwoun.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gtqsazkmcj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gttnqzgixq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtpyvhpiss.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtztxuzbzq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtrktadxiw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtwatzawfp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtrrpgbohz.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtlymyebcf.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gtbhgxjtta.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtgmlsinmt.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtdncbiodo.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtnphnwkyh.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gthasicwkh.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gtqflbqsdt.html

Ruby: s.lines
来源：http://dali.jinqigufen.top/Article/details/gtplckrhdk.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gtenogdyym.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtjkphumnz.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtuhgxhkzg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtivtuutsq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gtfmcaxmph.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtqqtiqatt.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtnodrrgze.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtisudlkmn.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gtrgytidne.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtextmsees.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtrilvqasw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtozqqsbov.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtvzefbmfh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtlmjhdnvd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtueyifuye.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtotnioaih.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gtghnhprxe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtvrkdfeyn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtpjnohrnz.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gteesbxbjh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtkbtvztgm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtlyhwtqyr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtrbmrmoam.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtkoohlrtw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gtcpqeigbr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gtkbdznbjz.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gtzubugnfr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtiotbsdoe.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtoslowamz.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gticqjcyxf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjrmhbtlr.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwskvrjkb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdeitmid.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gttxyvnawm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtmypcmkps.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtyptqjknz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtdaiyttza.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtipynqcgg.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjdmtxbap.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gthdaxcztf.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtchqqrbfo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gteqoirxtp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtcdwrehxp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gthqluatmw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtkqqdfvwh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtzeulubwa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gtomkorrvc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtpgghxlxz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gttyidxedl.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtkhkylzbu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gtxivfpwiz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtotvbebnz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtzcfonpjt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtrdpvrbkm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtntzqugxt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sweek.top/Article/details/gtabcnakjw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gtnmbfdupp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtbpagpdfq.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gttnfflqwf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtaupgddey.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtukjjcjkk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtzorsynqw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtypxrvkpj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtxkjslysq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gthwtywblz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtxhhjfqqx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtbfzzmvez.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gticubzulj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gtwtwlkrjs.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtwrfykfvb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtirkrxkiy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtiqyeyjly.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtdohrunac.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhkqaizu.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfaskkbhb.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgpzigybo.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtjzxcbqum.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtlimibjmy.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtpuvahfhw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjomnzomu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtswesxnmx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtfctattvc.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtzrvtzfru.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gthvtmrrdi.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtkkuxcxec.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtczwsdzhu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqqaimdg.html


<!-- 参考信息 -->