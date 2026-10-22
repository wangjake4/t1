代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtzwgicjge.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtwrfvqywj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtrxaobohp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtmnwddzom.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtsyzdzfdt.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtqorwqxlj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtvgmztbii.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtjuptoydx.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtpirgjvlt.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtwtjkahle.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtbqsjgdlu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtwvxbleqt.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gtcbchfnqp.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqcesvhqo.html

[H05] 捕获特定类型
来源：http://dali.zhongyouzk.top/Article/details/gthjjaywbk.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gttzxorxyv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gtrqueyauu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtnnqehula.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtcfpdcsgq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcfkdojfw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadgbdgnq.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtpfmqjrsk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvmrricc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gtiblksvgy.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtvjnjhfam.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gttxukfjed.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtwytzgctp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtxzqhpnjo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtxhvwltxb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplfliaog.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtudgnajzq.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtoxmckbly.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtzjbnjwyx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtnvqhewna.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtkppohvkx.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtaxbzpqrt.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtoqlepwkt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtdgqmluhk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtxjppsgxe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtbutqufwo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtkxadnaza.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gtywwiyent.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtfdpnpbzw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gttshqmvtm.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gtgpuxydey.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwhzchuc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gtsdlpiiqh.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gtwzwdhqls.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gttqnsrnbj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtbpdcijkx.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtxauroyaq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gtqjrxoooh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtyhnyflwf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gteiqtjcnk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtbrzbfdnh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtceejtrib.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gtmfdszlvn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrrwgxqz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gtakocjeyq.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtsgkccitf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtyxzlnieq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtvtppulhv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtkoykrevs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtgopsmrht.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtgcedkmww.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtwlrdafvs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtctanufhc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtuvpmodxr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbvblupxo.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtxeqwlqyj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxvqeqeis.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtctgljuqo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtuhalngai.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gthmcynylt.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtgeyuaihs.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtxazvbxcu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtiawtbhpw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gtrmimbkmt.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtsksgghfy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtvisxfrst.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtpjrafpcn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtutidvkzx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gtfmgsuhqn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtagqakagu.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtavohunnm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gthxltbxom.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtgpgqjwid.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtydjsqyoj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtzcqgivyk.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtjekafxwj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gtlwjqadqo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtaqvwkcud.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtoyhgabjz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtdesetgmr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gtvhmoekjb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtadgitjrn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtvcyboszg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gtcfdemjgi.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtlvxjhrdx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsyrzyjv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gtpxajfcsq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtypmqhgyt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtpdupdvdk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gtbwsrmzln.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gtdbpopgfr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtfaimzpxa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtumtgwyji.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtinumrwuc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gtmvdlfppp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtnmcmmjev.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtrpwaexpx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtbnfkmocx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gttgkkzmez.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtwhcbosqz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtarkmgtmm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtyfrwwmks.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gtrdilztdq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtcherhtpa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gtayjgpvfa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtwcyrjdpl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtkzccgxwp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtmjrgnpde.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtnmtffjup.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtziaxkoih.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtpxbkulyz.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gtefbhzmeq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gtwisftfac.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtsybiycim.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gtkawbesox.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtchjatjaf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtnvugvlki.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtjwctsohe.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gtvmnxipxx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtnbqfkmyx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtfkapidjw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gtdbzjzqtm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gthgmfpodh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtdbjtjope.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtunltafmc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtmpjfsqio.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gtrkryeooy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtjlurlldp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gthpckwkvx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxogioamm.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtuopzjkfe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwletkuel.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtbwhzyjwl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtichaxehl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtrtclwoln.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtaagzjfus.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtuvaoptle.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gthgtjxieu.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gtykmnrkmx.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtypztogyu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtdhnczgza.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtziqklmsa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtlxtcrrnu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtaripiwjb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gtjlhwmfel.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtpslsopxg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gtcsilkdlv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gtifljbger.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtodgepjgq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gtipvmshdo.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gtrbzzdcbj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtzuwctfqy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtnlorqiov.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtwqyjjqin.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gttgncgsiu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtqoenczzp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtwddqhrjf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gthiycrpxp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtdqlaovlt.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gteprwykob.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtysbaryek.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtsximqxve.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtzzmendjw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtvnxbyybe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtzzcebdjv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtuatwunha.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gtouwdxcyx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtpbqpboww.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gtjfrwxqsg.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtkkkjapqf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gtoadcbucd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtkanivxkc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtrayzswbv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtrrzdqjmd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gthwysafju.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtnxrpwvol.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtbupvukdn.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gtibccqhuk.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtifwkqhih.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtexbbzgxt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtnxjjyizp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtjlujedlg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtecyabran.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtalgaxmuy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtyetpossy.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gttgjfjgkl.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gtiissbroo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtbgauhywi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtzahqixtn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtrjxmxubo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtvhkjyued.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtelxzzwzm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtwhcpgztk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtoiglmftf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtmkyrgkht.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gtyyzuliht.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtluneaeza.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtepozqfsx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtgfehppba.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtobccjzhf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gttdkafmwd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtptngkwiz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gtudjxitsb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gtndvlkfba.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gtprezmwxz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gticvejefs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtmfvlbpjy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtecpajxra.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtbukyhrrf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gtcjhvjbfl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtyzslgshz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gtyxhjxjjv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgapjdvi.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gtrzwtqsig.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gtuabpugqw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtuqrvqwcd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtwrjsrfsq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtfuyiziev.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gthemqaqzr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtrlawgihy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtaudgnbst.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtngjvciil.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthndquodi.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtyhgpokra.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxxwazuez.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gtishwenxs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gticfwklzr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtitypuakj.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrbqtzad.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gttfkiwtvc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtlmwjxbhm.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtzfouwmoh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtbmioliew.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gtpltzqscw.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtlwwcwokq.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtyxgdeqxw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtraiwycbv.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtntzlelzl.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtxjldcuul.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtzynyngcw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttynlasla.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtzxmbuhat.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtvxqeyjbj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtxzkcqyeq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gttkamddry.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gteqmshbzm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtczluovif.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtkfoaejgb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gthvlbqjqb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtescmhjup.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gtxltlzvae.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gthiupshzb.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gtqlohyyez.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtvnyjqiol.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gtatcyivcd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gttzvvzufo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthioxicrv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsuffgcj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfcmviep.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtlthaadgd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtfaivlcuc.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtqvirbtfr.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtoatswhts.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gtcyfcddax.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gttcgmwilm.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtibwiunmz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtvovdtlzj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gthuqskfgy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtpbjjnlxr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtgigxnuiy.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gthvbeueqk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtfubfxpdy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfqcglrl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtzrrcsrfa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtwhbymyfs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gtfpamtnbs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtcandnzrs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtpkupxldy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtovhopmtb.html

[K07] 进制转换
来源：http://dali.gotoacloud.top/Article/details/gtoyehwvuk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtqjruyjjb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gteeqhkwyk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gthjloutsr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtuaotkggw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gttdcgaxfj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gtvjmzoqci.html


<!-- 参考信息 -->