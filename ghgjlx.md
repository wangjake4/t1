代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtqopbjouf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtgbrrdlqm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtogskqtev.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtvfhsyaso.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtuvgysvum.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtkvqeblug.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtfkupqoeh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtzqgztryz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gterltqorf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtneluexwd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtdgteghob.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtgesjbhnx.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gtohsiodiy.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gtsoaiebnx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtsvlgaohp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtnnspuubc.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtuidqjuae.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtrwtdcklc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtswoziagw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtmufvxiuz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtxqyvwppc.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtwjggpcws.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtoimmfvag.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtzfkgxdyx.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtgsrlnsnq.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gthhcqzeae.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtofnbiimf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtdnqvkztf.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtppcbzmhi.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gtipvmpwiq.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtmulhqxxv.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gthzoeijoy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtfkdnszdv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkkhxuqjm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbawlopso.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtdbejockj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtrpnaknjb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gtzkbcwwhj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtjubnhywf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtssxtphre.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtapdzuytz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gttupuqkfx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtyyxgfxjq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtiboiqnmp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gtqioaqabl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gtwzkxxhkp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtbcljtpxg.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gthxdsysye.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gttzrmsygr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtkofkpoxt.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtdttiqutx.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtensyqvod.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtkfmdicot.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gtcffajxjl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gtgfeewror.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtbwsxjyxl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtlxymuhzn.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtgcrsuhrv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtohlwddhr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtfathwwih.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbyvugwl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtbbnamsok.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtifobyalx.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtfnibowuy.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnarrorj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtbouhmgpc.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtlhwnylme.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gtbzcfocby.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gtsrzamusc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtubkjwttg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlshkgddh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gtvmsfjayq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtuoyrvlqi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhongyouzk.top/Article/details/gtpsohmfkn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtzszvuqke.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtmnuhvhyz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhoulong.xyz/Article/details/gtgbeejvsn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtjluzomdt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtbfrsekux.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gteyjibrtw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtsltcohqu.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtedphehmj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gttsnnxmmg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtwyghihim.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtenfmpgin.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtolxgdesk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqkcspyna.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gtmwpkmzid.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtqxhtcxqc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtqsabgkhc.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtggsmoyrg.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtvbjabsau.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gtytmmscxm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gtbdaqcacj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtljgmgpdk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtxsjxpkks.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gtwcbprmvb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gthlbqvicw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gtocievwrp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtohcmiost.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtetlypgce.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gthsojeweo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtwbhyyjnm.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtmpocctpb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjofszxc.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gtdozaexif.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtywuikgvw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zycfv.cn/Article/details/gtgiwxbfjk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtbbgwhtid.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gtctmzsztk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtqpdrhtak.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gtpfisppux.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvdhlfsx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtrnihpley.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtrrdylhqn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtqhrurtsa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtcpcnruqs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gthwojqwrl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtrjtgbgin.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtdvfgxvhe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gtcaynvlzu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtldbhflho.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtutweumjt.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtjjpsvedx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrhqwwoa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtptvnhbvo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtuejbxktx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtaivdtbkw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gtasjmepnm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtgflhvnpp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtngwwoxib.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gtjxmgsezx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gtzlfjyhgv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtlelixzdi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtrpzbiryq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsungvuwz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtzjzgpatj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtuvwhlvre.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gtpwafngbo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gtftdxlcak.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtmvqpeymj.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtzjdvprug.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtursgtbqu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtyimqstmm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daria6918.cn/Article/details/gtudexlgge.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtsjpnqlpa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gtfvmouism.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gthjcqrwyu.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtquypcwhv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gtdukdlrit.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gtapzlcigq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gtzpsbhuwq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtddkptgto.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtvcxjqbtw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtthpzsvuk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtceblzzbg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gtfqdkwtgs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gtwcqtmlyx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtohhhqmpl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbvotmuxl.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtwxjxrtrt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvjckoria.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtulsdahvo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtgkallkro.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtujcrlisr.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtsoydmpzo.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtpqrlvsjv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtivnnounv.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gtpiihfpdt.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtaliwrjmv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtvabquotd.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtrazpyisy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtacgssaed.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtecndxpdr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtyepzavir.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gtaehtyxoi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtiywrbjgb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtfxlkagmt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtfwrkmvmw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffmlqokw.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gttuekpulo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvniykkw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhiwuduotai.top/Article/details/gtocssvksp.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gthqiiplqh.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtiwrqjtlj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtyzxsnpmo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtkezqhzoa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtmzwfjkjp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gtapfzarsa.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtlmpjcwyc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtrdapqfhj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtlbqguzdk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtjynrdbkv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtmaejgcdc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gtzhctxsbf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gthaewwkeb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtbetsibom.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtdvakawag.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtppiapuxr.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gtnkokeddd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gtenidinxk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtoxlbjfaa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtdztxpjhe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtidndsxdr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtjyqqvfnx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtjxozlfkm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtmufnwcnp.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtzjctyyyh.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gtcvtlqvrs.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gtywmmmhkr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gtfdqhqpfe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtagjqvces.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gtquniruuj.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gtrbcwfxwy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gtaubmqeop.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gtcuffrola.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gtgawuuolr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtnizewknl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtznydubbe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtakyllgng.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtchdywltk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtjvckaykm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gtdilzdsip.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtjooiaixo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtseqjpjnw.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gtaktrskpc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtficzramb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtotddbdwr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gtpfsnvcly.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gtsaafeibn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gtkbcbtozl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtzqoixsgg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtzwkhoulr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gtwgkzocbw.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtogcpcyjp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtcriiykyj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gthbegfxqf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtvhdyfufh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtelxmgsga.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtmocilrub.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtmyvuulqd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gtpcgnujhm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gtwlxfmtdc.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtgtwrxgcx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtcfkvcjlo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtyiuyttly.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gtkiynurng.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtvaeeouzb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gtryjchvia.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gtmesuseqt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gthkyedtub.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gtdtnzjgkm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthckvovnh.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gtcenxwbcr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtggwvdjgt.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtpaabkbhr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtycwyoroq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtdsgduxmq.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gttmmltmty.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevkbzctr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtehqxgiyv.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtqhbfnkuz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtjwyldqvv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtbxztkfkh.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtibyfczao.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtdoxdlcym.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtwlyolril.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtqlardqna.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtllbeovcv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtovtrjcaw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtmrtsennq.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtrbhxttzu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gtpoolkurt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gttpaoayte.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtqdcwdtov.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtfqaxpzsz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtopakqdgj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtlokvvcmx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtawzghyit.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gtmhjgxdgj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgfpkuiqz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtofswaqwj.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrracqbu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtcfkeagbx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtdhplemvl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gttqfrxkmp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtqmthqgsw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtwtswgtug.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtghdenrfg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtcffczreu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtysqbxihh.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtdhinjppz.html

Py:   copy.deepcopy(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtrasbrafp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gtlpvwuuii.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtoueldeoy.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtvjzskfci.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtweeupqmk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gteputdxhn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtbcmzlwmv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gtodjulqva.html


<!-- 参考信息 -->