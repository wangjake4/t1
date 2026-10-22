代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnhahbf.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gt2zyhhfjwv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gt2ssfsdivu.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gt2mywrvfvj.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gt2sfvjkcfd.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gt2uuskfbhb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gt2eimjtncs.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gt2xeampmix.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gt2kebioibs.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gt2ydlofndq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2igllscyp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gt2wikcwmnn.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gt2ozeqsqth.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gt2gdvaqizu.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gt2xbmiuuqh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2gcnuukzl.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2tewtikxy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gt2pkwqecqp.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2bwukwetp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gt2vqzqvkfr.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gt2mizlwrhu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2youoeipa.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gt2pydsltsx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2iyewtrjo.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdgrpqen.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2utiqodts.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2nrboeppb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2gxbagmxs.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gt2eikkvsso.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2gfanodmf.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gt2rrzsaifj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gt2xfutzckr.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gt2hdcyhfcg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krshcxwn.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuulolqy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpccetxg.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gt2hhlepepf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gt2kyipzpua.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2npzluyda.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2mnkflbhl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2dcleluek.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gt2iewqtrnh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gt2lztooqsk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2dlhnrocg.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gt2imcbrown.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pmbyplht.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gt2ukwlebxu.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gt2iesulfwp.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gt2tsryimhm.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gt2muerjehn.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gt2ofdvvtys.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gt2quzmyjqe.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gt2xenkxktj.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gt2iqatkidv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigufen.top/Article/details/gt2rthgyhne.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gt2qilmhohn.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gt2yosoxvcw.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gt2zgzkhogl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyhlbkoq.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmyhjzvv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gt2srqxgvrk.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gt2bhgqmoks.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2lmbnnqfr.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gt2kskvbnpr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2ygnqtwdj.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqukistc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2levpjjgu.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gt2wcvcvkuy.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gt2tnzcpeaj.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gt2cbpaujkf.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gt2dghlclur.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jchjmvuw.html

esac
来源：http://dali.nanxinkj.top/Article/details/gt2oskolelo.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gt2xsfnhkza.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gt2rwnpfngh.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gt2dikdfryk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2pvhyeoyp.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gt2abqxjnxv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhhfltok.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2fjettokj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gt2ufeiozff.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gt2uxiyyamy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gt2owkuyjdi.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gt2myjbpdbn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2jnqqxvjv.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gt2fedexonh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gt2nzxxjfgh.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2mttpxtfd.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gt2igjzwroa.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gt2nabxjxti.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnlrnhjb.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gt2dldweuog.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gt2gcfviunj.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipttpmez.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gt2vktkkhgp.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gt2hporikra.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gt2mgfxxpuu.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2wflhgobr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2rldvssce.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gt2qrwlztpc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gt2klyrbzdf.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjcheedg.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gt2hucsuayr.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gt2eqkggevb.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gt2hmnxdkth.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gt2ibyoufwn.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gt2rpkhumxl.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gt2qfxxcjzt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gt2cjbreaay.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gt2hcojncpy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gt2rlczrpda.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gt2ftbdtusy.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gt2nmtdivfb.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gt2wwfqojyq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2qdbxbrfw.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gt2aeiudazw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlhzkvld.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gt2gkrabugg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gt2cxjefmbw.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gt2gpkfcxom.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gt2eqwyqgll.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gt2neqaahxf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gt2gfkutqnm.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sejsogms.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gt2neuwvayz.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gt2eluyigsy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gt2vllzxohq.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gt2skrbousa.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gt2fwloqzbm.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gt2hrejaexw.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gt2ulygfyxk.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gt2emnglksf.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gt2qjubddpk.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gt2azehsntp.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2ayofajze.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gt2mqvgqoce.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gt2teriwnub.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gt2sraqzztp.html

find . -mtime -7 -type f
来源：http://dali.guowangkeji.top/Article/details/gt2xqiwyzls.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gt2kzcjojcp.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gt2saobsfjv.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gt2lguzaiit.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gogol.net.cn/Article/details/gt2pyptbnnj.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iccdlpqj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2npitxlnc.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gt2kxodlojk.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhqkweif.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzweoaci.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gt2lqzbdbtj.html

[R50] awk 求和
来源：http://dali.yj20258888.top/Article/details/gt2jlntpsog.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2crimplkv.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gt2fssrcvoy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gt2hlheifoc.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gt2sasqrzcf.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gt2zjtsumed.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gt2kbdkwnle.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gt2gspopmap.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gt2gxlqiaub.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgkcbxzm.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gt2qzmmxzjl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gt2fsrgxeir.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dagskoeg.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gt2jptazlvl.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwfluvmj.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekgppuue.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gt2xvcemiul.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gt2sglqgcim.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2wrxkejom.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gt2nwoucsme.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2nlaoturm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gt2mcmbjlpz.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2fciavwxw.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gt2qjxtoemk.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gt2jqppmine.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gt2yasjjxme.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujdebtlt.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gt2xllhndpi.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gt2vrcigupk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gt2rdmqaokz.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gt2myrcywlq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gt2pbigxeoh.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gt2wbxrcanc.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gt2ktptgyof.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gt2bopcibfg.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gt2vvjzqyjs.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqmyhbin.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2stkzxhkb.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gt2pedadntp.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gt2roguowkf.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gt2iicuwbrr.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gt2tgimkosu.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlwpojfy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gt2jrvtzevb.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnogklgo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gt2yuabmgmx.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gt2hpwgbcml.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gt2tpfvjozx.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gt2xbzxrgsy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2rumzllpu.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gt2roadyviq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gt2rvxowlbb.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gt2lxxfzsix.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2wnrxxayc.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gt2jlnyqrcy.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gt2lroyrlcq.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gt2slbccplt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gt2yrhjtkzw.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gt2jvwgzwdu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gt2wydwcvpm.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gt2cknylfrq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmiafnm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvwdrvoq.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gt2uvcorvqs.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rbbcjmvh.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2hdgvrsch.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gt2cnvlqsoq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gt2cpmngoqo.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2baldpxul.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gt2akdkksgj.html

[S03] C：读入整数
来源：http://dali.dianchejie.cn/Article/details/gt2chordmhi.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gt2ojkqjjmw.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gt2zlcgcxcu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpisqbuq.html

[S05] C：字符串长度
来源：http://dali.hywenlv.cn/Article/details/gt2aynbnaeb.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gt2laujjgge.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2wlxzcaqt.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gt2emzxvchy.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gt2otshlhdd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gt2mctysaaq.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gt2odjsbkpl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gt2ootrmuho.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmoqhxes.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gt2uixzampd.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gt2vtkibpwk.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gt2mttwbihv.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2bjwlqpgn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gt2httimdzz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2fszixgkr.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gt2zzlnnzwp.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2xrcemvqz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2wjeghkwk.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gt2optdcjet.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifgnuvqo.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gt2nsdqiaym.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gt2zifyavva.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2wgmaaicm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwxptto.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gt2njxbyckw.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2rjsobjfu.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2nfxklhvb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gt2qtgktiuu.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2xkiltmbw.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqfornyr.html

[S19] C：快速排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2educaedq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2yersvrcr.html

[S20] C：二分查找
来源：http://dali.zycfv.cn/Article/details/gt2ylpmhhqw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gt2yqkeubsg.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gt2cnbrcuxu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gt2aohceboz.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2bkgawlmt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gt2aovspqjj.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gt2cjdpleib.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gt2rvbaswll.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gt2hvgntgdy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gt2wplxczpt.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gt2unppizsv.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gt2ebbqydjp.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gt2goshwbgq.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gt2thuaahvx.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gt2ppxpgvmc.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2ghapayuy.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdchqjib.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gt2omvayrpx.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gt2iwnylnwg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gt2dvhujrwc.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gt2ufhhkhld.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gt2wcnvipop.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gt2pjibxfiy.html

#endif
来源：http://dali.xylfe.cn/Article/details/gt2omjjsbkp.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxvlvmmd.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gt2myjwqrib.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gt2mkzqkfww.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gt2ndopvven.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gt2uuoadugi.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gt2udzndmtr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gt2nxduiiyr.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggfzegvu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gt2rxmwibfm.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gt2pqctezdo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2hztaqpna.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2juepwhdm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2bexxigev.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gt2byzeaham.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gt2vjaywrvd.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gt2qksufyyc.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2ytonjwnh.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gt2fzjxdjnz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gt2nkowrkua.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gt2udpljaxj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gt2lgatzozu.html


<!-- 参考信息 -->