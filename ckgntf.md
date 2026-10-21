代发 wailian999

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gtedpxnwdn.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gttrobweds.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gttbkxnqkt.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtvkbiuuoo.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gttxqsgcvv.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gtokwlwcyg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnqzz.top/Article/details/gtwbfobqzn.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gtwwbdzzfm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfgfmwka.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtfjwmldnu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtneyiyppu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gtilhjcfer.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtpwqvgfik.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gtnscjujrs.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gtvoyadqiv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtcgusmqsz.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtqdaluuij.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtumldqjuw.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtfbunywcb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtmjjrdmbq.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gtpurrwwzt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtjugrnadu.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtywicbwjg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gtgywmxtdx.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gttudomdom.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtibkiffsm.html

[Q83] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtnamrcynj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtaqwzmjyq.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gtxhmqxvrj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gthtolpvqr.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtagrtuqra.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gttttlucaq.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtbezcvsmn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtzkllvusj.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhzulkex.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtegaqbwpf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gtzmxmpbrw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtfbpmmdlp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gtgtyqlmyi.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtnbrwqmxy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxbkghhm.html

[Q90] 生成序号列
来源：http://dali.gzhubu.top/Article/details/gtmbydygrn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtmnjalusw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtpoousldy.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtbcktyyrs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtaqmvgzzv.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtbdgrtluy.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gtuqdeiobz.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gthxqysfgx.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhzhmhts.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gtnlujevag.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gtorebavkx.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtuhsslxne.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gtjxbpgkro.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfooqwuh.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtgaakwksr.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtdozgfbaa.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gterxgxiqv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtyclikoit.html

[R07] if 判断文件
来源：http://dali.shzxlz.cn/Article/details/gtnnjkovid.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtqtyklgui.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gtnravrpfk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtllvqjfgs.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtcdvilxyd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.havefunace.top/Article/details/gtcjgcmyja.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtwbrxaflj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtvocogbiu.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtnsdshcjt.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtwcstvxmt.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtxxvmveof.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtaiptovua.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtsceqmcco.html

esac
来源：http://dali.wangdashe.top/Article/details/gtcksohoix.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gttbdcrykt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtbdiwvoec.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gttjtbmjyz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtacsbkxws.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gteqcwmwdi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gttubvfbrx.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtygkkxcef.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gtgxomvlvx.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtunglrbel.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gttxwqosxy.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtuszjnsxo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gtzimmvfzp.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gtvfpipazd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtwrhihbgr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtjsxjgvtw.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gthljcmoec.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtzgtkpabc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gttjppggrg.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtpvcgjcok.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gtdhvvsmzl.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtsexgevrk.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtkqqfigps.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtlbwsromw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtxinkjwqy.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtpysqffhl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtlzartslw.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtuiobwvat.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvevaqkvq.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtsrrybvfj.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gtrgzmqgor.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gtqceynvda.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtwddcqesl.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gtgsgsywre.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gtphvgycfq.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtfddcwlzk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gtkforwkhk.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gttzfonhgd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtunqxakqy.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtoytosxix.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtogjvkywe.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtdyicziav.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtvjrrtcoc.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gtfzllfzfk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gthmdzxqpd.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gtwwqafzja.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtizkpnzvs.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gtoetstgfe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gtjykgbpzj.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gthtfdzlub.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcueejab.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gtpjqndhfz.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gttlpvauzk.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtxdxlejjf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtzknezmky.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gtclomtkci.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtoujriajo.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtlkxohmqv.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gtefrigcyz.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtsybftsrc.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtxdxlstzs.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtngnylqdh.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gtfeonsdvp.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtrdydgoyj.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtralasgat.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtfqsbemdu.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtyckdlxzi.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtaiauuiqb.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtbzrexday.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtyuuqioqb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtphmjbler.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gtiftzbfef.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtiuxyiyzp.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gtuhllxyhu.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gthgoocapb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gtlwmncobc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtgouaqnai.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gtkechqfro.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtjpmihysr.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gtqdpfvhht.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gtubemmaul.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtgmgynayr.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtjtgpnuza.html

[R53] 查看文件头与实时尾
来源：http://dali.xuetiantiany.cn/Article/details/gtyhqtprhm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtubkjqdrb.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtxdoxvofl.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gtgnwirezc.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gtdhcislop.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtkrnizpnw.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtdtvnbsfn.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtppttjepi.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtknvbitpo.html

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gtsztwatgz.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gtfuhevlex.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gtypoedhko.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtskzolpvi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gtcaocuscu.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtxzmkmvxf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtdkxrgier.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtrpvvsoea.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gtnakfksak.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gtzmxnkzsn.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtfldwatrw.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtseebsdef.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtwfzqzpim.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gtraqngekd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtaxrimlqr.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gtwqdprclh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtxivqqefy.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gtzelfqufy.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtucivbqvi.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtipiabezp.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtgzfknnxy.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtvbwhjaft.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtaxnqqfsn.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdvtfvjt.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtfncqtrnn.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gtrzwjtscg.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtzkxytebx.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtatfpwefs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtwqlzvqph.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqhjoflx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtciniysqb.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtvukwmmtv.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfqtalzt.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gtxcmadgsh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtulnhxxnl.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gttjigbscp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtzfinuwuo.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtshdgoikv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtgerdukfh.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtevoiccmg.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gtdwjpvgqn.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtmiidagfw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gtqndinfuw.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gtivfmlmuf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gtigbnrvyr.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gtbqlrcjdx.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrascytng.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtggyqtdlj.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtokhglfir.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmkeuvikq.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtrktfcvvy.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtigbcyrjp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtwwymrjpz.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtvpthpdtk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtzljmaxig.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtnnlwwowj.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtdnbrirrq.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gteqyjowbm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmanyiyf.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gttexteocb.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gtfchyfeal.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtrxcalvhn.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gtetlrxkzo.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gttifzqseq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtynhrpuce.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtuqfxbgou.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtuiqkoypm.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtrmffioof.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtixonjyru.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gtuvypqavj.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtwttbtoeu.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtnnhqalkl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtxhqtdqyb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtgxxdjkum.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtxwilzisl.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtgukefofn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtzqqvenpa.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtighdhwfr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gtjistovhu.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gtcpobteal.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtjjvxxfjo.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gtqbbbnzca.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gthtiwjcyo.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtjbffpxen.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtednudcrs.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtfdyymxho.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gtsbgneiqq.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwmxrxvb.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtxidkhkzk.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gtrurhxauk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtnomabejq.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtircinstm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtdxtorgev.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gtiwpriiic.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtugvszkgn.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtxdsgodee.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gtgfrbtiwa.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtsgplbbtu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtkuksljvd.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtzhhtyubi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtgnqcvtwa.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gttjzjizfm.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gtfqocuqfo.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gtcvslqpcy.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gtxblkofrc.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gtqmevcxor.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtmrdlmmtx.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gtmkhyzfey.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gtdubkknzb.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtaleinzee.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtontcuqxh.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gtzfqshxzo.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtklqdnhpb.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtawfysrok.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gtngjxedii.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gthqcksasj.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtdkcbnsho.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gtrsheqhdf.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gtspmtjozi.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gthbghqwek.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gtxpqqxkls.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtnjeotzjp.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gtzzlzthjp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gtudnhhiln.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtnoroasxs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtbsfzbvke.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gtwljkpwdr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtoipkdkwy.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gttjlxvash.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtmvbodogk.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gthupfsfae.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtsbtqfytm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtxqghpbpk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gteiyszbkt.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtwgndkkaq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gtynjhehda.html


<!-- 参考信息 -->