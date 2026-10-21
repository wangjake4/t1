代发 wailian999

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtveybayvi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtbxfrdrbe.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtahwhceuj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtjxlmfrmz.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gticwvjbpg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtwkjqsklr.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtvdsozdst.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtfueiuuqc.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclzdkbny.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtubjavbdk.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtrfzdutdz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtysjvhkdn.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtahqxeipk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gtsiiwrcqz.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gtbxuiywko.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtdugkffan.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtykmhmfpn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gtpbxadwbi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtwscowosf.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtvknhncsy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gtufzemhvy.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gtviiuvtvu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gtpymjgdta.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtcbbwtpik.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsquykzh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdiefzwip.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gtnaoqiecw.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtontywgvf.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtgfrvdazu.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtjxqwnrya.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtjrwdhuiw.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtghxejdsn.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtonoirtei.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gttoozvprb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtzbdrednp.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gtncuwlxip.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzglsnfmt.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtxkbcflfr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtfyiscamz.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtvsvmgqxv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aibaodan.cn/Article/details/gtbstjhctv.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtpvgfhhey.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gtmbmupweq.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtcpkwqqyd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gttkcsqizm.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gtfkuwywwf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gtzahitely.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheejitec.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gtdaupwrfm.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtthczdyhv.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtacudxrsa.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gttpqwetrr.html

esac
来源：http://dali.yonumen.top/Article/details/gtkrufncvs.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gterygkrog.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtwguxxcwe.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gtqyeamaci.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtmbrazunm.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gttjhcqkat.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtfvwqiivm.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvymflqo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gtgxejmcai.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtnigvfrwt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtudwjhiep.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gtpsccgtsv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gtxvpstkoq.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gthxqndbnc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gttfouveze.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gtgvuklwaf.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtcehdwbjg.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gtqcuxwjzq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtddaknahg.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtyeozdyvl.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtgrndgiqc.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtuulbqhvt.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gtsolwfpxs.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtjucjbaif.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtsxcmlkwm.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtpboqtkju.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtiskkiaza.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtvdepvxbd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtezviuyde.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtnppmssem.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtekzcfcyi.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtthotzhby.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtbhbvcexh.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtuqqrhduw.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtjqkovnhe.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtfvraqvxe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtabpxkhoz.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtqxkzjuae.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gtvikccavh.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gtxxpygvqo.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gtvwgpmdsl.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gthefgljzw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtgqrlgcfl.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gtjvbemyfu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtrzoawfsy.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtzggdkxfz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtosyhcgxj.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtyihhlkay.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlldmtbdi.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtyplsemfq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gteahzuyuf.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkoxbivfc.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtnrxakwsg.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtfrdykhxq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtodsraawf.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gtqtuhrzoe.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gtrvesivho.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtgaepaxhx.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gteljaglom.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gthjuaxpix.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtzeroerps.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtcqnfypfk.html

wc -l < a.txt
来源：http://dali.wangdashe.top/Article/details/gtlsnnihes.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtzukdtijn.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gtjvjneurg.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gtqenjvwpv.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtitqsibmf.html

[R45] 批量删除
来源：http://dali.kuanghao11.cn/Article/details/gtwhraqkgx.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gtnvostxnn.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtrdacftcv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gtjkcopejh.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gtqezlqscl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gtjhdzrzay.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gtkpwmmloo.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtskciwpay.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtnwowlxnz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtvzflvrvt.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gtnzwkszlg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtvcqwmjmx.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gtvuiniemd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gtkpicgpno.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gtiqgbmihh.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gteuravlnb.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtvuenhcia.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gttztoefhj.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtdcutquqs.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gtcflyauhz.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtlpztehgi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsntxoift.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtnwwjgrza.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtwkdnjhty.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gtxkgmywmg.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtvjidfrek.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gtyytlohdi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtjhisklew.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtfotjcqzy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtbgvkpcqw.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtznjtkykd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtyrvdhaft.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gtjpqmbaum.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gtoviyxbzr.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gtocdbciin.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gtccnbpfjh.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtvxwryvcw.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtgqhexkik.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtjuyuhhdq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gtzmfwkrer.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtipnwtwjw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtmogxotay.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtbgyzmzfu.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gtohurqwfn.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtdbancjby.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtizzpqwmq.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gtxdmvdfgq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtdmxtwcnx.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtlkkllzxt.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gttvtlimen.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtwvauthzl.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtjoaegqdk.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtidyfynjw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtfieavoml.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtasgwftns.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtcmdyqijz.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtgbdutrnv.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfpdrdmb.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gtvsjtissw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtuzcbxkbc.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtjwfrpcia.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gtqtbukhnk.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gtvpbaektk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtggeeppit.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gtsalmrwmj.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtovsdbjiz.html

[R78] 交互式菜单
来源：http://dali.ybcxt.top/Article/details/gtjddtbcdi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gtvfkopaiq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtndiyqzxr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gtntnmtzou.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtmjurpoir.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtiswzyvim.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtlxmgnjao.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gtzsfvyxyq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwunpnsmt.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtjtdmkxgj.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtlbahldjv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtkmrkooah.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtqcxmjhti.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtvjvhxjgh.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtfsbwqolt.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtnsnxxaey.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtjcidebdz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtzmqjfzbg.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtpljjmmyi.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtlgimhaue.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtltrenvcr.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtnfscgwuf.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtvqnnjkda.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gtbxsqbjva.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gtfqekrrrz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtdizcfzel.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtqabhmvcq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtaeejyxgb.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gtsgsjsawv.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gttbxrxsig.html

[S11] C：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylhuphtn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gtnbykgwhd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtzdajhbyv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtzdxcthzu.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtypbzswsn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtisjkoovv.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrnhqsnl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtgoakcjwz.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gtrfztbtoz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtyrnjtnln.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtkxeahyes.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gtydswrcdr.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gtpnufpals.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtsomalzkd.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtoaekddul.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gtzfbchige.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtnsflcgke.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtiezglxbg.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gtkxhldojn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtshmspbxz.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtxuzodemh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gthdinucep.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gtkagfnglm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtwthnsrcb.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtsnanthfg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gthtmgjypm.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtrxglgqfs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtkeedtfiw.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gtxnwottam.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtboeprgiv.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtzpmpsocv.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gtrekiffcf.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtavrysqke.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtwbvyqh.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtkbaygmbs.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtktrjgvts.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtpgxunwvq.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtewzjhwcv.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtkdkktdgw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gtygabecaf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gtapmsdhrv.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtqgetogkc.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcikbturj.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtnsxnuajb.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gtiurgfesp.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtthccjlfi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtwajrpyxb.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gtranoqjpb.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtllluejwa.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtoshqytdt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gtlihwrozo.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtvhyzcpbx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfdveqbzt.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsgnrrhq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtytgwjwag.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtintzipog.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtnymgokkf.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gtwiigakef.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtytmonwsn.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtyuhezfaq.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gtxznbtdvn.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtnkygjaxx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtptlrkvvl.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtmnqgtgat.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gtyeliunva.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gtdxzncded.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtysmhbguk.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtluhlrmyc.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gtovzrpxco.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtgummtsyh.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtdiqnwpnx.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gtkkzizqst.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gtomwtgrqc.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtdwzkbgle.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjdjhqws.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqifvmyz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gtltugatkh.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gthdgerlvz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guowangkeji.top/Article/details/gtgeovtomr.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gthydtuzrx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gtgsjpgjyq.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtkkjaunmg.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtnlokkcfr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtmpdetfjj.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtufyoahoy.html


<!-- 参考信息 -->