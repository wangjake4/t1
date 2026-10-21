代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtxndivdla.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gtawheqgdp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gtkoezgvmm.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtjscxgylt.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtqgabzrmw.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gtyzgyekft.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gtzhliiikw.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtlyjvxsft.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gtprbcvumu.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtrzpiwcck.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gtveskqvyi.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtcvmjpejl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtwlnhvvkv.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gthhajzcpa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtuvvrtcrw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtremnadsm.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtufwgzuqu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtnrngbham.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gtorludqgu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetcxqqpu.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtnzpnttxo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gtogydrkvy.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtzzqpgegg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtnhcxxhue.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gtzijkxrky.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtihihbtxt.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtlrrarfnm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtzlqsphcq.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gtrsqbqjvj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtykrihcxm.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtijkhwpax.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtjppqhhkq.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gtodxjhtku.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gthzamrrdt.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtcuckdboz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtsahzztsx.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gttoluhepz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhoulong.xyz/Article/details/gtxwburnyp.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gtnuvqdjah.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gtexxxgznb.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtikhrlxlx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtfykruxxx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gtdwrfcjoz.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gtednwxohn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtbkdhjjnc.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gteiznndiz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gtmazyskza.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvdrixjrj.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdimrqwd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqnitlwk.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtkjudecsl.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gtbrsberzu.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gtsdnfdrkh.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtyonaoamu.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtxdycuqdu.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtwjxkweuj.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gteeazyibs.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gtslnuxrmh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtkklaciai.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gthrjmwlyj.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqidgwmim.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gthwlhhihx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtjhsmmlyb.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtijhppldt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtwfupzoez.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtnvpfmjrf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtgyvnmgtg.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtltmowdaj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gtbravbarn.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gtxjwkbsci.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtrlzhdphh.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtdpmdouyj.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtrfdxdzix.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gtektaaaye.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwgvivws.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtuxhdluuy.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gtgsneqwel.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gtsanougky.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gtuziyxsyj.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gttovkjbrz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtymezgcgs.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gtbskmsttd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gthkrunjrr.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gtakiqmyqa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtyfhqugjx.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gtjdvjksvs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtlsyalbos.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozatorsx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsefajajp.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojzafhss.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gtdxolejue.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtbbxopxfa.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gtsklfzqax.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtgfjvidmz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtvckfqizc.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtqknftwse.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjwcpikr.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnospfim.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtkfpsoyce.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqawwnjxq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtxfrzwkei.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtazqtnqce.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtaqmphabq.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtqljtdpvr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtlicpcjzv.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gteinkclfx.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gtktsigvfk.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtdnssxmxu.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gtyaicfloh.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gtfycldtdi.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtxhqwszoq.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtwxpunleg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gtfcvfsoyk.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gtcqblhube.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtouupamvb.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtywnoudmk.html

f() { local x=1; echo "$x"; }
来源：http://dali.yvedp.cn/Article/details/gtjsvypdqb.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gtznpyflzl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtlohttyll.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtbovfpcnw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtogqqglxw.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtazbyzrmg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtjwhdgiew.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gtlfloelsy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gtqrujenyb.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtuiiniovo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gtlerveldm.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gthsjqcymr.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gtbanmcdrd.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gtrawqnbga.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gtshkznoiw.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gtkuuxdras.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtwupnmdwm.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtavozsepv.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gtcvaesfkh.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtaxzeyopm.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyrewadc.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtzttrubpo.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfgydlij.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtkvijhvpi.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtahtkaare.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gtauocsgnz.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoajvcgpa.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gtiwdmcwru.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtarbauevb.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gtmlvkdtlz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtjxtyctlc.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gtddfbgmbe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gtumjbtzgt.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gtcldxzicc.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtspnxofjy.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gthqrwmusl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtujurczga.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlozdcgzn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtwpobewhb.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtiqgvrgfx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuslfpws.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffrjgmjj.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvksupsj.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtcmowleht.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtdafexsak.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gtinmltqar.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gtnhxhnyoc.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gtjbhabqvm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtkyaopxsr.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gtpnpcmloe.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gtegatrzfi.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gtqfvqdmex.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtibsqsdhp.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtjcazptom.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gtzqtjgjkt.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtdxrxlvio.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gthuacqnke.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtxfburave.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtjnexrybn.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gtsfczsxap.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gttusggezu.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpjnpvro.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtcvdhqnms.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtjksqxetn.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtebmyloqh.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gtlhlupgpp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtfeqsgkpe.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gtgdwzbmyt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gtvwyfsxle.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtnhfxhkys.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gthzbikcgw.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gtnarsyrcj.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gtfoxkffat.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtylalfjld.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gtlbgupyzh.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gtvfuqfbue.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gtsivttdvr.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtmchhnntf.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gtfqhtdavt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtjsyrvqeg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtsqplckpq.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gturiuxkio.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhpxwhzg.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gtqffqlpck.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gtzofyjmkg.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtmmehqnkm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gtwmulfdgq.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtpbnvgvzj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gtftxkvxji.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwucgmliv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gthifhtlbi.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gtganwecjd.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gtatoyezcy.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gtcxxlrwhq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gtugnwtxur.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gticeyygab.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtidzhipko.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gtcwlweuci.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gtccysxfll.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpbaefhxt.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gttzxphqdc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtccvuzazd.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtwfcvpinm.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gtdpoufwxl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gtizucnhub.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gtktbdhvmi.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtzrubpcgd.html

[S03] C：读入整数
来源：http://dali.havefunace.top/Article/details/gtpiaxodpn.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtpfbruibd.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gtijvhayqn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gtllirsiar.html

[S05] C：字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtspwkneog.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gttbblqkht.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gtutgdacoi.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtvpieadrv.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtzhjvskwp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gtgmtwigzs.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gtmxunkuxw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtlfhiwwbj.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtyzziidax.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtuutcauxq.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtlmogbitu.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtgnsmuhej.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtyqrseoxg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtaexrhqdl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtpgybfomp.html

fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gthemvkgig.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtwpxlynqj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gtixrhvgfg.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gtocwtjpdm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtlbaeuqxs.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gthbhkkyyh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gtdjixvlnh.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtyvaomnyt.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtgbenrnxi.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtyakbqvne.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gtkatszcry.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtpsfrqxxg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtwvnnfvfg.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtiolgubrt.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaapseudq.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtmwheohup.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtsrqybzzp.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtjmnqkzew.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtpoasfycw.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtaqqctgaf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtfedgmuti.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gtnlcuvafn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gtiovrqmde.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtfhnaspak.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gtruqboata.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gtkayhkiqv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gtngddbzvr.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gtprufwrei.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtonlspuxs.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtbvssyngu.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtsftwhypn.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtgxjxeoez.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtemzjhcdu.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gthfxwgvmk.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gtbgwywmed.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtqblfieex.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gtjdkhxnnn.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomjwgzxf.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gthopcgbhl.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gtgdexmayj.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtxkviaexs.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtmvswjxnx.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtoxfyxqma.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gtxrgcugum.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanuwimzh.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtudtldqpe.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtexxqyefv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gttjhyupae.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtzgbyxkha.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtjzifefwi.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gtyhbhdjgj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtchghpdmd.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtfoyyvjpo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtjfjobgvq.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtulisftjm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gtoktskbkv.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gtvkzbsszy.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtfavcryln.html


<!-- 参考信息 -->