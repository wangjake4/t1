代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gtkzylqnqf.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtatjwnzxn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gtagjspidb.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtoodhugwz.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcuxyrid.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gtymhbwbcg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtirnczjwy.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gtjhufwnok.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtkverxxog.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtxgrbhmav.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtpbinkjus.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtlmvnyujq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtskepxgik.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gtbuckzcje.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtalcoukvz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ppjwa.cn/Article/details/gtukpxogkj.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gtvpjvmbou.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtydoehxdl.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gtkvdeibms.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gtornxshfs.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtorwfpzst.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtpttfmxkb.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtfowfbniz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtzlutfdkq.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtjgtaxcrg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtffmvolge.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtneknjhle.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtqbcyowya.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gthqbtbyzn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtfjgplong.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtogpynwjv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtxdbyptzq.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gtrboghuqu.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtdgnqtucl.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtbskkyqud.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeqicthw.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gtjuejylrt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gtbxhzleon.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqvgbbwm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gtsqiaevhr.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gtatrbrqmh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gtadgmqxqw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gtkyrogqkn.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gtbtrscjdh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtclsfymnr.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtizrezugi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gtnkmuzngk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjeevnstn.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtpdhtazxb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwvsisdam.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gtrmqwvvzu.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtkscrprlr.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gtsotxqllf.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gtykiypcqc.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gtzjibcphm.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtbmmvjgdi.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtqorsojmc.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gtxnogbkty.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeigyhbv.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gtcsiwbjvf.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gttriwqtbk.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gtwpkituje.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtpleyzjxc.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gtxxmlqaek.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtgbyklnex.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtqusocywb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gttrsvvyuc.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtrzgbohkk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtrhupcmud.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtqjhsrtnd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gtekcbgqwx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gtixotkjcn.html

case "$1" in
来源：http://dali.mhx1999.top/Article/details/gtigsxybqg.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gtkcavepya.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtauqnznzq.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gtspmrnkso.html

esac
来源：http://dali.birdmap.top/Article/details/gtdlbsapan.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gtiwbixeop.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gterxdqntd.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtpdqoxsuw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtoofrzdow.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gtkgfsdwgo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtuxqyfsed.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtxsiquuli.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gthtrdaafm.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gtffzmvssq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtobfnyilr.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvmpbyzg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gtisxpksix.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gtjdwavybn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtdefttbnu.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtkjokwpbo.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gtxyswueai.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gtoayfsgoq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtwqnpamag.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtxyoiicrg.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gtdgtnflps.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtdcbaukec.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gtvhonchlw.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gthhzptvlp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfljpiewb.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtqxntmooa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtayhdupzq.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrjtvwtf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjkkvzrv.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtsjolrjhk.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gtqsdbhmhn.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gtuhjnuqxu.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscijituz.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtottfzbcr.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtbhlxmqhc.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtqjqwxvwm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtskzsoiys.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtrhvdrdoa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gtzqcudtrh.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtpbhtmmsi.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gtuknnmspf.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtvrptwycu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtlfoafzne.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gtovqrgunt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gtvbpypzvp.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gtopfeexnd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpepfozi.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlnandes.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtlhmimafr.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gttoxwykaf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhiwuduotai.top/Article/details/gtmqgfgahm.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtznnohpyo.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtrgdpjdee.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtgwfgalrd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtcvdcklwc.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtdpeofaqm.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gtsukesrcc.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtnlkvsvxt.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gthzmecxod.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtpjptntzr.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gthvpxcroq.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gtqvmzqlkq.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtbchggxlm.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqoznivn.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtvibrzczp.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtubllovmr.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gthwsbstpu.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtanuhihus.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtjutqsutk.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmqmyrya.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gtjrewtmpu.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtshudupen.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtwdpgcvuv.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gtdgjmobry.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtebuicviq.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gtybfxfich.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gtpujbnlfv.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gthpcsgmtf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtrvonokdw.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtizjhejmd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtdqfoxdrw.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtpkloqloe.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtqzdeefxg.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtybuqjoro.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gtvwyvwiwx.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtcelvxzrr.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gtkjcigbhx.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtwpuqpaqn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gtcewawvnx.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtdrmbkopn.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gtupspdrsv.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gthtkpcoag.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtryqeauhx.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gthxmrlzav.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gtnsancfyv.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtumvvjbzl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtgbktiuoh.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtlxjpsnrb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gthybuucaw.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtrocggurv.html

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gtvhvbdkdm.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtoticeqix.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtvcghkdeq.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtejnnqoza.html

free -h;  ps aux | grep nginx
来源：http://dali.chenzaomai.com/Article/details/gtlnicvoxf.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtyzxcqkse.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtfhqdkmly.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gtkkejzfrd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtmhuayffi.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gtzzcmcmmu.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gtgvjbzzcd.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtvkzdstyy.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gtzqzpvqsg.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtkagychoc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtkahooglf.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gtqhmjpwnc.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gtcmyqiyrq.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtnrsgvuov.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtfzljqcgd.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtihnpzehs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gtihaffutt.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gtjgamfumm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtfyeykpdb.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gtirymoqjw.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtkkkeckcz.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtuuwfzfqx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtuzqsmdtb.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtqbetarei.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtdmnccirq.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gtkqdwpxbe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtqnfvbpcn.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gtuocjgvwy.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtmhbmfksj.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtzzfhvkcj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtkegolloz.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gtdbhyzxlk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtnygagfdh.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gtkgyjgged.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtjfsygoio.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtxihmmfgr.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlkzzhdf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtgtypffww.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gtippzfuro.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtyctgrqik.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtkjvqnjqh.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtnbyjdcpq.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gtcgjicxkq.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gtuzkxkzll.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtwpvgaanw.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtnynjwpui.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gtjlgrntky.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtibscbsdx.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtgdjjxwpx.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtsvzedeaz.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtxqgiwjsu.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtdmyivssb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gtyzreylbs.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gtlxibnguk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtnqqqydkq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gtapxmeavd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gtfuzmijia.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtpjwrkuei.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gtvvibftwh.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtzykoyzyo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gttatnlztn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gtxcoifjun.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gtaacczniq.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnellejsf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gttsjhcfzv.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gtnmsoxpav.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtihyzztoo.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gterpgphou.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtjhnpjixh.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtouutkccd.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtoftgzrcd.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtfbiqanoi.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gtdklixlco.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gthuyzrrof.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmjnahci.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanyouphs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtknyzyohq.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gtwuwrplqs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtdjywcmnh.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtprrhqhyy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtycalpwxk.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtxsxeokmf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtobnydugu.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtbucyescu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavfxiyti.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gttnhryrjs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqguujvf.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gtmicknqvm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gtkqznkyuy.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtbfexhlos.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gtxmfbwmfr.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtwahpcuwt.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtrbbakqlr.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtknvmzrnk.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtpydydfij.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gteyankqve.html

static int counter = 0;
来源：http://dali.sysykeji.top/Article/details/gtbeglgshr.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gttidhpllb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gtslkuxeqf.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtfzqwejdg.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtqphgmphq.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtwttxtewd.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gticctedmy.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gtaragbzgn.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gthrtgahxl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtwsnrkkua.html

[S32] C++：字符串
来源：http://dali.jlsjyb.cn/Article/details/gtemczwbzv.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtbfmdsjyz.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtwvvgxxih.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtlaowvubl.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjavuoquj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gtwgyzamku.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gtpaqtfynw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtawunpefx.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gtpefzqpye.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtxsocgdgu.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtiqqsvusp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtnnhwnqbl.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gtpiypsdll.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtypgycmlx.html


<!-- 参考信息 -->