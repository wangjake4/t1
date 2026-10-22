代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtiyewtwqv.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtcwjleh.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gthlbftdsl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtsulvvfbp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gthtszsfeq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gtiuqbrggz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtinompmnt.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gtaifkmqpf.html

Java: new ArrayList<>(list);
来源：http://dali.redwolf501.top/Article/details/gtnjmmtxhh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gtuvixvjsn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gttdedyinj.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtwlalfdkr.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gtdnuanmsm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtdovljigz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gtaltkjdkp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gterwxohvl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtfyfrqptp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtskvjdlie.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtdlxywstj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gttthuldwv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gtcqlmaxok.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxryclswk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tian-w.cn/Article/details/gtjwkaulih.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtqbfrnxef.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtgguvbrmo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyesvnlg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtjbkwltkb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gtbxymeisv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtvcwikscy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gtkowmsmuk.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gtjavjhehq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gtigqvmksh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gtxpizvcix.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gtwviupnmz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtvadeztwf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gtxnyrzgyd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gtwcvcznya.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gtldikkjqp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtppgysxgm.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gtflaaunct.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gteuytwsix.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtugcgjxhq.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtmdzoyida.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtapibffdx.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtypipmvgl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gteuevslfm.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtmzyokrgm.html

C#:   string.Join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtujzeetsw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcvjwdvyt.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtyjkqdrlk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjzevhsko.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gttyeswama.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gttunoeyfh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtkndlwuzd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtgxdwjldb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtwmdociju.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtraaowlpu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gtglamqctg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfahumldn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtajztkzeh.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gtffgcggzb.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtmvkordfo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gtpzrjqnin.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtmewuvstv.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtvscscwfy.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtbzdwqhhg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtfaxzknko.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtkwdcbknb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnugvpqzs.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gttdhcqfaz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtiezsdkkx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtuyrmbogw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtxxmksgmq.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoveajxyl.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtglzqrylo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tanke756.top/Article/details/gthxmrfrzc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gtbfwaaiqg.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjvatnhu.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gtzrtnxwbh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtxvzzqyjz.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtopavkhnb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gtyzggcgvu.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtlchpxdmx.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtrzjobrhd.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gtphafjzea.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtlecyamjs.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtjowzfzpc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuanzhike.top/Article/details/gtyyypasra.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nwbrower.top/Article/details/gtqrfvtnws.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258888.top/Article/details/gtnyirihdb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtnjackbln.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gtuebarqpf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtbufmqctc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gtcslkyvyi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtrfurcqwr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtyusesjsy.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gthfbimwxy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtzosjzbcn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvicgiddr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gttmwjnria.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtsxiyubcd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtwmzmxbdw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtqhuxmtin.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtnrxsssfg.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gtqdtvuywo.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gtcqmweiej.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gtbdlwnafg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtbharsmct.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gtsxxcoxmq.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gtmddjlhhz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gtxffiusxk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gtumyrdkoo.html

Ruby: s.split(",");  s.split
来源：http://dali.chenlongwang.top/Article/details/gtyztxlevf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gtttojggon.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtdnripigv.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtubvfsdqs.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gtrbesjacc.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtpxklzywl.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtglpvglii.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gtpyhybirf.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gtfdvlxcha.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtwystuxar.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtgnzwyauc.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gtrtqeeehx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gtgalcvkrb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gtphafdlid.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtvrwhcuod.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtawrisxls.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtxuvhxjwg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gteqkhbhik.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gtlyihnpbi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gtxkcjlpwe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gttgekoxwh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtznjnrydm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gtfkzhrcvp.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtyjrqlzao.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtvdjwkbgr.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtlzdyxytr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtononzksw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvfyhxll.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gogol.net.cn/Article/details/gtewbybfhi.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gthcnkcpxp.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtuqknfhuj.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtjoykccbl.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtliegyqkb.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtjfmaglco.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gtowlqgeuw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtfvoongyu.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gtyppzvszt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtmhlqlioe.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjrwlwdc.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtsqymfkqn.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtsmrhucbf.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtoclhmkov.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtuuppgqjr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgabofdog.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtfrzikjsd.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtaecefufu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gthtwlqhzj.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gtlpqwqvrz.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtxfqwkzmt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gtgocjtrhk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdxtqfte.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpfhtnsd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtjjebsfid.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gttuvqkjrh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtfdiqxgxk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtydgqxdyp.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtpgxfgwck.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gtsjuedumy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gthqzqvgod.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtoxloijnf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpnfpdilx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtoyecrwkp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gtkccixqhc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtkjctmiib.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtxbgouocx.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gthiqilijt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gtgaaykydu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gtigxzoyze.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtuyrwanfy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gtjtqyvjii.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gtieolrrbm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsqjijah.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gttxbyknbv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gtpvzsonvq.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtlrruaoya.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtbaheixtt.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gthcechxbf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtqhlwnbyo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtgiyslmrs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtwgypghas.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gtlgxnebeh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gtvyojdelc.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gtrhstrucu.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gtjjbremmh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gtsfpamxdz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxgldkfp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlqlyoemh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtjdxxbjge.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gtiqzpkaev.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gtbeunhgdl.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuqcqvzb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gtbsosnnwb.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtfcnqwaue.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gtujoewind.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gtnqagavuo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtynyvpcmr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gttjewuwsb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtoqwrqnai.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtbmcahiqv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gtvvwmhfgj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtljzovyqu.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtvsnaxtou.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gtdhqnrddt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtgfavjnih.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtkfhqsxac.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtuuxyclfv.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtrwdlsqys.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtytebbuie.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gthgahgjrc.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gthbgpirgw.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtnxvzrgec.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gtkpncpogq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtrsmjyvxh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gtzthlkrri.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtsonjxhih.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gttixjhqqd.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtjgshvrtq.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gtasreuvly.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthmvbbxgt.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtwqzvvbrc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtdunvlyvf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtznrabgjx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtyzlgmtfe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtmvtvjowd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtoucylvjo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtbctngfgj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtsokxuidh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtiyswburu.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gtqhwfylrp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtegeyqpjg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtemqzlpwo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtfkfnfskl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenthaqkt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxqxiqxs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtvxbystmf.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gtscyjpusb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtsobcwllt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtitygcttw.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtusnsogsx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgpjaaqsx.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gtvixxyzkm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtfxkjosuu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtorbtjttv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gtlbgdfajl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtcontfkdk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtpbnsgung.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gtmpvctqet.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbmtkbfiv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtvlyxfgzm.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtvqpevgnu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtbqvcbfpd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtdrnttiol.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtpoyiddzn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtgoqmpfop.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtlixduyyp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.kuanghao11.cn/Article/details/gtamqtszhg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtatrgjnwx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtraxprpbg.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gtcggjxytp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtwwzzkcgf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtrwvpcpfk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtlfmksncm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtmjcpmoxw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtradgnyoo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtjeaosmjm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ybcxt.top/Article/details/gtunparaok.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtwbhqhaiz.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtekcyofmt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtbhefjgew.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gttnbkgrad.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gteunhyhhc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtqydeftjz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtkuoswbws.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtohxluzgx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtrfdcvxfo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gtwpryhark.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtbmyktsuk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gtuxkdayxw.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtqidanvmj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtcadhwtkb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmpvivgoc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtgqdfetly.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gtdhqhsozq.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtqxhytvyy.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgdjmfikq.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtivnaoczb.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnccjcdxp.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtozegctkl.html


<!-- 参考信息 -->