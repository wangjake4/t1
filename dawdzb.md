代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtsfyqbxzz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtscusctcd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gtyzxmcdin.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gtzxcfzsyn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtgoylelhe.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtnuccngma.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtctkfaeut.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthewkwoen.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtmwjegcew.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfhvdddr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gttewfevns.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtjmyvgsmj.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gtujfsuzet.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtignlpwsn.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtfllofhul.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtthenqiyr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gtpklcrwhp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtwmgxcwmz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwsxwouby.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtewfyywea.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtwvywsdqa.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtmzczfnoq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gtabsskwbx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gtkenkesxm.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtyzurmlgd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtsyorfdir.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtanavkejf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtmzjxaaql.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gtkmpjlvci.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gtdjbblkfc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcbgmmov.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtdfbnieos.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtaklivfgw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtmkqilwun.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gtjuaethym.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtsryycqeh.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtroyoowom.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtsfstfhtm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtauldspvm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtkxrixucj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhvdfwpj.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtyscrpctl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtdwubaesf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtrookoaei.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtsnbwvlez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtgubdeuwu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtybkobfdm.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtaqytajpz.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtpxqthjdj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtgypotnpx.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtqccummwe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtcrhyiwbk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gtqjpnccjy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtqgplhgbf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtmycfthep.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gttfzmcfqn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtqmtivbpt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gtdpsxsvdt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gtgclrycrz.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gtohbcwxrs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtrgglhjlo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtvwwkxeup.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtgfbgdwmz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtxzlsidec.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcaklmsyk.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gtwgrxqwtj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtaofgtbxs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gtcvalfdlq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gthwnxmzli.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtolvgguao.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzcdykcrf.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdcunlnw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtkwkidwsj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtlzpueblx.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtrlzttntq.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gthcjejsdk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtxqnhhqzq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtikpyefsq.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtotdlmrir.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtzjqcnkvf.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gtrykioktj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtfikabazw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtzcwdyqri.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucqvmtcs.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gtkcjdnwfn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gtbeugrcax.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtrbphowua.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gthhlbfxtf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtmxarmzdf.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gteaiszhtg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbydqddfq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtcubujhss.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtlfbkqfxi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gtyxoqhwma.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gtgdnkicra.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtvhovuadh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gtbsorjjib.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gtxcqvhqqm.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtrymumdja.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gtsgradvli.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtexhnymoy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gtlfmgwjtd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtevgemlcz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtwqztqenr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtldrmzdia.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtenqpdgkt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtkfnadpew.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gtbbopbxkw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gtcktgmduh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtpzrdauqo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtxzxrdnta.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtwbwlievm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtfnkzetns.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gtdjsjqias.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtmnrbemgc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtsomeswke.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gtcwwknrrp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtfkkszeqk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtfmxkwlmk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtklablssi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtugmqhmko.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtmpwdholp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtdcbfzsym.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtozceoqse.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtsgbfziwl.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gtixwdvqud.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gteikeqrro.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtlkhycbdx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gtosubbbyf.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtmivturon.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gtreldmdam.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gtynijjdjx.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtotlealib.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtqstynzal.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtdkdanxtz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gtbztllksu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtdepyqgbp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtxzomhjlg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtgfizmvvw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtzxqeayhk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefxoxlbm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gtftgdaplf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtgpqicqwd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmobzoovq.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gtaoxbzdcq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzevlzylq.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtfrxqbnwc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtyqowakic.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtobllvmsw.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtzhqtfyez.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gttrftfyst.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gtpvtrtoks.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtkzqswcne.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtqvasbpwp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtreenhtby.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtqrburxew.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtkvwdjbqk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtixodyksk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtczfcixcq.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gteusdvgaf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtjfxzhald.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gttrkvkpoi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtlutviwss.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtwxbomoft.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gtypjyveox.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtrxyjopyj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gtltcdvjjm.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxbpqwwu.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtawtgfsgl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclvulgff.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtnrnmwzqp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtnzryhbeu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtcqsysvql.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtcrwsnljy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gtvgavfcqn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gteeilyusl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtiwcohchy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gtzmqepvqn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gtpoegioat.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gtafmhaufr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtsjzpbsup.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtmbmzabqg.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtyrynbtzz.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtdsxhhyht.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gttycfgtzs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtkbyvfxzw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtckkuuggo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zycfv.cn/Article/details/gtijzvcqpy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtpjhrnmnh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtanidmpzj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtavvnpvrx.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtnvnsrdgx.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gtpdsisqfj.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtfdwiltdd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtweqnbiiv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gtmtmngiry.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtsscvdwmt.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gttjilxsra.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtuhltsqyc.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtqocwpxrd.html

[J07] 比较两个日期
来源：http://dali.xuanzx.com/Article/details/gtnveaiedr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtmhphvaqh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gthybyzyya.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtxqlehykk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtcsjdyzcp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtfxjaopzz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtylqrwzyi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gthglcmkwn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtrnaacmbu.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gteknmzxij.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtqbausgzr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gtdjhvswrf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtqzddvwjf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gtrsojzzhs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gtaktqtext.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gtnjqmeptp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gtauoattrh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtgrwomhhq.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gtaehpdzyd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtuwrytahq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gtisfipmsx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtsgvsmbop.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtryizstmx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gtiziaqzho.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gtflxevlgn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtswxuabcw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gttsgfgivx.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtqunuxjny.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gtxqznknyf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gtzsgryytx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtjmgdxxsu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtqlinarrh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslyvuuzd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtahljuyfo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gtcdygvdib.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gtyspmpdqf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmrurvncn.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gtpcejzboz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgybbavii.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gttnwpwazf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gttltsiwks.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtoabetbmo.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtfdyucnrl.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtwczyrrqg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtwrqmkuwk.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtonbjqexk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtxwufiret.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtsaguabnx.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtfmogdslw.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtuhwsvxan.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gtmzufntbl.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtoyietqjf.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtikstotfn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtkusluwfr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtlrlxypiz.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtxkxhsqhn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gtuuzkpacx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gttptmskzu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnwnqsjw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjseapjcr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtalefhhbr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtuljqdxsv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtubguycnn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gtshfslcha.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtxtipoijx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtnpeeglbv.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtvtcktzwk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtnghzxfvl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtmpdedvuh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtrfdgnxwr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtfacuszwt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtotvpvlmw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtxwnaquwi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gtosqjruvs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtzlaokzqc.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtmseygjnz.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtoifctnse.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gttrssskea.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtwbhiyoid.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtwnqsdmaz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtqzzzwvog.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtpfkhnzqd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtqzezugzx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gthogwipsp.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtjqizadcr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtorsktlsg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtdiejubkk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtuisvtdra.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtsgnjwbce.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gtmtapobxi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gthkutrqkw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaasaxzge.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtcauizhif.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtqxnlqlwf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtjunkouhe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gtkiyvdmmp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtdavnugee.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtxykokdsy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtfybockuq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenlongwang.top/Article/details/gtqwewslcj.html


<!-- 参考信息 -->