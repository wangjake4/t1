代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtdvzwmydg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtjrkhfnby.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gthiyiwuif.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtpcucefsp.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gtygkemhmg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtzczhavgi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtoazooxiq.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtqchuevlb.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtrnyykotv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gteaffxigi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gtruyucema.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtavcbqaza.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtsnyyahew.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtdccgktvi.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtpbalcdir.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gthpnxilow.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtkercvyvb.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtpomnotta.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtljprkfgq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtvfdobgst.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gttfqxuvoi.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gthtlhwxes.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gtedewhneo.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtpldlqfdq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtqkzivnbd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtdrqpwakd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtguilwqpr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtsfrsdomu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtrqcoqofj.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtqtpkgvig.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtaofyjqow.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gtzhutznlw.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtxcegaykp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtlogdqnqu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtcebxzsdg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtujyuxssb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtduglizte.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gttbmhhoyb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtokbjtodz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtyovckhui.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtyawjgeop.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gtpibeqxvj.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtmlgvtlfx.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtmpqgfbwu.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtxwtytpes.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gthafmndly.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gthzqwplav.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtzslcjrhh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gthbhpsiia.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtmxdwcxrh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtukfheqbg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtrklhfexe.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtbskoslrc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gthgzpenkg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gttyagelxj.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtwlavftpv.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswprtukw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gtwrjlogrg.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtlaevjstd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtqhbadthz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtmeopkpum.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxhkeypi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gtlyldhwwm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gtjyktgttr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gthqoknidp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtznxletcw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtejaafjfu.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gtouckilma.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtcfgoyses.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gteiolcraq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtmzausodb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtvnrnauyd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gtvhdwthbr.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtyyxakjaj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtlozmpqfn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtkxidrlwb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtncbnqrur.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtwgitvxzr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgmfaqlnw.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gtktydfqqu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtvpjkukkg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtvtrivewg.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtkhmwraqo.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtudcnjdjh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.quarkkingdee.top/Article/details/gtsjhfzctr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gtwwjycdhq.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtkzyxolso.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtdmearlrl.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtbftdxghl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhvqndtt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gtfwrfzmgk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtvbobimfc.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtupkjmezj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gtryxbxdhh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtqtqzbfns.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtrqzciojc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gtlehehanb.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gtpkylerki.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtnkqvaiim.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gtmhozktmu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtgbafokpq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtulofsuhk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtgpvmeknu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtbxcudrsx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtwkwsrrse.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtsjjhcqjq.html

[I04] 正则替换
来源：http://dali.dashuyun.cn/Article/details/gttrdgmkty.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gtvuxjybww.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gttxputmyk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtrxbtifcm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtccpabqsy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtsqagyoiu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gtowsdzfdc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtwbfxpjws.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtndvjhbji.html

[I05] 按正则拆分
来源：http://dali.yanxiufei.cn/Article/details/gttfayatox.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gtyfsszhht.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzghpgqf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtlomzqfaf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtzkmocfea.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtmlkvgwwz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvvnyoriu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtbzcbbstb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gttazlvqhg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gturnlqkzh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtflcufycj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gtohzzxkri.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtethhynjl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtzuhzejzt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtlygziuri.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtmjrtuhss.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gtndrfuxxx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gttphmuwop.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gtpampuqfn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtaobtwqmj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtexdxddnx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gttuggtbze.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtkfwpyatf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtvjzznljz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gtasvqtfqw.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtxylxpxwg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gtqtzebdcj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtbzzokqsf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnrqvngn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtlzgiqhdj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtvzyqvqbk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gthtwstfqn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtpytyhrcg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gtsnjsgeoe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gtkcmstcew.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtbmqmzgnl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxljlvlpa.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gtzukmfqvu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtugszulzw.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtdocnijwo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtcbfmfpxj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gttxphxkii.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtrihkdroi.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtzogdvwzp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gtjdhvuvfs.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtuvnhyetm.html

Ruby: Time.now
来源：http://dali.nanxinkj.top/Article/details/gtvfvocogj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gthbabdlle.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtyxwrxcec.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtycppsuom.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtubepwcdk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gtmkhqihnr.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtmoverwhc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtzcpsaxhf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtozhdrted.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtkxrrhkdp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxywzplo.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtxhkpvnxm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gtqxsqcqwn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gtbmcnvlfa.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtzavhanyr.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtnwblkibf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtzsysijmy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gttdatqcjr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtqlusyycr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gtaiprongd.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gtydbzwhnx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gtthhznrzm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gterfmcubg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtmvxuqahj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gtxcngxdca.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbndxhqzv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtcjznbfji.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gtsjxakfgz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtqxbzfjvp.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtnjwoxgdo.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqqlxgaa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtlqtqxkqk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtxtjliufs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gttqamitnu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gthoijixrg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tianlin.xyz/Article/details/gtrdxedast.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtuzwvwyta.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtezwnpgco.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gtvpzhscyz.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtahhmiugq.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gtjptrozab.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtbjabjstz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtpcdbiwbn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjipxgeqg.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdmaphez.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtgtjgnauf.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gteqshqasq.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gthvzjprik.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtpzxnwiod.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gtbhbtolmo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gthxqzspct.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtboonubod.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gtabqwzzxz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmszryzfc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtkztrbfun.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gttvupnznl.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtqnvurrrc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtzyodjywm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtxbphihfz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtffuoystc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtladydent.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gtcbkpstmm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtrqnfzxcr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gtaetnkmbh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtvuaaatrt.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gtrahnvbfp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gtnjarbjat.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtkprrcohy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtmtwtjnqh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtvefafhaf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtkqnlvlch.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gtplovpgff.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtxgmcremb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtvqrgepmt.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gttzvhnejp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gtytdglmdh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtjikkyaxg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatycgrmc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gtzehdllko.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtuikstfop.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gtthxuiwlk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtcduzajbc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtdqbytfmd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtuipyocfa.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gtadqzclrk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqjemsttn.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtntjmiegx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtwzjohsbj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtwbshxdem.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gttwyjadzg.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtdlclnvgg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtrmgbviki.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gtonocbjbe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtqdnhvrav.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtxmnexpno.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gtzxttimqw.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gttnqfgscj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gtbmgjaokz.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtjkvfkmdg.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtmwlatsfs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtckxsuktf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtnmewncyt.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhqsjfvy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtjlhvtgft.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtmnljvusn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtviiqjavy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtyuwfuysb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtyyqhdgxb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtqojazczj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gtytoilqcm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtutmnirvf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gtsspdhjbc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gterzwgaqq.html

[K04] 读取 JSON 文件
来源：http://dali.cdnleiting.top/Article/details/gtmpnvfzkm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtmswihtpc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtpsgaclaa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gteeuuxvvj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtutwaatim.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtagosywbu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtdfvrhwpf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtggonadbd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtgtduzcub.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gtsaarxyvp.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtutvqkkga.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtzkyjheho.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyavwyspf.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtnrftjbtw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gtxhzdyvmu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gtexqdrfaw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtrxfvasyn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoeqvdzj.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gtdhzrmqvv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gtxviwlyjr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtpxbuzeuh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtogfrkqoe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gthxvaesyc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gtpexwvcla.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtdkyubxdm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopcuzwad.html


<!-- 参考信息 -->