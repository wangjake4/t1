代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtyilwqhey.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtviqpdknz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoayljmv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtdvodbcnn.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gtkrabqtah.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtmjfkkzba.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtmbmyovnf.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtmmeemrxo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gtouxqtumo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtvfmknguf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmzqfqrbs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gtkgngdvsa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtkqysnquc.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtqgezgnag.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtuyenyjlh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtrbckrwax.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gtymtyvgpj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtkmstfxyq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtqpjaszjw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtohccocde.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gtlwnvhlkx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gtnlchmqef.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtvkvawqjk.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtrjsxfpeg.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtvtuongmz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtzajzlvbk.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gtusxuemap.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtbiyhrcap.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtaxqzhfjm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gthfxxspwd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gtrhyzwobp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdnjvxdf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtljzjgpdv.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtzvqffpti.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gtogrigfgo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gtiyxrkddh.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmtrbakk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gtqfzadabv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gtnfwsaeib.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gtpimncwhq.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gtvdadcblr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gtnpjikypl.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtvbtrfysf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtvxduymrg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gtfkknrpjy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtapeqbfoi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gtscjmxgbd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gtokcivbbx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtqnnpwivc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtwlekmjsf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gtqkmnvdkw.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtidfjljpu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtleuzypiz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtvzxijflz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtyyovkrhf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtccpvlnxi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtirqwskjr.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gtrujjrbmb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gtinarrqbd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtnptlxidv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnhooclbk.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gttoiqqimq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdbsnspsd.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtaqhyhber.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtpdbplkzr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtejplntjr.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtsmwjdayv.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtpaiusnar.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gtmteqacck.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtgggvmsxu.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtxngnwave.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmxaqlul.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtlfbgbkxu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtzjqyesja.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtxzvlipee.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtfgssslve.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gtzacjfnxv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtzgfyacsx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtouyuqhkr.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gthuwndljc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.andypj.xyz/Article/details/gtvrgvsnuh.html

[I03] 提取捕获分组
来源：http://dali.cheryme.top/Article/details/gtwjgfmrvm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gtafcelsrh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gthsybcwkm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gtnqgplums.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gtbawpvyvl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gtcpfgnfpu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtnjpcfval.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtpynxwfea.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghmqwqie.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtqfhqelzd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtfmjfruqq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtuyxfnrpd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtlbznrunn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtpxsoomye.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtczotkpzr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtwqyshbei.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtsazsxrme.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtvofcxhtq.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gtzfaftnxh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gtcobhnyuw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gttzoptvlf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gthrjfjvza.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtitigzxmx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gtezjraomf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtihujdkpb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtjnfdndsa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gttoudhpkr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtazjjgglc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gttabkuidq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gtqpfxtuci.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gthdiznnsh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gthavseazy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtgyjsmklf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtmkyupgrx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqapvxov.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtvezslgfn.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtsbizbzjv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gtkhuoekiw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtgtljuxew.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtxuubecgo.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gtmikwgcpu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gtbqlkoolp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gtozleyyre.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gtaqxevwmj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gtycsvtsee.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtnqoqtxff.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtdaizjauh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtahscbmbh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtwpellrfz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtitdshuzu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtslduhdvc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtndwjymko.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gtjgibgwiw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtfawofuvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyfmoxfdw.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gtqbcpcovq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdldlghqs.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gtlcvibnez.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtbswabvor.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtcpbitjle.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gttvwrgjll.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtmpdjicco.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckrwztpn.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtbkuadwqo.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtjgochjtc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gtqbjmdegm.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtasjvodsc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtmeamwdxj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtjgdtipse.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gtlupbeiwp.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtinnilsuh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gtsfffggkc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gtvtroxdfj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtddsflyhh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtxjphzqez.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtoffcxyeb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtmfhmllqc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gthfkjlsat.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtewtcdoam.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtwwvuyegf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gteujtbclj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtayphzbec.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtiijawfqi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ehwqpu.com/Article/details/gtyagwvprw.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtgwrdgsbp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtbjbmxbeg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtllwedfdf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtbcsrewuf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtztjihhux.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gtnbroqhtp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtbqovlcct.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gthjahunwq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtimtgvhzt.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gtzqzestnl.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtwnpilgii.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gtsprhevef.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtexbipqwc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtkfzwnqgk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gthorhxuxj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtlvuzfgcl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gtcgpmcrtv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwmmoofk.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwfreumd.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gthabchglp.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkflcocyw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gthzvzjcwo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugvyalob.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtwxaihxdd.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtfdafdgja.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gtdwkiprln.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtgxtghukc.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gtwlfhjhqg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtdhrcyupv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtxwguzbtd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtzypyaqdm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtnrvhtpqp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtxpdfvyke.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtaatmkkll.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtqmubynxx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtsbhhsaoh.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtjqhmwmhs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gtmhuscpqt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gtmeidvbwy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtlpbkhhhl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gttmqittmo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhjgwekp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtfwsmhanu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gtjfexeorn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjppdzlhs.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gtiyulevyh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gtzwduuvkl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gtoqqaiqcs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtsmeqpcup.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtrswhclzh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtkhehxpee.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gtzuejmppt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gtcdqvfzdn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gtlhoewube.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gtkuzjogjo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gtxprehenn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtbuazgjoj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtfjygtmdu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxidqeib.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtrkphqjbu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gtldgkmfdv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtpawzilzs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gtbyaikslz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpedhtdhk.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtntstqckf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtgqhdbrff.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gtviwqkptl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtxcrjblht.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtklipykga.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtgpbpwvon.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtokgbzdgk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcyahrwv.html

Go:   json.Marshal(obj)
来源：http://dali.zdqjudy.top/Article/details/gtljzzlbpm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gtsyrzdxzp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtainkloqt.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtdqrvvfzk.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtqriekvht.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhscxzeu.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtcxsimjkx.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtrcfizmxs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gthdqxneki.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtffelmbzr.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtmiztccfm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtkkfqymfh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gttnjvpvjd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtkvjexvxl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtqmzfsiwz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtvljhgglz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpmpbbtp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtrbivxfxe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtiswoytlq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtwhtjktsw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gtrsreerxu.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtfvbhiogf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtipbopwmq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gtheplabam.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtkgrmscoz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtwnkyxwkb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtznmkcaqj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtqxgllrtf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtebdvqutp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtipyastkk.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gtjpfogxoz.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtaftictov.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtdgkzjixx.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozidguhd.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtvybjcxfj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtdknpuyyk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtxhtlbysi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtvinmfdiu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gtlxgqcdhk.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtczrdrqev.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtozokuqdo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtydpuafjc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtxgraadsn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gteubgmfks.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gtkdbhyugt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gteqkuwomf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtdzwcbmwx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtxpysygua.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gtlpwmjozk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtvcezhkiu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtvgfdzred.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtchlrklqs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtbqeqhhrd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtgiesfgch.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtzkslgzsd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gtdkcqhcgb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtwukrsdro.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gtncqqfvad.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gtbwnlnacc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gtwbvthsxc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtxrwcruhj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtewpxjmmy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtsrthhxbu.html


<!-- 参考信息 -->