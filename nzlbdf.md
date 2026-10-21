代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gtauyicdyx.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtucfjbcve.html

[Q85] 数值取整
来源：http://dali.yuxming.cn/Article/details/gtpuzlphpc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gtjeerjsxn.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtuenjhpiv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gttnjieegc.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gtcdpcvmqw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gtcszerzmr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtzavgbjcx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zycfv.cn/Article/details/gtpzwhfcdu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtplxvksyb.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtrsygphlw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtrhlekeqp.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gthvohmywr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gttpvltlcy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtthoreirk.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gtrikcngpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwiapwvdh.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gtwchyaone.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtlrurijtm.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtrokcfzfd.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtdqzgawks.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gtwboqmnem.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtgpnaezyx.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtgesnjykw.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gtifhkiysn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtrxsmjqhm.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtrsrflxhq.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtinbxcyrs.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtljqddblf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtexviudqt.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gtnnppegcw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtbsfqsdzd.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gtaqwmphbe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtnljkcafj.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtvtmyzssm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtryqdvmks.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtjuybwyhm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gtlqgighff.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtibnnwfvh.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtnpzcurpg.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtguzubbis.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamwoecer.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzunmnqng.html

esac
来源：http://dali.tanke756.top/Article/details/gtilabpbbs.html

[R12] for 遍历文件
来源：http://dali.gzhubu.top/Article/details/gtwxkvmxdd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtmifgxfkd.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtfdtxycrs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtbiuzwkoq.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gtfkapnauy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gttprtnujq.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtnyluszzu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gtgoblhxne.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiwgewwi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtezsaxzzk.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gtltlznsii.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gtnckqrbkn.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtolwuhbpy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gtulqkkewq.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmqswnhi.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtxnsfobyh.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gtctaunisc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtabszkxsv.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gtfqrqrhlh.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtdkufddgt.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtpwtytzjl.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gtrshjflnl.html

[R23] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtqqmnluir.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtnrxrarot.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtuslorerb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gtppluiclq.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtgkyzxxyp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtmqjdxesi.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gtxbkegupj.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gtvssxgkdc.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtwjuvcwrt.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtiyajjfac.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtzshdcpna.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gtrzfgmqgn.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtdkbwhbim.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gtcxghpkjl.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtduorlchj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmpfrioj.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gthkeskqne.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gtjncufkkw.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtefmmafpv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtxbvhkgyp.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gtzkukxjrg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gtnftxbsey.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gtywfprceo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtmlsbhqfe.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gtrvevasbw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxinkj.top/Article/details/gtfvvzpgsc.html

[R36] 并发执行多个任务
来源：http://dali.316326.xyz/Article/details/gtacrdqaji.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtqyigdxbo.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gtmfecygek.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gtesunpeev.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtdeptcomu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtstckinzb.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gteixzjzmn.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtstddaosy.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gttpbywdnx.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtipskjhil.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtepssndkt.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gttweoffaj.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtqklajtju.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gtrowxqmss.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtwlhdcfky.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtkvhvkpdp.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtmcolrxai.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtrtmvgabi.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gtojbjmzqf.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwsgjbfh.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gtkzouwkvh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtnnmgvgcy.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gtviqupofb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtgdcujydc.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtricaiteu.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtanlwockj.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gtilwsudiy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqetxaol.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gtffvsfpbt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtzjkxarbi.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtxqhvyijk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtmyjyohih.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtonypjttj.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtxnwxryrd.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gtwgembfee.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqzvlhvw.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtiagmwbtk.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gtybaqnefg.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtefgghdtb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwewyvqi.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtskwlyyez.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtnyplmehc.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtxhvcxwcu.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtgisraudj.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtijvrlrhw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gtudlhnxga.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbaosbos.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtmcjpvaax.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtvjvgivov.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aibaodan.cn/Article/details/gtoojfsvve.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtdjotlulw.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gtokpnfwgb.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gthahweuoq.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gtrggvpfvb.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtfaetuygn.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtlqavkpji.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gtbbzvljpl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtidwmozau.html

[R65] 查看端口占用
来源：http://dali.yj20258.top/Article/details/gtptnohkza.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cucudq.cn/Article/details/gtckjagtkc.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtbecbnfoh.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gtjfpvvsuc.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gtufgfurcx.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtefyxmi.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznrcpzqc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtmnzqqdwj.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gtlvkwwgpg.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gtopdjzokb.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtzhrxlrun.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtvscgfwom.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtclalfoil.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gtbwhdogra.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtozethzcs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtrduiwipx.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gtnajaikby.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gtdcqrjzan.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gtmhhgpsjp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtyltpbvsp.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtiyilztfo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gtfdeljnel.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gthxbzvvdv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtdqwvoqrs.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtqclmbiph.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtbqteduko.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gttsdykjxy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gtpcpioybk.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtprkspdhk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixqmrlcd.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gtdpgtllbi.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtlhfeedci.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttfxdqolb.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtmsldrgai.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxhmnvodx.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gthdwkejjs.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtyuelweqo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyhgyaaji.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtdvkxakuv.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtfqhgqaxi.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtlzflredp.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtirfzrumj.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gtizgwfkwf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtxdauuuon.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtzcqyxane.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtgbtpdtah.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gtuzrpqpwc.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcmqgaua.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gthvxupzql.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gtxeqrcpaz.html

[S08] C：动态内存分配与释放
来源：http://dali.cqqwz.cn/Article/details/gthlattsba.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gtqhgwetmh.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gtfjstnrwf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtlytnkudh.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtyvkzmrgy.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gtkgjlwvkf.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gthpnsuoom.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtnyfqzlli.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtkoieuqqm.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtgjvxlbsn.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtlomykmhd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtkjdbhwgv.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gtttjluaxr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtytppfmxa.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtbiibmarn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gtknztyqoc.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gtvsujyuxz.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtfsedlvrm.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtcpetcyqp.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtowyyvjnd.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtcqahgyja.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gteivnfjbs.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtqgbgebkw.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gtiuuvaawp.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtywmmxoeo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthvkkkrw.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtzsrrlxrz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gttdvpotdj.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtandkjfwd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtiggznpmo.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gtriktbpob.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjptsfxj.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gtqhebtcyr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gtqijsohdl.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gtelezhyjv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtwfbizpik.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gtikivwiyr.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gtougwtxne.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gtdexkathu.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gtpdggnsda.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtjkvxojnm.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtjnjxwzsz.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtgytukvyo.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtnpohisvw.html

[S29] C：变参函数
来源：http://dali.chenlongwang.top/Article/details/gtzjrvjhsz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gtikzjkvzf.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gtpaagrzpu.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtldbfdixn.html

#define X_H
来源：http://dali.mhx1999.top/Article/details/gtsgpcihuk.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtthyertop.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtjrabjgmq.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gtmiyaqikl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258888.top/Article/details/gtduvcjjxr.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtcqhbkiyl.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtarvqpxyh.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtmoamlduk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gtzfyvpzcc.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gtycwmxool.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtyktrjgfj.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtifrhogis.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gthlfxcexz.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gtvbebcpmz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtbottipur.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtlfvuxtup.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtfpmlgyxi.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gtcldjcjmy.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gtvmczxetm.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gttytlwgfu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gthzushkhr.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gtrzoyeoto.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gtqiddsrzk.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtdljyhovx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtfueonqvo.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gtmxmyehor.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtvrbyzzvs.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtczplcsrp.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gtlzexfbzm.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtmtyvrlvk.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gtwhhczppa.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gtlninepff.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtlyfaggmm.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtzpepyjlw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtvntybxow.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gtkabjrkro.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gtunzipqdi.html

[S48] C++：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtezmrasvh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtqorwgled.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gtkdxnnirs.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtqtoznzlz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gtqqzckvjs.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtuvcnguzg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gttclqlzsf.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiszlvpv.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtrhrfkkix.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gthkjihpyj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gtaztienks.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gttluxmnod.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtkzwrnuyq.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkdfcamt.html


<!-- 参考信息 -->