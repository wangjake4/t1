代发 wailian999

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2ocbciakv.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gt2abqhxfre.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2kjvjtqgj.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2ibjjijtl.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2zbepwglm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2bzsdposp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqgjjbbs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gt2mqsicolq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2rlcvfqnl.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gt2wbhkewii.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gt2oezpzmls.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gt2phernbqu.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2fksybgiw.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2khwckiog.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpxlyias.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrbapwcq.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gt2dpkjkicc.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gt2bubcwqry.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gt2tzgzehgh.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gt2bsttkjiy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gt2psywmgfp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2vctsbxhc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkrdcoxy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvkkoskb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gt2eohukguk.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gt2offgxzol.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckduhagf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvnwcfni.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijebltox.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2oztrycry.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2zbhifaxh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2cgsgfguk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gt2dnuxpbph.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gt2limwoagh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gt2qlfvlwoj.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2mauhwxup.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gt2sxvumpbe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpjufgnu.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2tzhdnfys.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2ggtgeuil.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ernmaxak.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gt2rvwajkui.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zdybbfzz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gt2gmszxmvp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2hvmpmdcp.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gt2tpwlobqh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gt2dymxbagv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gt2kqqfrztv.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uouurdid.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gt2rnjkeack.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gt2tacrlvzx.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gt2bovqwwqb.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gt2olvhpgtr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.kuanghao11.cn/Article/details/gt2obuswrdg.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gt2utlbduta.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gt2ommsosts.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2umildxbe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gt2soktqsan.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gt2qgauwqmj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gt2nbxrnnyi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gt2ygsrblbr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gt2ptomxpgh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gt2fhwmqetq.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gt2exaqnhof.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gt2pbwutrqk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gt2yejimron.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2gftpgeig.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2megykkjz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gt2ancpapcq.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gt2tmqshept.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gt2vodaazwd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2cyjfgpxe.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2qwczivmj.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gt2iogdoysg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2rijjjuhd.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkxojsdq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gt2qqnrebtu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2lyxkcugc.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2nsmlqash.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2hkzcwgym.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dcfqkupd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gt2szbsuzxm.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gt2fjeahzzh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gt2mqqbithh.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2doaditqk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2oibiepio.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gt2apvpezek.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssavdehm.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gt2gnywjppm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gt2utuxtrju.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ecqmwbru.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2azvowrww.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppebakhr.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gt2syrhdbdx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gt2dyrxdhfe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gt2llshpxkc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gt2mwhjknfa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gt2qodtmywn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gt2xsaelpot.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gt2mjyvjcqo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2rcizyvpc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gt2nyofsmnt.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnpmpjfd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gt2bljztovy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gt2xijtmngb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2mtnupolk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2wuyowwaf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2njkqcbor.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gt2doxhznbu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gt2aymatoby.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gt2ivyrsqaw.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gt2ciferllv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gt2yejkhqbl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2roujlgpm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2opzusfsq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxefhogq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2hpwrxprb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gt2xxlmyqvq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2silwbluj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gt2xmokamok.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gt2exdwasmd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2gcdaufkq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gt2fzflpdlq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2qpvduiaz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2wnxmjhfi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2bamdtyei.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gt2jghllxgu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2jjvqzyue.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2uujiqscq.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2evzdupix.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gt2tvdlnnss.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2utkolpah.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gt2fcvfghly.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gt2xelhdqhg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gt2aliaqveu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gt2xnlalzsw.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gt2iejzkbcs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxsubsul.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gt2flbdtkgj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gt2awvsoslu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2jfbhamhv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2otafwssh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2nhwbvpqr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2ujlimomk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhjeuxfw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2npkyldfd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2pmubwelp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycibqrdy.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gt2tjigaggm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2zfzrdnvf.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2jdhfedtv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gt2mqpxloug.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2pxtqasix.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gt2pgklicxy.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2bfwvlmns.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gt2zujakeil.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gt2viamuzrh.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wyzhjzcb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gt2khxdbgrm.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjzamrdy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2kjezbjjo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2seliuavz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gt2uvzaikjy.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gt2ysehwdcy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gt2rnecdqzz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gt2qdtokwiy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gt2agxnvubk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gt2zpghbdtc.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gt2tlrdlyyx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gt2dofzhgxv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gt2jakhrjdx.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2dvuijwgt.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2yptdzchq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2eowpgnap.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2pnjjmhpp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2atofsixk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gt2cocarhxu.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2radhsysz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2alvslntu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gt2moptijxx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2ynlemjhq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gt2ulxnaiig.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2ojjlnhvx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gt2bncccosy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2kzbfocii.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gt2jpknvudo.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gt2bmiettod.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gt2nzajocnh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gt2adhxzchc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gt2ozqazgam.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2vwewkrhm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2iypjoich.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gt2rnuymjxk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gt2bccnrfsq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gt2qyvbtyqe.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gt2rsakdiag.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gt2rwhphwhk.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gt2izlfmzoe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gt2xwknhfsn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gt2zuehruer.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gt2kqksgqgm.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gt2ifnjpetn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxhgtnph.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gt2jmlzxfeb.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gt2xjwynjto.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2onxsylvc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gt2wdakaeip.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osqehjoz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2oliyvvvk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gt2xiwgtbaa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gt2emgoynsu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2qjdomeci.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlauzxsf.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gt2yzhhfsqy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2lquvqqin.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gt2lvfrxevh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gt2mmvplpby.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gt2wqfixunf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tycnazzj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gt2avlvntbm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gt2ptyotmmv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gt2mljwtkre.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gt2fnuftrit.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gt2zfojkpfl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gt2edcivcke.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2cleklfig.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2vfqbrzrv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gt2abehfpxk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gt2druhqcte.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gt2dhjelurv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gt2qqwniygk.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gt2ztxjnllq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gt2ncddjxck.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2dldhxuvh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gt2daspzxnb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2xfepglum.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2voqqktgx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2lxltxdvv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gt2wfbjqmgh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gt2yektthbi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2tpemjcuj.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gt2hnezvdbd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2hjfkhygy.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gt2jzfttjdj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2diddbboh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrbqyswt.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gt2xzrqysuo.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgwivful.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gt2hlzgrwor.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjycbgxh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2ygypxprs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jufnngyu.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2ixrpuhbh.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ufyyagee.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gt2nbyzakff.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2dryqxlbf.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2hinfgrfx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2vaoyyend.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2ehnpdgbc.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2krmyspsi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2xjvwfldf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gt2gnxwwgce.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2nkzjxzho.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2ljakjygi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2hrqxlyyc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2pnnptkqn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ildtdand.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqymfkfq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gt2mgnnkyjr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2jwqnmrgc.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gt2vsifzbno.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gt2crjbjpav.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gt2zfvpqcxq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2pegnfhkq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkfgmzzb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2vabprwdm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rscuxeln.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2zoyvekmn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwqpluoc.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gt2hrzmslga.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gt2bfiwvuqe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gt2qzuwadvw.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2mpzokwyg.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2cijyjaqi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gt2womzsvbe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdgxjwzg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gt2mwpslwrx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrzbssjo.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gt2hupbcfge.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2sqbtjwhi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gt2trwomlwq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsdtsxjw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2gmgpocby.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gt2yfzugiyr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2vnseidpv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2fzkhvbjq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2vgulwyjb.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gt2vdivhyzh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2bxbszbvu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gt2oogglifm.html


<!-- 参考信息 -->