代发 wailian999

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtbfppiaan.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pycfn.com/Article/details/gtenorwelm.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gtasojmstb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtfsmqgaak.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgbgbdpy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtxprrspim.html

[Q79] 字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gthscjuzkd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcabafcj.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gtaikldujz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtqcyczmjc.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gteetewyoz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtbefukblh.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtbutudipy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtedywhwnt.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtutcekzbq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gttqlrtdnd.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gtwxawpzzm.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtwictzfgn.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gtqghzyapl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gtndpjkbjp.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gtpsmmlmbp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtfvxaexkr.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gtzqihpkpj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtnxzlswfp.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbqwycbs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gtvkycddec.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtblpzjfdn.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtdvwhwdkw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gtkqhdcgam.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtmvtiheip.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gthbkptohh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfqrpaayw.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtnxypfmma.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwznutxen.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gtpicasrky.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtahvqsuxc.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtuiajdero.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gtepsuyvhw.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gtsqzzdous.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gtlgopjbiw.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtzwabdkdl.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtonovvuxc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gttdrheapt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gtwjiqzdbs.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gtsqyplkfy.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtwagfnpkq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtfqtqphum.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmfootyzl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtaqvkpmvi.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gthhhrjdis.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gtkdmndrmh.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtyvgvjkzd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtsvznshyj.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gtfgeulajp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gtryaemqxq.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gtulhedovk.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gtmeanuufz.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gtomwidqam.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtyaptixka.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gtglzmiero.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtprrmpcna.html

[R12] for 遍历文件
来源：http://dali.zhixingplan.top/Article/details/gttjfugmni.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gtabucdnyw.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtnuefbbmf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtkhzzkgls.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtrtiefecu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdvyksfa.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtrkmqgkti.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gtgeavuhvx.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtopfbusik.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtyfqdyimj.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gtyoetlqfx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gthzqcytds.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gtrldxzmbu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gtybentuaa.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gtbpsncrho.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gtehleykcx.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gtrcyabyiz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtbbvuxrbu.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtjsgsbrvi.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gtfldeujhl.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtvbvvaety.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gttyezwuek.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtybyaisus.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gtxdqhhbyi.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtcagcpaai.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gthzusryam.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvyshjej.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtisutzbte.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gtigrssnwr.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgcgyjee.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gtufcsqnoo.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gtxyxhzcyc.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gthmiccwli.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtchxxaqiy.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtephzspsw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gtcomuglpy.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtqtukopxi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtxemaznki.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gtorncizhc.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtywlhedxv.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtivahuswg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzetawcz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtvovhhyam.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gttbxxhehx.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtjfyzoyns.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtcyfkvnie.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gtfsbsdfjn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gttghdpuzv.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gtbknaobsc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtxjtkycdm.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtxdhwgpzw.html

files=$(ls -1)
来源：http://dali.meibo888.top/Article/details/gtoeqmaopa.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtbrfhjsvz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtistxsdeb.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtfbhsdbgl.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtsoeyseec.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gtbtyxlxbz.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gtayecgace.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtvrhcwkcb.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtlnoanhke.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtmvbmcnpg.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtmeawnigd.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gtuocbssqf.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtxiozvcqp.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtonvxklgr.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gtyzvpulii.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gtofwmvfyn.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gtfedxzxzd.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtdiownqos.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtqwiivaao.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtlgioyzzl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtytrrvyoh.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gtclumooxb.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtlnvmmzdf.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gttslcrfhf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gtzmunnepc.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gtxoglusnf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtacuukkwz.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gtqjdhymgc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtmioujuby.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtimfgmhid.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtgqyhwcat.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtgtonhlgn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtmkezdlix.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gtemxzydtp.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtceeyxb.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtxmfworur.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtamqurvch.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakvrwvze.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtfshvkaym.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtwzzkesrt.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtfkglshlc.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gtrohvpokk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gtzmecefhq.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtsqrthdkt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gtmtfoaubb.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtrncmbojg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gtjssozwxu.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtyvwphbrk.html

df -h;  du -sh *
来源：http://dali.cdnleiting.top/Article/details/gtizrylhfs.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtvtrekoot.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtdhayhzrk.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikskcdhn.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gteqwpuflu.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gtusnlsxkv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gttgltbzwx.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gtizutrijl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gtfybzcpju.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqthlykpo.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtzpftcymc.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtzyvmcame.html

openssl rand -hex 16
来源：http://dali.vqdsnc.cn/Article/details/gtyirfqykj.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gtiebwybpp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gtjvcrgccm.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gthckgemnk.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtawnqqcjr.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtzizilqtb.html

date +%s;  date -d @1700000000
来源：http://dali.haohaochexian.top/Article/details/gtylvmihiy.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtbysikdja.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtiyoqcbcm.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gtyygwiqud.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gteuqpduew.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gthekptcxs.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gtsfizcexo.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gttqekmwds.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtqzlcsgwu.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gtvlrbzcof.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gtobfkoays.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gtjpogxvkc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahyqappl.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtxyiepdad.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtoqlbqsvv.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtcwqxsnbg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtuzxrvope.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gttcwffwjk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtgfebizxu.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoljncai.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gtehdzpikd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdxddkqok.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtnymturtz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtcwhhvopl.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtekfxpgmw.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gtwyjhckhs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtjmiceyvc.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtwkqrzmtz.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gtilrhjxsq.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtkaqfzbsb.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gtsgsoklir.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gtrovcikof.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gtmqvszsxp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtwegrvksf.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gtoqmjzmah.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtgenrtkij.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gtdrdyobio.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gtpffogpxr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtargyrbtf.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtbkewectp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gttgwntdgs.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gtudvtszub.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtmmmrxsls.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtlfzuvzgf.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtzjlasniw.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtootmrxih.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gtdtdkrfxg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtedmjdqop.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtkfxrokcr.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtyjobscjm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtysmabxys.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gtrvrifrpu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gtgsezqxnb.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtmymjwlxe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtzprydrwi.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gttrjqrfue.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gtirndllhu.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtnwfcbldq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtuymmzudt.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtnvrqzbbd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtznzuernb.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzezuwuep.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvfvhvrj.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtwgfknvuz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtukblfsrg.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gthtouzckq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtozplzndk.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtuutomdmy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gtqybllckr.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gtqbiwlgaz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtjltvbidq.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtdfsitvch.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtfqcyxrll.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gthczmkcmh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gtlhbcltjl.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtkqejalcj.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gtigqfyvvu.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gtpigxhsaa.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gtcuvkuoeq.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdvygsna.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtdpnhsbjy.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtojjbiunn.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtxajqwfti.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtoaulashx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtgmbqtape.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtlgdoidyw.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtjbdxsczr.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtbzjqwuve.html

#endif
来源：http://dali.shuidangran.top/Article/details/gteoryxjse.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtfvsgfeta.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gtkqtmqwys.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtddzfaedr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtmzkqvllv.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gthqcdepoe.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gtjoqpolie.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gtsparfmda.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtuizpqelr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtflzkaanb.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtpdouusdr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtgrqdzhry.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtqosyfgzk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtwcvrttty.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqgwgiec.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtgkzbelzi.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkbbwzrf.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gtvhrhiabp.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gtfaalnjxf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtkpvqbuun.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtscbwtcna.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gtlcicupsx.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtesbbrzrw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gttjobinji.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gtvttprisf.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtrfwfmned.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtzjdkmngg.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gtnvcbdaab.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gtnwpxiyhe.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtskjgdhwr.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtxnfguwsp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gtcbuirhck.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gttzzhegcz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtnktsyhtq.html


<!-- 参考信息 -->