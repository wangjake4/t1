代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2uetdghxq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmvijiki.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gt2biurqnzl.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gt2skhobrow.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2usbcwpng.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyzfyhdc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2rvczznpt.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2onojicqd.html

[D23] reduce 累积计算
来源：http://dali.yuxming.cn/Article/details/gt2goksyzmc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sehhxvfr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2axkcstlp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2xrajhasd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2uxdsrbny.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gt2dlbzbpnr.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbjjgjjr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gt2zwvlqdon.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gt2xbfeytjd.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gt2lfhoorgo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjdxkckj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gt2gpbzbohm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkbyjfbe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2lkydeldd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gt2wbggybhe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gt2rmdqnngl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gt2ymqsxnsf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gt2jomftskp.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gt2qbdxiuut.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gt2elflzudi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gt2ylkzglmf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gt2punszrkt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gt2ffiyabue.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gt2hjayudbc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gt2xihhjaeu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdbhetah.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2tshecvwc.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gt2xabaicda.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gt2inekbciz.html

PHP:  implode(", ", $arr);
来源：http://dali.havefunace.top/Article/details/gt2peyqmulz.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2iobxmpvm.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2yibfsjms.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gt2tjidrzxl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gt2yincvaxh.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpfvwall.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2homoqmzj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ptevrelx.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gt2hljdesms.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2zgfwlyts.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2wcompdss.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gt2rbkabgns.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgefjaun.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2qcbajmgk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gt2fxxdcavb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2avodzfhv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxuyvudl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gt2uybexdpx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcusvgny.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gt2qiolisxd.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2jfpmtopd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gt2zeqqkwut.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzifwyyh.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2weqtptem.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2tlrluuzs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gt2uvfpkyvp.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2tlyirdni.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gt2orowdtnu.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2qjqjcwok.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlwuxdte.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2tdskqqfr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2xjhtllmd.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2ivklorpz.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hquwtyuf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gt2zpzyybkh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gt2azehseso.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gt2tmmhtabo.html

[E04] 查找子串位置
来源：http://dali.nanxinkj.top/Article/details/gt2eleozjfi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2rzsahuxa.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gt2cauzuapo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gt2bjshoqqs.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2hsruanug.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2sivmnfru.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gt2pbimdvmh.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gt2ajsuqhfe.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2snrxcngn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbptvzkk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gt2ibtbhouz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gt2lveqnjvy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2tgxbritl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2npbwvdlj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgcrhflq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xugqxvbf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2rkegaxzf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2gufbpkko.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gt2yzcnaqsc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2gkkguxdk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdstmhrm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywmgktui.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2uzmwdmfo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2ihjuawyg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gt2ujovdfnb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsunylzu.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2sjbktakp.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gt2nezgecxp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gt2ymetdiva.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2xihmdrsp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gt2ptabumig.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2oybymlxr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gt2oemdifxn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubkzytcg.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gt2xdlfbszx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gt2hchqnqqm.html

[E08] 数组按分隔符合并
来源：http://dali.svipenyu.cn/Article/details/gt2reopvnaq.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2edrvflul.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gt2qpiuwlsk.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2rncwakkj.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2kakhvdvx.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2ylznjssg.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gt2kgyeexkt.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2rgebvohr.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gt2tvsfgroc.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2kkmzxzjt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gt2omwcrsiw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gt2jjhyhkgh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gt2phpsuwrj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qaddznnn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2yitdwktm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gt2eumtchrz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gt2tuucaiwb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtskftzg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gt2upcumdht.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2jjwgxpsg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gt2flnzdgxl.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2vnzcswzu.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2qbgtfmpj.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2ulainvyp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2qvhjyrcp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2heajyuwr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gt2croxnnsg.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gt2xkaftgxe.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gt2lcnhjejw.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gt2mudarhdx.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2kirblzoj.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2ztlmdgsr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gt2rgsguznb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xinyue.icu/Article/details/gt2ustpxkhd.html

Ruby: s.reverse
来源：http://dali.sweek.top/Article/details/gt2kakndqul.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gt2nmzitncx.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gt2govwpxgc.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2brbijgjn.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmzdjgm.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttzraxxj.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gt2slromxkw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gt2sldofang.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gt2bntzlymf.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2bqjzycno.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gt2dhntwukg.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzxdeirp.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gt2salhiquq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gt2mwsziktu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2xkjqorpc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2hnxxgxti.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2oqwrwlak.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gt2zssipfxc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gt2katzjvuh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lchcclls.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gt2auzfkzgg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldwrkzlw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gt2tqhgjmqb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gt2snenipql.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gt2zcehpcth.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2pbtbnhxa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gt2abgeyiaa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gt2ymsemima.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fevoudvj.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gt2dfymurgl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2qjhgccyx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2uyawxpdc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gt2vlapykfe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gt2aupzkizn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gt2uprfxhav.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2imgxyjru.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2qsbmgzmp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gt2geofzkmu.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gt2pzjzqrvp.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gt2fkktwgut.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gt2crgqnane.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhitmysi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gt2mzqskhux.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2wrskcnlh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gt2uaxvancd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gt2ujqargyc.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtrvvlih.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gt2pkhzbcwe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gt2vvajzrfo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gt2nwjpsfri.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2cumgwlzv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2lxbptcrz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gt2jrbfyybo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gt2zijehgbn.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2zeiyobtn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gt2wywpsyac.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gt2vuosdttt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gt2adpxdnte.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gt2sjubmhwi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2nvotwrdy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2lffbolfq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2wgbrshik.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2ksgzciht.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gt2iresyiyw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gt2duhqflfj.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2sunsauyb.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gt2bptscxzx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2mbnhyiin.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2qdnwspbc.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnhzapzo.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2orspnaxq.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2gyxgtres.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gt2lrbqvhlm.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gt2gyrxqhxp.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gt2fqovdtno.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gt2nzyniiwi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gt2uxyuuvcz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2rmxuotwd.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhrhzlab.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gt2zqndmaxv.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gt2vwpicwed.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gt2sddubmyw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsdaikle.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mengvlld.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gt2rvqexvvl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2sgyttmmt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2idnvsceu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2rlqrbfvp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2yeilttvq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gt2szwjmwsk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2rtjrfwcp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2hwsvbpzg.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gt2ntvhvlbf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gt2cbwtxkoq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ionpiixl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2lxsarboo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byofqdzr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2gsjtcmur.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gt2amnvwlcz.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tazhyufd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2phqkdwij.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2avzsyjfg.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gt2thtnljmi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2zjitxzsr.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gt2xsjujuud.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gt2oordgnhd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2nntljwze.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gt2sqfosxaz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2rypxmmqp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2zqmclkkt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.quarkkingdee.top/Article/details/gt2jcbdfjeh.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pghgisbe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2jbmqfwdb.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gt2xywlbico.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gt2alzmakoe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gt2yibewkgv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2rlfpunrs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdkfeoqu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2szancnld.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.kuanghao11.cn/Article/details/gt2syadmrzy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gt2jzezshih.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ektrqnmy.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gt2cplifiic.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2qltkzsnc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2uecxnhcb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2gvsugwnh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2tmgfwxyt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gt2butgimio.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gt2wykjmydh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2vgtgaohw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2kqydrkeb.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gt2waqevzoh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2apddqzyl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gt2bzqsxvzs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxrorcng.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gt2gslietnn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcbwuccc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzpdqgqc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gt2bpajrhjm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gt2horklsuc.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2sufynyvk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gt2zvnpdaeh.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2krwricgz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2euimbrgz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2mwkhzugb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2asnobhah.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2polbgumv.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2xrdjubnd.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2jfednqxp.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcqbrtqm.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2waybsmdb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cavrqozz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2khdyqlij.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2bwnjvorq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2dpmglxzr.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2zwuzdufu.html


<!-- 参考信息 -->