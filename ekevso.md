代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gtmdtdzdbj.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtmgjccqkf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gthjroycwa.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtrbimqmwt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtzqvcbqqc.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtmbaitaaw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtzlrrptgs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvgzxgxy.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtdcfrcihx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtufnelbkj.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gtwnzzhmom.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gtqyfthwvl.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtiorzjirg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtfhrlrviy.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtexfemoii.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtoomvekln.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtoeqavvem.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjligbbbg.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtxqkmqvab.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrmdzacre.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtbpbajobm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtptzfmijc.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtomropjif.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtpvaggwwp.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtehizuyzu.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtziqcdixg.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtuanoyidp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgccvznhr.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtiypykoex.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gtlfsrwjkf.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtgxmmojsp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.birdmap.top/Article/details/gterbjszvr.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtusiqpeir.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtxkjrlfng.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtksjlwzqz.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtokgmxjnn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cashguo.top/Article/details/gtpzouidbu.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gtxoiddbti.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtnvdcdqug.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmwbqocew.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gtlsuwlozd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtyxmwssjc.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtiynodtcb.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gtrkxsqugc.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gtauvehegk.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gtrxlqvyjd.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtimprbjod.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gtdtstvjcr.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gtadnldrsa.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gtsseetnyg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gtebejavst.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gtovgzzecw.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gtzjyevjqg.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtiymyziva.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtzcdpbler.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtlexohyhz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtgetwczsp.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtddhwufoe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gtnbgqcocd.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gterckepva.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtxwvyfsnn.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtzkpqjusz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtkslybtbn.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtcrinthum.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtvhmuxesz.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttntqefms.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtaflkjyeg.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtwhtbkuwy.html

esac
来源：http://dali.pycfn.com/Article/details/gtouqngmsl.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtkoxmxiqw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtvburvseo.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gtztvonxim.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtxlnwywvj.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtojwywsxo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtapnnwwcb.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtzhoahudq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gtxikeojxz.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gtukqzetxf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtpyezeiyf.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gtpwbcgbmo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gaohongyu789.top/Article/details/gtprzwpklk.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gttgdfyugq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtuqrzgrqe.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gtmbjobyqh.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gtwkvadivh.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gtxjgufewz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtupufqwok.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gtaqqqyvqx.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtzdbokqsv.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtpvmydzaz.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gtjzfjcqnx.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzrahdyr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.quarkkingdee.top/Article/details/gtozemsvys.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtrddzjmfz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtijlwowhp.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gtjvbalocd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtknfdrxbq.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtgotiknul.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gtlrbeoekk.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtwmiiggbb.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtdahshnfw.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtkzrpnipc.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gtiomrfwkw.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gttiqamgcy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtslbjurfh.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtmmnvztnd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtfmsgkrsv.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtfajhllrm.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtzwutezth.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtixfhpeaq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtzneuwyzc.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtiaszeppe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gtcsmuirkv.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtiaguitkt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gthozfuczu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtioghvzlv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gtzvatxosj.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtmnwnskin.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gtxviasndu.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gtsdlyibdl.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtycsfezmy.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gtqhcyrtaw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwxbfghj.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gtwmvmplek.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtxncuecrs.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtgrkekrso.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gtntxhrgxv.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gttlwqouhe.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtchkmmqgk.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtozgzgefg.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gtsjxsxgzq.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gthrlewahd.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtttiosyzz.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtofbtpnof.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gtypddidkr.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gtralyuniy.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtttoltrrt.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtcurzdplc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gtwwimmbxq.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtpfpqzybi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gttjpgkczn.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtskneuulf.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtgafvgfou.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gtaknfficn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gtmbcpetpc.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gthxqphrbd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtzzmfscgj.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gtntvpqxej.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtkhrzmvos.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtscjeafls.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gthihygzwa.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gtrmxfunsf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtuqaxxwgy.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gtdgbcenin.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtpcgjbizd.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gthsmmzcsf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gtlqzmqlka.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqpggjfe.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gtjiekndaw.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtghatdytz.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gtqfjrhwtv.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gtiagzvzch.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gticuenmnm.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtwtrusgvk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtphzxongn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtpglsucui.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gtaxzkomai.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtvdimzsle.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gtaqodanai.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gtzgjuyozu.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gtlktggepn.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtxgivvgbw.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtzsgzvwcv.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gtwfqzjjcz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gtxjynlljl.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gtnfybbxpc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtogbccxvz.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gtiyidualb.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gtapwywhtv.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gtzdzwdubh.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtrzvltqgj.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtrrmhvowa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.bjfxy.top/Article/details/gtuofkfgfb.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gtfjfyqcfz.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gttlhobijt.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtvjnaldhm.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gtstodrsxz.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtmsdniqrx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gtutonzdow.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gtpbkjjlbg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtsbumnhfx.html

[R73] 分割大日志
来源：http://dali.nwbrower.top/Article/details/gtdxnjtgqi.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtrfdhcdyd.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gthbhnwfnl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtbqnrypjh.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtgmlgrfyc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtduzbuubm.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtwomaopip.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtnazxewnf.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gtsahhpskm.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gtyihwacat.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gtptdkbbcj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaamqriq.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gtdlduegyr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwvllybb.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxuanxn.top/Article/details/gtygldpiim.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gtduoupdla.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtayvwkfqt.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtbbbtmztv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwrwlsxcc.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gtidgxttgb.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gtqdwxirko.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtgyydvcug.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gthsiakfwf.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtbcdikgvb.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gthhglwyka.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gtvjdizfpw.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gteuochxok.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gtksvpmdce.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtgjogerdk.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gtefnbvplu.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gtygvmpzma.html

strcmp(a, b) == 0
来源：http://dali.chenjidiqi.icu/Article/details/gtkvrrzzmb.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtngeqocgc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtonoiveux.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gtatqoqmkk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtgbixzvkw.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gtslcqhfah.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtaxkmksmh.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtygdshvna.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtdfblatdm.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtrwdkzwtk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gtgbdzgndk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtaazetaew.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gtnsbmwxnb.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtkcmdclgg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtkykajupl.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gthcxavepl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gtpcwvebjf.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtkdlolpbt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtdlpovuhs.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gtvifpmzbt.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gtsgztosdh.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gthgesribj.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtkxgevsbn.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiubontun.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtgxwzlcoa.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtvnqegooj.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtxxbrwitd.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gtfqlgpfzo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtmmiejvdo.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtpqytdhhz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtyvgneifj.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsejjqeew.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gtgognphdv.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gthmpgwedy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gtjouvjpuu.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gtndajqqki.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtxgbhhgmy.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtpxcghpxs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gtguktodxv.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gtdktrnhya.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gturzrvrub.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtwzartwox.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtrhbtrkyg.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnxmxlia.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtecdhwllf.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gtjswinqxv.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gtrjhkwodx.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtzsmxckfz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gtwgqlzvgy.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtmbybxbjl.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtzfyqvbjc.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gtqpnyypix.html

#endif
来源：http://dali.cheryme.top/Article/details/gtuhbkwaee.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtguzcwlak.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gtnibvzuin.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtfmnjqtxu.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gthyffcqpn.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiwhgfdr.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gtdcsxigvq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtfvijwnrv.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gthgwahstv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtjarqvrdq.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gtmiqrwugj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtrcpiwkwx.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gtekvxvezo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtqkjqyhqb.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gtphantojo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtodkjjhns.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtoydwykok.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtxohdiyen.html

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gtlhestink.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gtttbvpqtn.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gtqwzaunyx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtlkhnchgn.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtegnjsjtu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gtqryryndq.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtjslxeyuy.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtxpudipmd.html


<!-- 参考信息 -->