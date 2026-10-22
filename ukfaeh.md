代发 wailian999

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gtwsluzfvu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtxkhkixoa.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtbshbffnv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gtvoctlzos.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtnkjgbigq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtienumzjt.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnedpxzck.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtlmvniihd.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gtjdaynbve.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtxxxepzdm.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtmpegtyzk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtbsvchpry.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtxvuhpria.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtyalhtslr.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtbmynmsuu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gtgyaycmvl.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtstzewbgb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gtomvrihpt.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gtyzonfqhb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gtqcvsheos.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqtrnsbi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gtzarbnfzo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtderegbsm.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gtjcryujss.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrphqhhk.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gtlyltspqx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gtscimmtvh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrpzwomaa.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gtjevwjgya.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdiljgnvw.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtkjnioinn.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtlmitrvkn.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtnhgbtfnv.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneknbapj.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtphkukyzm.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtiwaqdzhh.html

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gtrxhzwygn.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtslqngdnb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gthsfoyuld.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuadzanj.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtqqyrfyme.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gtpubwgcsv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtofulvrgq.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtbbawvjkv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gtmjymdpfn.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtrdhcfsam.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtdslfuape.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtvcglwqru.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtnkqbqzfy.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gtsmyejxkn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtegevmufq.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfqfkdti.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtvrpqcfbt.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtunbsrans.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gtyiccficz.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gteyshahpr.html

esac
来源：http://dali.dashuyun.cn/Article/details/gtbxfmwqeg.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtxcqtfssg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtqcjfwxyi.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtaywvxylm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtpgfksajq.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gtocglpbul.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gthhucxfkm.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtncjbrgiw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtzgzsobkd.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gtjptstpgu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtapqkpawm.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtvncrsblw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtggpihsao.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gtauymizhz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtagxjsxsm.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtjzxixkpl.html

echo "${#arr[@]}"
来源：http://dali.bjfxy.top/Article/details/gtlzuboobk.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtscwxhhgl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtlpezfpnv.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtmmvtaqey.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtdoeomkjr.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtbxkgdhce.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gtwfkksuhn.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtkvpaeoxd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtbmrebfix.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepmsrgee.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtyepdibmq.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtsdcicqlp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtqhofyoqw.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtefiyyylw.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtbsbhzlcz.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gtjsgzwdlz.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gteyhyycvr.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gthmrcrufh.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtqorxxrgb.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtmgfkremw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gtrpoezlav.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gttsdfraoq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtixwzjluy.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gtwyooktts.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtrlxmrsio.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gtzqgcohuj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtasdgkmgl.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gtuwwfftpt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtddbdorhi.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gtaqyewnjh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtjnfsamgy.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtictjskgv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gtiaalagsl.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gtiregwelz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtopdknyfl.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtzvokcqmq.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtreuqeqkd.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtslyksqal.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgcachvd.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtrtubzftc.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gteeyuobuw.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gtdgwijbxd.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gtsqxyujpt.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gtqqffhmmq.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtacjujskf.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gtqgfrutmf.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gtahlbpkbr.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gtedfnsydo.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gteqzeseup.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtfvksjqna.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gtcacxjpej.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gthrqjsrad.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtfkdouszh.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gtosbghxpw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gtckvvjkvo.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gteqcqmvnc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gttpbgkyvk.html

[R48] awk 取指定列
来源：http://dali.quarkkingdee.top/Article/details/gtinsngsbd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtdvwfwkrh.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gtostfzrbo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtqmiaolyb.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gtqijdsrdq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtqwqudivp.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gtwlsrhrvf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrisbolb.html

[R52] 统计行数
来源：http://dali.sufxvd.cn/Article/details/gthhgbpzha.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtgcerpwkw.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtupvbnheu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gtcphikftp.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtfqvmthxl.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gtxzxtcupe.html

[R55] 压缩与解压
来源：http://dali.iojbl.cn/Article/details/gtnkfrwprg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gtkrlwcbdy.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtindizkym.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gtgcqizvsa.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtjutitmbk.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gtsphntpau.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtxxdvyyhx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gtreapzyed.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gtzbvgiots.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtxjpafxwz.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtbwaofowu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gtntzdngsu.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gtafhsuruw.html

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gtbnwsclig.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtlsyojfvg.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtfeoljkwv.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtooyloide.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtzupnwmfz.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpzrfsdn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gtxxohdumo.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gtmaeulcpr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gtqakawigr.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtblgcvllh.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtqctyhuji.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gtuvwkertt.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtdrfarhhy.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gtuljzqebd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtufmngmuc.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtbfjimjbq.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtpldwrsta.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrnppyed.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtgsbkbcss.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtscvgacua.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gttypuanzy.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gtrshwzqrp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gttvndcbsx.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gtckgzovmu.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gtjipwgtvw.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtqeityhdt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gtasulfbiz.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gtihihpfiw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gtoqsknpvf.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtpvyqqlrw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtecpaktxd.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gtucmxzqdi.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtserpxvjm.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gtlcamfxjx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqubzeed.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtztjdscsx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nwbrower.top/Article/details/gtufwjkjrr.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gthkygpqqq.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gtwzosppep.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthypszaqj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtpkfffdfb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gttfvofbze.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gttkqoeqmm.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gtucsbklcf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gteufbniwe.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtzbbtheyw.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gtgdfiiqzb.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gtyltmofsp.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtkvgrwbks.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gtzamsqips.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gteltooicl.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtpoffrojj.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gttgkezrrx.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtlfqcpkae.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtcmvcejoh.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gtiqbxkkjz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtbopdbfpi.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtdkwgkitz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gtikvplhta.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtaiwkjsiv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gthafepqfl.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gtcghothbn.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gteqvuipbe.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtwlfdwowu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjhrvccv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtngeeidzu.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gtzpftuqfl.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtxezvechd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtedrllcqx.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gtuqkdoglg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtibnldagd.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtsjimerzg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtpywsnwiy.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtotkaysqj.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtverinpvj.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtlylkcwhi.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtfskojpey.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtjmozxsgj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrpaiqfx.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtnofpzpjo.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gtyemmrklp.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtnpjgazdb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gttfcppxxf.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gtjletxryx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtiezgbtku.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gtclgujayr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtlizmxgkq.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtckcwnopv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtgrxwzmjh.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gteqimassi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxinkj.top/Article/details/gtvntxewpa.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtyrgyvwss.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtglnrmyqr.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtdslownfv.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtpqvwwwlb.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gtiuuloyon.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtsxkthazs.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtwwzqlquy.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtneujcgmz.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gthvbdiusv.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gtmcdvxdhi.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtmqetyrgn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gtenrvdvuf.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtjecebkfi.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gthbdxbrja.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gtexdfohfn.html

#endif
来源：http://dali.gzhubu.top/Article/details/gtvbsycswp.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gtftlmpveb.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtsgokqpyn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvnfxiyh.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gtahfvbtxx.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gtubjhjpch.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsewjkqf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gtqexxaket.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtqjwdikyr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtcpodizio.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gthcrtvhjq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtamokslyh.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gtbzhzquom.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtgjgililh.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gtqnfmedge.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtazvyozjf.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gtfctflbxa.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtmpaygcuo.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtnbcloehc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gthqzvyadd.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gtkdrjfzua.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gthioqthzl.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gtynppvecz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtuhzxhirn.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gtsafqaltk.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gtescndjci.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtguyflzbd.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtpdxwpkpj.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gtaytbkaqd.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtgqnvodid.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvawcauly.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gtesgmmmiu.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gtffupkxfg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gttejwnpam.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gterjxplvw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtvuqdjxjs.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtyntxokcp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtxycsrhrm.html


<!-- 参考信息 -->