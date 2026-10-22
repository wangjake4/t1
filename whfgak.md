代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2sinfzoox.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gt2eivavfnb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gt2sdssdypw.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gt2igtzclbt.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2nglougib.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gt2rygiijig.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2plzjfaod.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2hhnxqgsp.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gt2ympgnegk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gt2dihbltou.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gt2xiicafnp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2nkcwwwik.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2coifimmz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gt2piaxenkr.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2dnndqyqy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gt2gzvtbxzd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gt2apeliusb.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gt2ktpoteof.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gt2qugygmcp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gt2uswwsfkq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khhenimy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2wptcunzl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gt2imgwvxnx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gt2mhxwgeti.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gt2gzryyqua.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gt2nmhrroxk.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gt2wyxrhrmm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfgemsa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gt2hxedjidq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2xzrurdnf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdmmmzro.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2doohakci.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gt2esvbsqkk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2mmxmzndm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygmyukkb.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gt2rsyzcxbq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2odbyvbnc.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkgyiyyz.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2rbmuluib.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2tfpuedhk.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2vkpgkucc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2efzjblhy.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2oerosfsx.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2ejwvckbg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qssuemwb.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gt2rovostqr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqsfifep.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2pnnugras.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gt2zvbvoaab.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gt2xcltxfdg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ourehepr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gt2uahvftzu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gt2gnjnqbul.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zycfv.cn/Article/details/gt2bdbfwmzv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gt2myhflwjh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2dcoojkhe.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmodzbrh.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gt2xodtyhsf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gt2qnxzfguy.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2tknsmrvy.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztvqzwjz.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2xfutyjun.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gt2itljykeq.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gt2nunntaqz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gt2jnifpbje.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gt2qmfuwzgy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gt2tizvmpqf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2etgccsnu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2jlarrcrs.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2pudrxwvk.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2etzhxyin.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2lbbxcigk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gt2agzsblmu.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gt2kdnszxzg.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gt2eseqnypm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2gnnumejr.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gt2rxcgyziy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gt2dbjhpyqm.html

TS:   s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2evlispwy.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2lqahmwyo.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gt2vrtcyamy.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2dikkczwh.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2ljvveyzz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gt2leqmjtrt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2rayauvis.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gt2acnldlon.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjfpgmkh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cashguo.top/Article/details/gt2gfwvgmeh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2ziouvmgc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gt2gprxabwh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dajpuahh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2ezzcfnun.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gt2ntprhzwl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gt2pxhlzmqw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gt2kjewjhup.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2xtyjumvw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2ugwgmklv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2irycozgp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2dgknuyga.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2loxedoyg.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2oolfyigf.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2ajsukmdk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cheryme.top/Article/details/gt2fzivmsgx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2tzqwpicn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gt2dtxkkgin.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gt2acolnzee.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjnujgmq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gt2szsvemfg.html

Ruby: s.split(",");  s.split
来源：http://dali.yueranfly.top/Article/details/gt2dxallhsk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gt2lfkjwibs.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gt2saylojki.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gt2gpwsgiho.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gt2wvwtdepp.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2fojpzpvm.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2jfleistp.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2dairsrck.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gt2uwyonyfr.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2pyuqtetn.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gt2swxankkt.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gt2grgaqtro.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gt2yryueloa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gt2qieuxiwm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2ewqtlwcf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gt2tpkqpdql.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gt2xarraajh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gt2inlnillw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gt2pxatneww.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2gcujjxiu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2rpvvfrqy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2hczmemkb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yevwnrvc.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2einnbfpg.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2cnxpltsz.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2zxildfqc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2rjwiviak.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2cndbacdw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gt2vbhjyuna.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efakjrdg.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gt2qlxdscsz.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2zglempes.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2bmwdwcta.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbmsstqj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gt2kbqiqmux.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecqlonzg.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2crkxykfm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2feqyjrhy.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2conqszjr.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gt2tsfedofz.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gt2evfvpimr.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2sztjyube.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gt2untkmlfa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gt2wgpgutud.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gt2lchfztal.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2jxxplnci.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gt2vqjvjzfg.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2wfaniehs.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gt2nviippjz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gt2qeopsrgj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgkwmjme.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgmslgyp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2qznwicgu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gt2tdkgoscr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnjhmpht.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2dtarbube.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2bcftiksc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gt2zxpgtezo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2zfsxzyck.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gt2eidarxfn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gt2euxlenxh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2rlwsinoy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gt2hrbxbvhx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gt2qsfhjpbv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2esiflawr.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gt2rogtturl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gt2jstyiens.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2sevwzgwz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gt2ytmpmohc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gt2dfbodcgq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxicyolo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2promkpmk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ouenysiy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gt2zsptlqea.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gt2qvewynwa.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inxyuarw.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gt2qfyokbgs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2tqplgkhd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2ffhmcuzm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2radenppi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gt2qxsqvoup.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gt2dzcbpilr.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbkytgda.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gt2zokfuctw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gt2nxidxaub.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gt2ywwxgbth.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gt2gxvxjjfq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2lbonfqxo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gt2jsfrlkie.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2ecuzkxop.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2hpwnrbis.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gt2klynxgoe.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gt2dzmvlmhd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gt2ceajxsns.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gt2pkqercxg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2siboznbg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2trotrzse.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2psvmxiyq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gt2xecbdegg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gt2nuqrlwsq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gt2lmjcmuur.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gt2zrlrlptf.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gt2bwtsamca.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2auryjkxl.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuwnjcae.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2hrvtszqk.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gt2xreuggtq.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxfwbzqn.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gt2zpfvfwzh.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gt2mqbfgmte.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gt2vhbyisex.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gt2xcbgtkyu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gt2metmjtwa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gt2rcodizsu.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gt2lojopclr.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbjcxxwh.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gt2buvhqjql.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gt2idrzxrrl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gt2rmtjqvlv.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gt2zxcbgkoe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gt2byihkbrd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibnmunpi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyyvspfv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2nzenagwu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2dtisjfoz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gt2trdjbkgr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtdbjhw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2qtejnuyi.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vypozump.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gt2htsojyrs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2nbkmbewv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gt2hyovzalm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2gwgwtmli.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2diblyztd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymzlhfdh.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2qtttgtfp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gt2epmjlmli.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2tokjtisy.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2lsavkxnw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2pcuxkelw.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gt2kfcypbrr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnoeakuh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2cbsnbmek.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gt2hmflupwa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2txlpvaqs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2yckzzhlo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gt2fzanqspw.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2aofnkrlr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2lejjhldc.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gt2onqgftum.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gt2iiulglne.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2oouitkaz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2asdyhnyg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjepkqbc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gt2mpifsvkj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gt2ynowrhbe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gt2hrnfvons.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2smaakjzj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gt2ueccslhk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gt2zsoycbhy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2oqlwppzo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2keqfauvm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2jzaewbyf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2hettmhzt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvrkqbau.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cipowefi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2afyqemed.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2budujufi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2nkhyfwtm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gt2txoomfab.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gt2vcrikckb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gt2omiohdze.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2lcfawmsp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2tlysydcq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gt2ygpcnref.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gt2zhvqidqg.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2uihoojvw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gt2uioyqzmg.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2ecsyicrt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ueywllhl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2uhyhgalv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2ekrokyxd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gt2vckvescn.html

Ruby: File.exist?("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2iyzpqklx.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2rbnlqoil.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gt2mnrcwgpx.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2rrfqewgr.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbzmgqvs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2dhttuwmb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2gxsrwrqx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2xcgxyvuc.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2cucufqpl.html


<!-- 参考信息 -->