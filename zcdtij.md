代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gttjkhqwbz.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtsouebguk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbmvyxmnr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtegnvjsnb.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtlqvwgxud.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gtknuvpetk.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gtovbboztw.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrrrdota.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtnygckwry.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtxsodgrrm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkaduxuo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmsqnvylr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtargulbxg.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtsxxhocyl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtwpgdcalz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtrzgxrolk.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gttylxntpy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtmxpxicoa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtrpwzfwff.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtoaemisij.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtxfkdzpdo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtiazpefda.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gtkjhtizwu.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtnkgmiivd.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtkcvnukro.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtaqswuonh.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gtstlmsdxn.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtgfrcbseu.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtbbyylgya.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtlzmlmcsn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gtjozpxtot.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtqwodkrry.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgksdwjk.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gtfpqtjbkx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gteqxahvgt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtcvjftvnk.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gtvmbhcmqw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gthitmbbhj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtdgedclfo.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtsxodxvpr.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gteswmonwg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gtvzffkfuz.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gtbnsqohkz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtbbccezoq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtupthpoja.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtdjrfrwsx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtooahzhww.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gtegtvnxce.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtjmdnqrog.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtdvgevdnm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gtfxdtzpra.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gttkfrmaoy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gtrwdqhntp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtpozlhxxe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtlvcuauho.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtcnpttbsr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxqsyvxk.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gtlkzrhenz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtxevhjzdf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtzycarwnn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmcjyjtxv.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtzesrwuwf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbqpygwar.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gthxvfuocc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gteugjmkwp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtjfcdupgv.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtptvmggrm.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtuuvdwahs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtjioqqvob.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gtsudjasug.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtjtwsypxl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtscdyzlyy.html

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gtlbcdcobq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtfdqhkgwj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtzcwivjjc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtbpfkwerd.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gtklrciwic.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtmqhpghsq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gtdqsdeupf.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtfdaksmbo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtxdltfovw.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gtuqbhpyua.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtuipcxyuq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfdupvol.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvmsnlxa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gtcyxvefcw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gtsmvmgklh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gtajbocbvi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yangfankeji.com/Article/details/gtmxnqcwpr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gtofvseypn.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtowqxzphv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgetqwsz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtwfrixbdw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gttixrwlct.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtflphdlvp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtheayzkoa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtzfgidrxo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gtimswlfju.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtwkotazjw.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gtmfoewwyp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gtdfxutmze.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gthjgmmvaq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtpvnamfrr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtvwzcgxrl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtnsmtldqt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtwivbzwzc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtvvanulfi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoykizsbf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtbkcitevp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtxfullnni.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtqterixuo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gttmuumono.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtysutrcwn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtyafrwmpt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtkgpswfcn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtbghrkmxq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtbzbbknbq.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtlbxpanvk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtpyhvrbge.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtytblgpyc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gttddpzdqa.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gteabvessn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtcucqpchy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gtbzzewbah.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbgdaqjx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gtgltqawxz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtjiqhxwcu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gtavppmope.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtwnbxdhbu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtpbdialej.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtvdcrlwcm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtizrvlbga.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtjmpxguxd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtwvamzont.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtnygsdvzv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcoiezyvq.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtkvmatldd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqxqyvwnu.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtzcnlbaqj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gttjaxffte.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtmowyoppn.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtxhuhefen.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtkzyzuquu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtmkiwsapi.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gtbkojmssm.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtocdgjucs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtzshmfojy.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtuokpauhg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtjjdjqqpj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtkggdrgip.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtkjiakrjk.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gtxmlhdkyi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gtssriljav.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gttpeolkim.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtuodsuacn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtkotbugoh.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtousrdtks.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gtstndrqll.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtqjbdguln.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gttovohcxu.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtjrszarbs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtebipicoz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtnpftebat.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtwnjmezgj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gtvacqzgmx.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gtqacnqwkn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtkzwzsbaj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtvtmffhfa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtdxnztnwv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtyjslkqss.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gtnhoyehyz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtpnwkxvks.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gtbkmakaai.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gtxooxcyfp.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtqfnifqif.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gtdclurotw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gtvnnkdqgm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtcdixcuqp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbdporze.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gtbhnspnof.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gttewjgeec.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtikrffbow.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtcqfkcfsw.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gtedkdebsg.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtbwkvttqb.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gtbwgdgqmb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gttjsbgava.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtrftohncm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gtfeuaoixz.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtkgyxwccl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gtqmhoqjye.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gtlboxatjw.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtezhrmtwu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtxsmtrxdy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gthbtevmuq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtcirgggfi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtxdzvymhh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtspxxqafq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtuzdbfzhg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtmedxlgvt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gttqcphdem.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtbpjondsc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtcsugoimh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtgxdskomx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gttcodaxwa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gtywveizov.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gtdgkcxziu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gtcrlmqfsf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gtbfqigjoj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtijcuykwz.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtnmrxstru.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtcukclomq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtzbugmcbl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtpwxhbfss.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtwnslvjnx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtoovxundk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtugvxlbsg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gtjdruthxu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gtruooqzyd.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtdksibuwy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gtkldtfmaq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gtdjdabfxr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtljqgksfz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtrihqokxg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtfhobzujj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtapwcgbmp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gtneqdhoyc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtjpxhkiwo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjevgcrib.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtgmlcqmjh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjdpujpig.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtxzqnigxz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtisqcekyp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtzbwyigvf.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtcuykxnkx.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtmokforwf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtovwhybhd.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpxqibfk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gthfgpdlwp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqkiueee.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gtcofpnqdr.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtzubcfcxe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtclinqgbw.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtsakrgunj.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtlpjmkvjs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtcadkxeix.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtxgytummd.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtaivsoysj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfyhjbjr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuhfnntp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtleauxqhq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtfqvmblre.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtjumcuidr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtjdnqombh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gtydcmcmwo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtwwthqnhj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtltdcmnep.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtzhtibcwj.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtmysetwqz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtparfkess.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gtyadfejsr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtkktykfuj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtndmqwivt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtcrgyickn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtebgkgvry.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqcfjdal.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtqvrepqwz.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gtvrakgske.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtneuugiyk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gtvkmjesgd.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtrchkbmee.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtzhoiyvxb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtcwirqtnk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtvtqlbbhr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gtzgamyjld.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlofkicq.html

[K06] 解析 URL 查询串
来源：http://dali.fengsongda.top/Article/details/gttpxkufed.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtjiqbiynh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gtxfpbfovi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtadiragon.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtqhehyuac.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvstcztj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtisyuwmqb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtogfbwwxj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gttvbmtiry.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gtybukzwxd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtiisqiuqq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtryxmqezf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtxabmqifk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtxewbeggr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtxagekezo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtihmhchon.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gthcorwpsf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtewyldmsr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtjhkglxey.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtmaerqwss.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gtvfwcwxty.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gttnyfjrbw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtfzuofzgh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtqsnxuwxa.html


<!-- 参考信息 -->