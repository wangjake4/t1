代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtgdvxtfpk.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtuipyghyx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtlsbahhdz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtkaoupoqr.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gtxjmfuxzo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtjfznklav.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gtxbcdqowk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gtqtvjowev.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtjsnlpenk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtiwvqirps.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtgadnlons.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtcvmfnx.html

[Q80] 字符串截取
来源：http://dali.zhengqikj.top/Article/details/gtixtdxber.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtyfqgrbjo.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtilfswcnj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtruqploig.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtelkfgmtf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtblcgdzpt.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtluzmscrb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtltkfgcwy.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gttwvktuwx.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfabffnqm.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gtnbsvxlkv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gtmmlqzput.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtspykgwhq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtymqxzklk.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gtnipdhixb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gtokugvisr.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gtmgfeegei.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gtjehsspis.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtdbymxcvf.html

[Q89] 判断表是否存在
来源：http://dali.aibaodan.cn/Article/details/gtfvllukri.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtxzpmwxgd.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtnswbujdt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtpqtqkbtb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtywaxljlq.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtacdtkvbd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtecvrkgxb.html

[R01] shebang 与严格模式
来源：http://dali.iojbl.cn/Article/details/gtfrgnbskl.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gtvfpbnkkp.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtyyqttsgr.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjmfkclk.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtqtogqlat.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gtjnbkzosx.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gtdekdgtec.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gtvvuogktn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtcmscglge.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gtcfqrgtdc.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtecezbxiq.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtarjligju.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtyzylvsls.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gtkbroyhbt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbpzhnea.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtrqnxiqzg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gtylxiimwu.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtbjwunfqw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gteqjojdta.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gtgbrekiop.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gtsqdbqhhk.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtfibsmgvy.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiywdthfd.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gtlsbbayyz.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtgeppmomt.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gtgpvszwin.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtgdevpjje.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtxetliygt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gttuegcrtm.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtrefjgokv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtsijlrnja.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtihyyiaqb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtiaoiyycf.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtogziidzk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gtahebocac.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gtnimgcayz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtggyqbhla.html

[R17] 数组定义与取值
来源：http://dali.chenzaomai.com/Article/details/gtjhsxbrcp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gtuqdpcvno.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gteamqorrm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtskophcal.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtobqgdeyj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtsnsbuloa.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtwxbkxe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tianlin.xyz/Article/details/gtjgulqtau.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtraflpydj.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gtoirdifhu.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtcyunomwb.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gtsgschkye.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtmwzepdlf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gtbbcqxvyx.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtkpdptdfh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzthhkedj.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gtqcjlgzhx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gtwsingqgx.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtdldxltgr.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtppgoxfrs.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gtecweahmf.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtdtzzexzo.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufwpiauo.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gtjjgxexaf.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtgorwpzam.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtppeewnwv.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtpryzwojn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtkcfwrgfa.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtwgokojed.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtvmdqnfwv.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtrfarsllk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtolcfyeks.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtsuclvxai.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gtwjrtmeae.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtwdkfhydy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtemyhuxfg.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtqtxdvgdm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gtefktysre.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gtacukqobt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gtcaxvvhgq.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtlckvympa.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gtunrpvhzr.html

[R38] 管道串联
来源：http://dali.yonumen.top/Article/details/gtmxucfqie.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gtqauwxxsk.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtblxgunxm.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtrvhvtzgd.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtnxodpqlj.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtavlkclbb.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gtpuemfbrg.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtpolwsfgg.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gtpkpsygix.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gthwppdsjj.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gtjirrduxx.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtvmdmecmm.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gtkufnfpeq.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmzbbcan.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gthhkkygsd.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtedkqmrlu.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gtrohxepjd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtwotonopj.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtjlvbjgew.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtwlkybwqu.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gttgvvtdbc.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtnlpqjudq.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gtcrqoptwk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.snrcjt.cn/Article/details/gtoxicplxd.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gthjfiarwi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuygcfycd.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtddqculxf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtuwqvcgcq.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtlugvrmxc.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsvuxilz.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtorvkdepf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtjnfmvgxk.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtlzpzpnpw.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gtldraqmhg.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtoupeqvpm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtmimbckvl.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gtmcmkfogi.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtinjglecq.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gtjsumnnjm.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtxzjjznoc.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gtacayubws.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtnpgttruq.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gthxbwcerb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtoieegsoe.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtpoofnpgn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvxobrrc.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjkgxscx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gtuhmmwtro.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtozvcruqe.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtpcedrvza.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtsxburxio.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtvdzmvwwb.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtwbfjrynx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gteyvxpqif.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjoambkt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtyhhpwlie.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtcsiesqgi.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtpoftfneo.html

[R67] 生成随机十六进制串
来源：http://dali.hywenlv.cn/Article/details/gtziviqvjq.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtsdqyaema.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gtcculitjc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gtmudzrvpv.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gtsfznoknv.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtorwdmjhf.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gtgwlgryed.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtfpegircr.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtcsdckxgb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cashguo.top/Article/details/gtvpxmtzpm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gttszecbzd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtjunhiisd.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtahmkxjko.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gtgzwiyjeh.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gtkqkxcfjv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtgfxpxvqn.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrrjswgo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gtshtlegbf.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtimcgovpa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtbvbhaoxb.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtssfwbdry.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtdikmpwqt.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gtdfoagkct.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtdlppboqw.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtbmvjofqn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gtdflmflwt.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtyugpdabb.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtlkpycewh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyhuavcmc.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtqdjitoga.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtuobasfzm.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gtoegqmebh.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtbvcmbhbd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtulgoedzw.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gtbdavnvio.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxepclmv.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtcupzeoio.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtckrtaauo.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtrzikbdre.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtebkznzqz.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtjwvqqycn.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gthksbdsly.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtgnlbnydb.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtagehsaid.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gtavgnlhon.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gtfhmfilfr.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtdqufgnnp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gthssdnwpg.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gtivgdwisv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtmpsifrce.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtemrdbnyi.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtpjriydgg.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtpslawswj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtjcwzyvaw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gtbgfppkyg.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuedknja.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gtptytjpgf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtgetsjzqw.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtayofegdu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtgrprktwt.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtisgpbqtg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gtfntywnnr.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtfiupypzm.html

(double) a / b
来源：http://dali.tianlin.xyz/Article/details/gtelalvhaq.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gtvoygyhzh.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gtvtfaywzq.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtvemvpjfr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gtdyiatiyf.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gtgljvcyzb.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gtdbbyfvoz.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gtjjbgzbva.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtdrojzykx.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gtvaxorkrr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtrduboetp.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtokvgtxbr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtqxxvmruv.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gturpziokp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtwrhhvrlq.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gttxriyaze.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtjcxcutoe.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtzmakemzo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtpnlqovpw.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gtyilllhuo.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gtmpyedbyt.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtdftdacrg.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtefasyoql.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtwnrmnggd.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtoyagcivu.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gtewnmjimv.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtspcoucgr.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtukcoggks.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtfrffvgdy.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtedbetpqb.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtabxwkrlx.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtwuckeztr.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtaqurcroh.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtbvcsbcnc.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gtyxigllng.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gtpeuiydls.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gtzwckdtjj.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gtdkmeqslc.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtnarrtuuz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtqxmowqfb.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gtjirroybw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtkxyseevn.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtqhokgqam.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtwekmmlpk.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gtyektcnff.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtwmzkolgv.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gtysvhflmg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtqzfzibeb.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtkhkdzary.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtxoothgqq.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gtrvcshlut.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtyfvbtofc.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gtutugqzhh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtiychastc.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtypbmzjmy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gtnypjkutf.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gtsxhvrcwh.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtwdmufhhi.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtipiuxvlc.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtaponaezm.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtfoqhadii.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtbbruzqmo.html


<!-- 参考信息 -->