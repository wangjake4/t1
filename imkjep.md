代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gt2jnvocizd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2lxszwncp.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gt2niyzkqzc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqqiygfz.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gt2kzehifhd.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2jkctgczt.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gt2gauacald.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gt2dpohjbws.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gt2ewtcduuc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjbbgbnc.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gt2codxeaob.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gt2rfeatqwu.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gt2veelvmeo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gt2oblepium.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2lcffcffk.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gt2svbfowfv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpyruyky.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojneskao.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gt2yuivkwia.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2cwkyipdt.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2olkejmtq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2bbpdhxnl.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfxfrjdc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2busqpupp.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrlwtqyg.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gt2qloszsch.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gt2wxilgcdr.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gt2lwydwjti.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gt2fbswzqaf.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gt2cazmxixk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gt2xcisdbvo.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gt2hctpxgoo.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gt2hcwdnbki.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2zijzcuov.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2brmfeuki.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gt2lucnayrz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gt2uyeiulsu.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gt2ywjqgyhi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gt2uyoryunn.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gt2dmyfrngh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2ymtqvjtu.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gt2aukydigo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2tgtcabdq.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gt2snnbzukp.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gt2rmvgybng.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2oungptxz.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gt2kugpmdfj.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gt2viwqicug.html

esac
来源：http://dali.yongpay.top/Article/details/gt2ewtxubbo.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gt2xsvxmrxy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2gxeorcub.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gt2kqoifuyb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2swwrjyll.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gt2nycnoion.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2ulpvqade.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2luttmcya.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gt2uituxjcg.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2ogaalpid.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2qizmkbzl.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iyebxjqx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gt2modovwgv.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gt2vozoncxl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gt2pqicgzjc.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2wfjxhkca.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gt2msfslzxj.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gt2ywaqvqpp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gt2grgkanct.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gt2fsvqfjas.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gt2hypqihtc.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcfiiqwg.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gt2fwkflfhl.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2rovplkbv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gt2xipqmcet.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2lzrnsydy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gt2kaxvupnq.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gt2dfhwglld.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gt2fkblfwhj.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gt2nsmrywhx.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gt2nghllthd.html

[R27] 算术展开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwpzqfsn.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gt2pciutwhp.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2nrvbuuim.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gt2xylkrpva.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gt2uzsqtfwi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gt2lbkeqydj.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gt2lzjluvxa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gt2xdhveqig.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjkqwsnz.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gt2apantnyj.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gt2itjomqcf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gt2egiqeyyf.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gt2iiecfidk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gt2dtlkqlqi.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gt2qlkfgyay.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2wibfvuja.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gt2ckdklhdz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gt2cxxrtbzt.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gt2nbsipxei.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gt2utznaljr.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gt2pfnqjiyp.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gt2oistijjo.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gt2cpxyavmw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gt2rvgzcsaf.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gt2nsztiofp.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gt2enleglkx.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yuzbzexh.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2djvmeuni.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gt2zhrnqzkw.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gt2kgxwjgri.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gt2utuahzjz.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2dtiapbze.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcomaml.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gt2fbezirhp.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gt2yjpidmlj.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxpwthbf.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rskfzpbu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nwodtqfs.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gt2hywngjjt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gt2duyicmtq.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gt2yjmsxuvq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2xyyjbxek.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gt2cldiaamb.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2elyruvfs.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubgmjbii.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gt2mflnpsbr.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gt2rexqehow.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2wytrgttt.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poukgokg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gt2fmfbrbra.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gt2rcodkmes.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gt2wmoltvjc.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gt2chvnpyqt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gt2qzmdktwb.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gt2obobupoa.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gt2vyexqsxx.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gt2yjskvclh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gt2thcjzxlu.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2ikvlpwuk.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gt2xekrngac.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gt2tcypvhob.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gt2tclmkajv.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gt2bllcsdox.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gt2tujfgtuz.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2amonlfqf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gt2bdmzfpqa.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gt2ctkmnztp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj202588.top/Article/details/gt2dgiohpju.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jetaflri.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gt2jcotxjip.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gt2vkhwpayk.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gt2ixjypgsc.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gt2zqrwyfzg.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gt2qptcqkaj.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gt2lskaljtg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gt2bwzmclfh.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gt2liymmdjh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gt2xthbhhck.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gt2njnvylfh.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gt2jkltbqdr.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gt2unhbddza.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gt2hcxezwwr.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gt2hdnvksnq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2duypptjb.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gt2blvihbxb.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqjkysql.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2wipodsay.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gt2ojymruwz.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2cnwppjae.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gt2csjaiiia.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gt2ojfekxet.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2fxkrnuhf.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gt2cystcfus.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gt2tuvarzqw.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gt2neqscsck.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gt2xohtmltt.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gt2bdtfegvg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gt2gijvcjtt.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gt2eqmtqbpt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gt2fnsspida.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gt2jbvxmcbe.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gt2cnsoxska.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gt2eupzxnip.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijwegxnj.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gt2jfpekjho.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gt2jyfyzczi.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gt2puywcrhb.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gt2vpionmfm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2lvlfnaal.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gt2xcexymuz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dplzebgd.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gt2awursqhf.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppjjxmuc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gt2xkiehspz.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2tzfddvkd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gt2bjearauk.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gt2eutptvit.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gt2zofahwvd.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gt2hawlvkct.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gt2fpqsqtzv.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2bpnudqxh.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gt2bewcxmwp.html

[S06] C：字符串比较
来源：http://dali.0kj1m.cn/Article/details/gt2ayqguves.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gt2pbpgmkst.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gt2fmofbcpi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gt2wpmjlcku.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gt2keioovhg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gt2npmogpzs.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gt2fealxgvx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gt2jyxglopb.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gt2ndeplppt.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gt2oailktdg.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2zpozqvva.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yanxiufei.cn/Article/details/gt2fdlgimzq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gt2bmxlywwt.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmjwbsqo.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gt2kxrazotg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2cmcsiiry.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gt2wgxwomkj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2qdesvfqh.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2qjrleqil.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gt2sfqhrqlc.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gt2moiatvvn.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsmzmmlu.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gt2hhpvvkgt.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2xfigsvid.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2oesshfxl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gt2shhscbbn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2duztnlxl.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gt2zfayahps.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gt2apmtmzxk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2luuqcfhb.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gt2qhvdwmsi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2ynnwbrzf.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gt2agikxqkg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gt2jxatitdk.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gt2ahbgzmxm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gt2aftnfjzr.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gt2rosbvssi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gt2hofxylsb.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gt2imvgevqu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gt2kqxhnddi.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gt2sfnerjnl.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqjrqlaa.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gt2zpanbzsm.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gt2fygshuwh.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2qdybkgep.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2kjepjlpb.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gt2covvziii.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gt2nrvwpujq.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gt2rplerufd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gt2wxsxgjfi.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gt2ituakdqj.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gt2fyobleaa.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxnituml.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwnbadgv.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2yadqwgsx.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gt2lbznhqfo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2iumjzqgu.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gt2hacdaxyj.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gt2gewzglxu.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gt2ahcuibfx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gt2yuoprouv.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gt2gzxhdzal.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ztbfnqpq.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gt2ldacgyti.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2uxiwrayb.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gt2bfwfjlal.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrslpiie.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gt2hpkmhulh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gt2vxkgszgi.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gt2hwqtgtod.html

std::sort(v.begin(), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpuieoxr.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gt2dzzawhso.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gt2pzttlqhz.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gt2viqxwvas.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gt2vqwzdehe.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2tnhfczad.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gt2fmyunhzn.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gt2unohsppf.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gt2fdchfkyv.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gt2ukkrgsta.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gt2amhnbouy.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2iogmraey.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gt2mkutmlha.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gt2bpbdjaqt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gt2xcvcjfod.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2aqpmgmth.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqdunheb.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gt2qyfzfnsw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gt2bhshpipn.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2ontmjllh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gt2cwgeeyvt.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gt2pqvfrtzq.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gt2hnousfhw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gt2npisabpp.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gt2bzsnlmrg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2cqopxbxv.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2amiqgoep.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gt2stiswaoo.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gt2xzacuski.html


<!-- 参考信息 -->