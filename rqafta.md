代发 wailian999

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gtsumzrzsq.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gtakuggowu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gtyntwtqvs.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gtwqligfqh.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtqhmznakg.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtvhpemzyh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtsnrixfks.html

[Q74] 强制使用索引
来源：http://dali.tianlin.xyz/Article/details/gtfphzcejs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtmlryqpub.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtfyligred.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gthtbhafhx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gtwylwrnvn.html

[Q76] 按天统计
来源：http://dali.jqgufenzy.top/Article/details/gtqdnjsuwh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gtapyevfng.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gtvmtwnizy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtnvtkujap.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gtpwpsdwdn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gtrjtozxiw.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtuvpzcuzz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtpbptwxxb.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gtcjzsmuiw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gttuxugaex.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtidsojhql.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtdtfrgcan.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gtmnwljxzn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnzzjjmi.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtfbjhidax.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtgbzzjpfu.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gtwcmvaduw.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtwcolnjdx.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtjklppffi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtenbvsgzn.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtljrumuog.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gtfymkdolh.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtxtzracii.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtxudrtouc.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtxexswfyj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gtuduksaxy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gtutltkwyo.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gthggdzvmg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtcmdkaoxr.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gtwfqyfnnu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtshqylpgq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtigspnanh.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtarveidbj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtogqjjjex.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gtzuaeimuy.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gtoqagfcoe.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gtnkcpryzi.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswdpowgx.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gtblewxdrd.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrsvligq.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktztpekl.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsjaydcn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtbpfdkklp.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gtrwlrmttp.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtobpcelxz.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtdnjluvwr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gttasydefc.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtkosyhrrw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gtmjcmiotn.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtmuxpjygx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtbcjupkce.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtgbmrlmyn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtzluwdjnn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gtjivpiiyk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtlwijbsdb.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkrtnfjx.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gttoeblffq.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gtaljsigms.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtydxfdcpu.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gtukjmtufi.html

esac
来源：http://dali.cdnleiting.top/Article/details/gtnxrgezbt.html

[R12] for 遍历文件
来源：http://dali.aizwys.cn/Article/details/gtwtjfeivq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gttbkbohsk.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkilvxbhj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtbbyleynr.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtubragviz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtqvbzcnlg.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvejbbsnq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gtwkhebbmd.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gtrzkpmyfh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtrnpmcvme.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gtydwcrzdz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtcbvnpjib.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gtxitcyztc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtxdqhznvn.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gtijyansrt.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gtsgjluicl.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gtoxzgrxkd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtzpcabbmk.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtfnssaopk.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtmhdmcvzb.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtntmofmrd.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gtvrrjkzeh.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gthejcoufr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gtucktsgcp.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtzdqqkwof.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtrpdeokle.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gttkqbdcbw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gtcsvixqfh.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtwnxoadpy.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gtmojqydwg.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtmjjgrupr.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtnupxmpne.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtfppnuvyi.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtgmyjowqh.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtijkeugjl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gtodwhjnyj.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gtlzutuhkp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtullpcspe.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtmcoxciqo.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gthqyhvrkr.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gtuhrltgzo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtwmdnsznm.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtoeuzqqjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtqrgwjdbu.html

[R34] 退出时清理
来源：http://dali.svipenyu.cn/Article/details/gtwdtzyoyo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtuoodnezw.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtgdqirulf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gtipvawnxb.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtvznrvtuu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtaaxmhpdg.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gtjmokepvl.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtyhexvkvz.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtdjxwoogu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gtqthstrve.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gthsqmfcji.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtwsnubpfh.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtqjjdohud.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtjcamwbea.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gtbxulgaed.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtpzvjmmst.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtzdspzwyc.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtervtvzev.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtznhagroc.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gtxrhclmkj.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtelkfiqap.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gtnhjgxhla.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gtancluvne.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gtwsehcizz.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gtgikqjtgt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gtmpedulfh.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtvbrnuwpa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtwrbwurgh.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtzzeckmya.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gtahglmrxb.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtjezsrkah.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtpthqvtyu.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gtkwqiczaj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtegsiemsl.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtehgzlgxx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gtbyqproat.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtpslomohc.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gtsxrnxgmx.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmxmrnkp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gtxljbtmsz.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gtlkfpdijb.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtesddocoh.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtuylamitp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtrqslvlou.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtsnbfyplq.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtvjmzhaes.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gtyzlmrdad.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtxwxafwnx.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gtuerinhur.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gttwqcvexi.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gtefqrniah.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtkgtdiwaq.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtixutehwg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtcqgnxbae.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gtpvwwicrr.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtnoouznzl.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtidrqtlaq.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtuuhnqaor.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtpyuihxlb.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gttuqvdadz.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtopxtrfcd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gtoolziyoi.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gtdbxlaert.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gtnwrbnakf.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtmckrfakp.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gtpixfgzcr.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtubrfpait.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gtmqkblgtt.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gtfuhhwnrl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtkvffqtzd.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gtcpcjwont.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtouoffuxy.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gtjtfzttfy.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtcipmzdvt.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtenwbxsow.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtapuboqwy.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtvzspuyjg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtsgygeqer.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgwzaxao.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gthxnuymwi.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gtgaorgpgt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtzuuzkiuz.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtepawfvja.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gtdolnrziz.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtbvbgsasj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtzqpvdooh.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gtkltxxtcl.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtaynowaxh.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtqdivtull.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtstlhijvf.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gttdxlirfp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gttyghqkfn.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gtzpjqmrlg.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gttbkypavm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfhvcivvb.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtrqcbxkpw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqpjqnqac.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gtaifgilng.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtwsagehdx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtzahtpdfv.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtszjsrcur.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gtmhsprkfl.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtjzuitrza.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gthrxxaeic.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gtmodmwbhe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gtbirmhuxu.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtfqvvteem.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtybqfaktj.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmniyrfsp.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtvrlfyedz.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gtdljdqzyd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gtmydbafxp.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gtvhozgdbp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtnsxpuixk.html

[S09] C：结构体定义与初始化
来源：http://dali.daria6918.cn/Article/details/gtjiqqhlji.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtvaursthj.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtvieqazyb.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtsxayrmqy.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtkbnpbjrp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gtjzkflkix.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gtntkyzbcy.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtdhabpyan.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtyzpkgjnq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtvzljzcpx.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtipvlupfe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtakwseeqf.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gteuxygles.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gtllvlzcjo.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtheucvpke.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtshismhye.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtmvjcmicp.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtfxcszzyv.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gttlwydjvw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtasyipvxd.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtykapbpyy.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gtsqrivsng.html

[S19] C：快速排序
来源：http://dali.daria6918.cn/Article/details/gtorcvxygx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtwfoerhhq.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtihslrmrb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtsozhfghe.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gtlbknnegp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtqpirqwya.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtvtjxzzdf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gtrghfxcsm.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gtosgkgotb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzwupogs.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkujxonqx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gtsfftolbu.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtjcbxpmom.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtbmqjtzok.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtnmwhiabo.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtumrluoyk.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtxfyujytq.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqilhjkcw.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtjlcxmgyh.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtcmenvlbr.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtwjuuytdp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gtifmugplr.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gtkhjncubm.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gtncgwxkac.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gtrmgnqcpg.html

#endif
来源：http://dali.nwbrower.top/Article/details/gtbyzwqqlw.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtnqaoshtg.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gteoskrfwo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtgjhchqcb.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtzkbdoyeu.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gtjlcqlrjc.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtalqmbtpz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gtacpjqjhw.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gtsozntoyv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtwqnzwcjz.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtlvhjsrnu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtxmacleoc.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtlhexcona.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtklwptbyg.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtoknrxtxa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgufenzy.top/Article/details/gtmgccznfc.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gteuumammi.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtbkceqsmr.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtfkkwmylp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gtjdmhcdso.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtwnbxeoiz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtszcsfdyd.html


<!-- 参考信息 -->